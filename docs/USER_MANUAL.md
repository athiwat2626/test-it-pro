# คู่มือผู้ใช้ / User guide

## ภาษาไทย

1. เปิด /login ไม่มี navbar บนหน้าเริ่มต้นและ login เลือก “เข้าใช้ครั้งแรก / ยังไม่มีรหัสผ่าน” กรอกอีเมล @ku.th ส่ง OTP ตรวจ Inbox/Spam รหัสใช้ได้ 5 นาที ลองผิดได้ไม่เกิน 5 ครั้ง ห้ามส่งรหัสให้คนอื่น
2. ยืนยัน OTP แล้วตั้งรหัสผ่าน 15-128 ตัวอักษร กรอกรหัสนิสิต/ผู้ใช้ ชื่อ นามสกุล และอ่านประกาศความเป็นส่วนตัวก่อนรับทราบ ครั้งต่อไปเข้าใช้ด้วยอีเมลและรหัสผ่าน ถ้าลืมใช้ “ลืมรหัสผ่าน”
3. เลือกแจ้งของหายหรือแจ้งพบ ระบุประเภท วันที่และสถานที่ พร้อมรายละเอียดที่ช่วยระบุสิ่งของ เช่น ยี่ห้อ รุ่น หรือตำหนิ แนบ JPG/PNG/WebP ตามขนาดที่ฟอร์มแจ้ง เลือกสีจริงของสิ่งของจากสีแนะนำหรือตารางสีเพื่อช่วยจับคู่ การ์ดโพสต์แสดงพื้นสีขาว แยกลักษณะเฉพาะไว้ช่องข้อมูลยืนยัน ห้ามใส่เลขบัตร/เบอร์โทร/หลักฐานเจ้าของในช่องสาธารณะหรือภาพ
เมื่อเจ้าหน้าที่ยืนยันการส่งมอบคืนแล้ว รายการของหายและของพบจะหายจากหน้ารายการโพสต์ แต่เจ้าของยังดูได้ในประวัติของตน และเจ้าหน้าที่ยังตรวจสอบประวัติการคืนได้
4. หน้ารายการกด “รายการของหาย” / “รายการของพบ” เพื่อเปลี่ยนหน้า กรองและค้นหาแล้วใช้ปุ่มก่อนหน้า/ถัดไป หากเห็น “รายละเอียดถูกปกปิด” เป็นพฤติกรรมป้องกันการแอบอ้าง ไม่ใช่ข้อมูลหาย
5. หน้าแจ้งเตือนแสดงคู่ที่อาจตรงกันและการแจ้งเตือนจากระบบ โดยเปิดรายการจากปุ่มข้างรีเฟรช คะแนนเป็นเพียงความคล้าย ไม่ใช่ยืนยันเจ้าของ หากเห็นของที่เป็นของตนในหน้ารายการของพบ สามารถกด Claim ได้แม้ยังไม่ได้ลงประกาศของหาย ระบุลักษณะเฉพาะและรอเจ้าหน้าที่ตรวจตัวตน หน้า “จุดรับฝากและการติดตาม” แสดงวันเวลาที่ยื่นคำขอ สถานะ “ยืนยันเจ้าของแล้ว · รอส่งมอบ” ยังไม่ใช่ “คืนแล้ว” ให้นำหลักฐานตัวตนไปรับที่จุดรับคืนตามเวลาทำการ เจ้าหน้าที่เปลี่ยนเป็น “คืนแล้ว” หลังส่งมอบจริง
6. หน้าโปรไฟล์มี รายการของฉัน การติดตาม ความเป็นส่วนตัว และออกจากระบบ เมนูเหล่านี้ไม่ซ้ำใน navbar รูปโปรไฟล์บันทึกไฟล์ใน backend/assets/profileUploads และเส้นทางใน users.profile_image ไม่เก็บภาพเป็นข้อความใน users
7. ชื่อ/นามสกุล อีเมล และรหัสผู้ใช้ไม่ให้แก้เอง ถ้าชื่อผิดยื่น “ขอแก้ไข” ในหน้า Privacy ให้แอดมินตรวจหลักฐานก่อนแก้ รูปโปรไฟล์แก้และลบผ่านปุ่มในโปรไฟล์ได้ กดบันทึกแล้วโหลดหน้าใหม่เพื่อตรวจผล
8. หน้า Privacy ดาวน์โหลดสำเนา JSON เฉพาะข้อมูลของตน หรือยื่นคำขอเข้าถึง/แก้ไข/ลบ/ถอน เจ้าหน้าที่ตอบกลับในรายการคำขอ การยื่นคำขอไม่ได้ลบข้อมูลทันที การถอนที่ปิดบัญชีอาจต้องสะสางงานรับคืนก่อน
9. ออกจากระบบที่โปรไฟล์ จะมี ยืนยัน / ยกเลิก เลือกยืนยันเพิกถอน session งานที่ยังไม่บันทึกอาจหาย

สำหรับแอดมิน: หน้า System Settings > Collection Points กด “เพิ่มจุดฝาก” แล้วเลือกหมุดหรือค้นหาสถานที่จากแผนที่เดียวกับหน้าแจ้งพบ ระบบจะเติมชื่อและพิกัดให้อัตโนมัติ ตรวจเวลาเปิดและข้อมูลติดต่อก่อนบันทึก หากจุดรับฝากไม่ได้อยู่ในหมุดที่เตรียมไว้ สามารถกรอกชื่อและพิกัดเองได้

เปลี่ยน ไทย / English ที่มุมบนขวา ภาษาเก็บไว้เฉพาะ browser นี้ กรอกฟอร์มแล้วสลับภาษาไม่ล้างค่า ชื่อบุคคลและข้อความที่เจ้าของกรอกไม่แปลอัตโนมัติ

## Troubleshooting

OTP ไม่เข้า: ตรวจ @ku.th และ Spam หลีกเลี่ยงกดซ้ำถี่ แจ้งผู้ดูแลผ่านช่องทางประกาศ; 503 หมายถึงบริการอีเมลยังไม่พร้อม ผู้ดูแลต้องตรวจ SMTP ห้ามใช้รหัสทดสอบข้าม OTP

รูปไม่โหลด: รอข้อความบันทึกสำเร็จแล้ว refresh ตรวจว่ารูปเป็นชนิดที่อนุญาต ผู้ดูแลตรวจ API/assets และ URL ของ backend อย่าแชร์ token หรือ .env ในภาพหน้าจอ

401/หมดอายุ: เข้าสู่ระบบใหม่ บัญชี inactive ให้ติดต่อผู้ดูแล ไม่แก้ sessionStorage เพื่อหลบข้อจำกัด

## English quick start

Choose English at the top-right. For first-time access, verify your @ku.th email using the emailed OTP (valid for 5 minutes), then create a 15-128 character password and complete your identity details. An email check is not university SSO or registrar identity verification.

Report a lost or found item with date/time, location, category, colour, optional brand/model and image. Put ownership evidence in the private field, never in public descriptions or photos. Use the Lost items / Found items buttons and filters to browse.

Review possible matches or use Claim on a found item even without a lost report. Submit private ownership details and visit the collection point for staff verification. A similarity score is not proof of ownership. “Owner verified — awaiting handover” does not mean the item has been returned; staff records “Returned” only after physical handover. Request and notification timestamps appear in Tracking. Profile contains My reports, Tracking, Privacy and Sign out; identity fields are read-only. Request corrections through Privacy.

Privacy lets you download your own JSON data or request access, correction, erasure or withdrawal. Requests require review; deletion is not immediate. Sign out requires confirmation. User-generated content and official place names remain in their original language.
