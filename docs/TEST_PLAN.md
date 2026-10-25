# Test Plan — FOUNDLOST

วันที่ 21 ตุลาคม 2026 (Asia/Bangkok)

Target: C:\IT_PROJECT_GitHub\FOUNDLOST ณ working tree ปัจจุบัน (รวมงานที่ยังไม่ commit) ไม่ใช้ผลทดสอบวันที่ 20 แทนผลใหม่

## ขอบเขตและวิธีตรวจ

1. วิเคราะห์ routes, controllers, schema, environment presence, startup dependencies และสถานะ Git โดยไม่แสดง secrets/ข้อมูลบุคคล
2. รัน Node unit/integration ทุกไฟล์ใน test/*.test.cjs บน fixture PostgreSQL engine แยก ครอบคลุมปกติ/ผิดรูปแบบ/ว่าง/boundary/auth/roles/claims/ส่งมอบ/audit/queue/retention
3. รัน Playwright ทุก spec ผ่าน Edge Chromium ตาม config จริง ใช้ Vite + API + PGlite fixture เฉพาะทดสอบ ไม่เชื่อมฐานใช้งานจริงสำหรับ CRUD
4. อ่านยอดและตรวจความสัมพันธ์/constraints/images ของฐาน local PostgreSQL จริงแบบไม่เขียนข้อมูลส่วนธุรกิจ
5. ทดสอบ startup/API/database persistence ด้วย PostgreSQL ชั่วคราวแยก หากตั้งค่าและสิทธิ์พร้อม ห้ามใช้ข้อมูลบุคคลจริงเป็น test data
6. วัด performance เบื้องต้นแบบ bounded request ในฐานแยก ไม่ stress ฐานใช้จริง ไม่ใช้ผล queue submission แทน real AI latency
7. รวมผลราย test case พร้อม source, preconditions, test steps/data, expected/actual, PASS/FAIL/BLOCKED/NOT RUN, severity และหลักฐาน ไม่ข้ามกรณีล้มเหลว; rerun แยกเพื่อหาสาเหตุโดยเก็บผลรอบแรกไว้

## สภาพแวดล้อมที่ตรวจพบ

- Frontend React 19 / React Router 7 / Vite 8 / Prompt / Leaflet
- Backend Express 5 / pg / multer / scrypt sessions / Google token verifier / sharp / local vision pipeline
- Database PostgreSQL 16, Docker postgres port 5434; pgAdmin port 5050
- Automated browser fixture ports 4173/4181, workers=1, timeout ตาม config เดิม ไม่ติดตั้งแพ็กเกจเพิ่ม
- Role: unauthenticated, student/owner, finder, Staff, Super Admin
- มีไฟล์เปลี่ยนและ untracked เดิมหลายรายการ: รักษาทั้งหมด ไม่ reset/checkout/format หรือแก้ source ระหว่างตรวจ

## เกณฑ์สถานะ

- PASS: มีผล run จริงและ assertion ผ่าน
- FAIL: รันจริงแล้วผลไม่ตรง expected; แยก bug app, test harness และสภาพแวดล้อมหลังสืบสาเหตุ
- BLOCKED: มีเงื่อนไขที่จำเป็นไม่พร้อม เช่น บัญชีจริง/เครื่องมือ/สิทธิ์ ไม่อ้าง PASS
- NOT RUN: อยู่ในขอบเขตตรวจรับแต่ยังไม่ได้ดำเนินการ (เช่น soak ระยะยาว) ระบุเหตุผล
- Pass rate = PASS/(PASS+FAIL) ของกรณีที่ execute แล้ว ไม่ใช้แทน % requirements, UI completeness หรือ AI accuracy

## ความปลอดภัย/สิ่งที่ไม่ทำ

ไม่เปิดเผยรหัสผ่าน/token/key/ชื่อผู้ใช้จริง ไม่ส่งอีเมลหรือ push ถึงบุคคลจริง ไม่ส่งรูปผู้ใช้ไป AI ภายนอก ไม่เปลี่ยน role/ประกาศ/จุดฝาก/ชื่อ/อีเมลจริง ไม่รัน migration กับฐานใช้จริง ไม่ทดสอบทำลาย production ไม่แก้โค้ดแก้บั๊กจนได้รับอนุญาตเพิ่มเติม

OAuth ด้วยบัญชี KU จริง, SMTP delivery, production TLS, AI precision/recall ที่มี labelled dataset, Figma pixel-perfect ทุก state, load/soak บน deployment และ uptime 99% ทั้งเดือน จะระบุข้อจำกัดแยก ไม่อนุมานจาก fixture
