# Detailed Test Cases — 21 October 2026 (English original)

{
  "initial": {
    "total": 436,
    "PASS": 408,
    "FAIL": 18,
    "BLOCKED": 7,
    "NOT RUN": 3,
    "executed": 426,
    "passRate": 95.77
  },
  "afterDiagnosticReruns": {
    "total": 436,
    "PASS": 418,
    "FAIL": 8,
    "BLOCKED": 7,
    "NOT RUN": 3,
    "executed": 426,
    "passRate": 98.12
  },
  "note": "Initial failures retained. Reruns have fresh test state, not app fixes. Each row is one automated scenario; repeat runs and assertions are not extra cases."
}

## Summary table

| Test Case | Feature / Scenario | Expected Result | Actual Result | Status (initial) | Severity | Bug | Rerun |
|---|---|---|---|---|---|---|---|
| UNIT-001 | audit: coordinates accept zero/bounds and reject invalid or incomplete pairs | audit: coordinates accept zero/bounds and reject invalid or incomplete pairs | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-002 | audit: date ranges reject invalid dates and reverse ranges | audit: date ranges reject invalid dates and reverse ranges | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-003 | audit: legacy schema migration, coordinates and admin filters work on isolated DB | audit: legacy schema migration, coordinates and admin filters work on isolated DB | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-004 | audit: report cleanup deletes only failed request files, keeping saved reports and older files | audit: report cleanup deletes only failed request files, keeping saved reports and older files | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-005 | audit: map loads all pages, keeps unknown places, and respects hidden coordinates | audit: map loads all pages, keeps unknown places, and respects hidden coordinates | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-006 | read-only UI audit detects mismatches and leaked fields while comparing JSON dates correctly | read-only UI audit detects mismatches and leaked fields while comparing JSON dates correctly | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-007 | Express hides its version header | Express hides its version header | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-008 | uploaded images can be displayed by the web client on another origin | uploaded images can be displayed by the web client on another origin | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-009 | legacy AVIF images are served while non-image assets remain blocked | legacy AVIF images are served while non-image assets remain blocked | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-010 | CORS accepts server-to-server, allowlisted, and local development origins | CORS accepts server-to-server, allowlisted, and local development origins | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-011 | CORS rejects malformed and untrusted origins | CORS rejects malformed and untrusted origins | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-012 | mail transport requires credentials and enforces TLS | mail transport requires credentials and enforces TLS | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-013 | OTP generator returns a cryptographically generated six-digit value | OTP generator returns a cryptographically generated six-digit value | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-014 | bearer parser requires one opaque token | bearer parser requires one opaque token | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-015 | session middleware rejects missing credentials while optional auth stays public | session middleware rejects missing credentials while optional auth stays public | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-016 | email validation rejects malformed input | email validation rejects malformed input | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-017 | item validation normalizes valid data and reports invalid fields | item validation normalizes valid data and reports invalid fields | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-018 | AI response helpers parse plain and fenced JSON safely | AI response helpers parse plain and fenced JSON safely | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-019 | AI score normalization and disabled mode are deterministic | AI score normalization and disabled mode are deterministic | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-020 | backup refuses relative or missing executable paths before starting a dump | backup refuses relative or missing executable paths before starting a dump | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-021 | restore check rejects an unsafe target and an unrecognized backup | restore check rejects an unsafe target and an unrecognized backup | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-022 | suggested and custom physical colors both affect matching | suggested and custom physical colors both affect matching | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-023 | item colour validation accepts a palette hex and ignores old card colour input | item colour validation accepts a palette hex and ignores old card colour input | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-024 | lost and found posts persist physical colour without a card colour | lost and found posts persist physical colour without a card colour | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-025 | decorative card colours never affect matching text evidence | decorative card colours never affect matching text evidence | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-026 | legacy picker values move once with audit and rescan, while physical descriptions and existing card choices survive | legacy picker values move once with audit and rescan, while physical descriptions and existing card choices survive | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-027 | 30 labelled illustrations and complete reports use valid fields and balanced categories | 30 labelled illustrations and complete reports use valid fields and balanced categories | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-028 | seed keeps original accounts and reports, has all point links and no outgoing side effects | seed keeps original accounts and reports, has all point links and no outgoing side effects | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-029 | a collection point collision rolls back the whole seed rather than repurposing real data | a collection point collision rolls back the whole seed rather than repurposing real data | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-030 | local demo staff uses username, cannot become admin, expires and is blocked in production | local demo staff uses username, cannot become admin, expires and is blocked in production | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-031 | required fields reject empty/whitespace but never modify original input | required fields reject empty/whitespace but never modify original input | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-032 | required selects, files, checkboxes and field constraints have specific feedback | required selects, files, checkboxes and field constraints have specific feedback | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-033 | numeric conversion happens at submission, rejects blanks and preserves real zero | numeric conversion happens at submission, rejects blanks and preserves real zero | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-034 | Google authentication accepts only a verified exact KU domain and a valid server-verified token | Google authentication accepts only a verified exact KU domain and a valid server-verified token | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-035 | local vision uses normalized AI feature cosine rather than filename or text similarity | local vision uses normalized AI feature cosine rather than filename or text similarity | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-036 | missing, external, profile, query, encoded traversal and nonexistent paths never reach AI | missing, external, profile, query, encoded traversal and nonexistent paths never reach AI | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-037 | the cache hashes actual file bytes and invalidates overwrites, even with the same filename | the cache hashes actual file bytes and invalidates overwrites, even with the same filename | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-038 | blank, tiny, malformed, oversized and pixel-bomb images cannot produce a visual match | blank, tiny, malformed, oversized and pixel-bomb images cannot produce a visual match | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-039 | upload directory junctions and image symlinks cannot escape the item upload root | upload directory junctions and image symlinks cannot escape the item upload root | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-040 | an image-file symlink is rejected even when its target is another permitted item image | an image-file symlink is rejected even when its target is another permitted item image | Not executed: Windows host does not permit creating the requested file symlink | BLOCKED | Medium/P2 | — | — |
| UNIT-041 | concurrent repeated comparisons share inference for each actual image content | concurrent repeated comparisons share inference for each actual image content | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-042 | failed or malformed embeddings report unavailable instead of falling back to a match | failed or malformed embeddings report unavailable instead of falling back to a match | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-043 | embedding cache is bounded to 128 entries, retains content keys and evicts old images | embedding cache is bounded to 128 entries, retains content keys and evicts old images | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-044 | a single worker serializes inference, bounds its queue and terminates timed-out execution | a single worker serializes inference, bounds its queue and terminates timed-out execution | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-045 | test injection is unavailable outside the test environment | test injection is unavailable outside the test environment | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-046 | offline real DINOv2 inference separates a synthetic key from a backpack | offline real DINOv2 inference separates a synthetic key from a backpack | Not executed: optional real-model smoke is off and backend/.cache/matching-models is absent | BLOCKED | Medium/P2 | — | — |
| UNIT-047 | localized JSX translates UI branches without translating names, free text or API values | localized JSX translates UI branches without translating names, free text or API values | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-048 | English dictionary contains non-empty translations including backend validation errors | English dictionary contains non-empty translations including backend validation errors | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-049 | known notifications translate only the system envelope and preserve captured data | known notifications translate only the system envelope and preserve captured data | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-050 | approved cleanup preserves unrelated records, old account and credentials | approved cleanup preserves unrelated records, old account and credentials | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-051 | an import identity conflict rolls back deleted items and jobs | an import identity conflict rolls back deleted items and jobs | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-052 | an approved item gaining an owner prevents deletion and rolls back | an approved item gaining an owner prevents deletion and rolls back | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-053 | labelled datasets reject leakage, missing labels and repeated ids | labelled datasets reject leakage, missing labels and repeated ids | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-054 | evaluation reports false positives and cannot claim accuracy when no predictions exist | evaluation reports false positives and cannot claim accuracy when no predictions exist | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-055 | identical report text cannot override unrelated photographs | identical report text cannot override unrelated photographs | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-056 | automatic match notifications require a score of at least 95 | automatic match notifications require a score of at least 95 | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-057 | different selected item colors keep an otherwise similar pair below the alert threshold | different selected item colors keep an otherwise similar pair below the alert threshold | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-058 | missing, invalid or low-quality photographs never create an automatic match | missing, invalid or low-quality photographs never create an automatic match | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-059 | an unavailable vision model fails closed and leaves matching pending | an unavailable vision model fails closed and leaves matching pending | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-060 | the durable worker retries unavailable vision rather than completing the job | the durable worker retries unavailable vision rather than completing the job | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-061 | durable jobs preserve PostgreSQL timestamp precision when completing work | durable jobs preserve PostgreSQL timestamp precision when completing work | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-062 | a report requeued during inference remains pending after the old job finishes | a report requeued during inference remains pending after the old job finishes | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-063 | overlapping worker flushes never run duplicate inference for one report | overlapping worker flushes never run duplicate inference for one report | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-064 | a true pair after the first vision batch is eventually evaluated before completion | a true pair after the first vision batch is eventually evaluated before completion | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-065 | continuation preserves eligible results from the first vision batch | continuation preserves eligible results from the first vision batch | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-066 | unavailable tail inference retries that candidate without rescanning completed batches | unavailable tail inference retries that candidate without rescanning completed batches | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-067 | lowering the administrator threshold does not bypass the visual minimum | lowering the administrator threshold does not bypass the visual minimum | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-068 | a high visual score is not evidence when both images were not compared | a high visual score is not evidence when both images were not compared | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-069 | high visual similarity cannot override object contradictions | high visual similarity cannot override object contradictions | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-070 | a visually supported pair persists auditable scores without asserting 100% certainty | a visually supported pair persists auditable scores without asserting 100% certainty | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-071 | scanning one's own two reports does not call vision or create a match | scanning one's own two reports does not call vision or create a match | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-072 | matching requests require an owner session and queue expensive work | matching requests require an owner session and queue expensive work | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-073 | legacy text-only 100% matches stay hidden and cannot authorize claims | legacy text-only 100% matches stay hidden and cannot authorize claims | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-074 | staff-confirmed legacy pairs remain usable but never bypass physical claim verification | staff-confirmed legacy pairs remain usable but never bypass physical claim verification | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-075 | rechecking a previously supported pair invalidates conflicting visual evidence | rechecking a previously supported pair invalidates conflicting visual evidence | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-076 | a manually rejected pair cannot be reactivated by a high-scoring model | a manually rejected pair cannot be reactivated by a high-scoring model | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-077 | public matching JSON cannot expose arbitrary or raw internal AI metadata | public matching JSON cannot expose arbitrary or raw internal AI metadata | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-078 | SQL and JavaScript both reject malformed or out-of-range automatic visual evidence | SQL and JavaScript both reject malformed or out-of-range automatic visual evidence | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-079 | human-reviewed legacy output cannot expose model metadata or unrecognized provider/version strings | human-reviewed legacy output cannot expose model metadata or unrecognized provider/version strings | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-080 | retention alerts ignore inactive legacy pairs but preserve staff-confirmed owners and active claims | retention alerts ignore inactive legacy pairs but preserve staff-confirmed owners and active claims | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-081 | exhausted vision jobs are unavailable, not completed searches with no matches | exhausted vision jobs are unavailable, not completed searches with no matches | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-082 | matching job failures owned by another user do not mark the current search unavailable | matching job failures owned by another user do not mark the current search unavailable | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-083 | changed source and candidate inputs during vision cannot activate stale evidence | changed source and candidate inputs during vision cannot activate stale evidence | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-084 | expired inference leases cannot activate a pair or complete a newer worker's job | expired inference leases cannot activate a pair or complete a newer worker's job | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-085 | an already expired lease is rejected before any visual inference starts | an already expired lease is rejected before any visual inference starts | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-086 | monitor rejects a false-green health response, HTTP errors and TLS failures | monitor rejects a false-green health response, HTTP errors and TLS failures | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-087 | monthly availability never counts gaps or future time as proven uptime | monthly availability never counts gaps or future time as proven uptime | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-088 | verified roster normalizes email for comparison and keeps student identity | verified roster normalizes email for comparison and keeps student identity | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-089 | roster rejects duplicate IDs and malformed addresses before repair | roster rejects duplicate IDs and malformed addresses before repair | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-090 | dry run reports only corrupted matching accounts and never starts a write transaction | dry run reports only corrupted matching accounts and never starts a write transaction | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-091 | repair updates guarded name fields and rolls back if a user changed meanwhile | repair updates guarded name fields and rolls back if a user changed meanwhile | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-092 | first-use OTP grants password setup only; replay and non-KU email rejected | first-use OTP grants password setup only; replay and non-KU email rejected | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-093 | password creation is one-use, salted and cannot promote a new user to staff | password creation is one-use, salted and cannot promote a new user to staff | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-094 | staff can log in with their username while student IDs cannot be used as usernames | staff can log in with their username while student IDs cannot be used as usernames | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-095 | users can update their profile image without changing identity fields | users can update their profile image without changing identity fields | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-096 | User Management changes are reflected in the user's profile | User Management changes are reflected in the user's profile | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-097 | Staff has operational permissions; role demotion and Inactive affect open sessions | Staff has operational permissions; role demotion and Inactive affect open sessions | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-098 | AES-GCM rejects tampering and stores claim evidence as ciphertext | AES-GCM rejects tampering and stores claim evidence as ciphertext | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-099 | automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox | automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-100 | public filters include brand/model/time but never reveal identity evidence | public filters include brand/model/time but never reveal identity evidence | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-101 | report creation stores new form fields, encrypted private evidence and durable matching job atomically | report creation stores new form fields, encrypted private evidence and durable matching job atomically | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-102 | Google login is disabled by default and only links verified KU roster accounts | Google login is disabled by default and only links verified KU roster accounts | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-103 | found reports accept only active collection points and store the canonical point name | found reports accept only active collection points and store the canonical point name | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-104 | forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions | forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-105 | scheduler dispatches due daily backup, records success and does not rerun it immediately | scheduler dispatches due daily backup, records success and does not rerun it immediately | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-106 | new report profiles persist, are reused, refresh, and cascade on deletion | new report profiles persist, are reused, refresh, and cascade on deletion | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-107 | offline training uses approved claims and staff-rejected pairs, not rejected claims | offline training uses approved claims and staff-rejected pairs, not rejected claims | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-108 | weight training refuses datasets with too few confirmed positives or rejected negatives | weight training refuses datasets with too few confirmed positives or rejected negatives | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-109 | training and validation never share a lost or found report | training and validation never share a lost or found report | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-110 | shared candidate items cannot leak between splits | shared candidate items cannot leak between splits | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-111 | the same photo reused under another report id stays in one split | the same photo reused under another report id stays in one split | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-112 | PDF export is protected, validates scope and produces a real embedded-font PDF | PDF export is protected, validates scope and produces a real embedded-font PDF | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-113 | manual migration is idempotent and preserves existing reports | manual migration is idempotent and preserves existing reports | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-114 | all new admin resources reject unauthenticated and regular user sessions | all new admin resources reject unauthenticated and regular user sessions | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-115 | existing admin login remains functional | existing admin login remains functional | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-116 | point management validates coordinates and prevents duplicate names | point management validates coordinates and prevents duplicate names | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-117 | item handling records private attributes and point without permitting direct return | item handling records private attributes and point without permitting direct return | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-118 | public listing exposes the basic description but keeps identifying details private | public listing exposes the basic description but keeps identifying details private | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-119 | matching requires visual evidence and persists scores plus deduplicated notifications | matching requires visual evidence and persists scores plus deduplicated notifications | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-120 | admin match confirmation notifies both reporters with the confirmation time | admin match confirmation notifies both reporters with the confirmation time | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-121 | claim enforces own lost report, prevents duplicate submission and requires manual identity check | claim enforces own lost report, prevents duplicate submission and requires manual identity check | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-122 | release changes both reports atomically, retains audit, and prevents more claims | release changes both reports atomically, retains audit, and prevents more claims | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-123 | new ticket can be investigated; notes and status are audited | new ticket can be investigated; notes and status are audited | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-124 | user registry can be created and edited without deleting previous reports | user registry can be created and edited without deleting previous reports | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-125 | settings reject invalid policy and apply retention only to new reports | settings reject invalid policy and apply retention only to new reports | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-126 | notifications can only be marked read by their owner | notifications can only be marked read by their owner | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-127 | search filters, daily/monthly/yearly statistics and real Excel workbook are usable | search filters, daily/monthly/yearly statistics and real Excel workbook are usable | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-128 | privacy correction requires identity verification, updates users and prevents replay | privacy correction requires identity verification, updates users and prevents replay | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-129 | personal-data export contains only the owner data and never authentication secrets | personal-data export contains only the owner data and never authentication secrets | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-130 | erasure completion requires external evidence and does not automatically destroy records | erasure completion requires external evidence and does not automatically destroy records | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-131 | withdrawal closes an account reversibly and blocks its existing session | withdrawal closes an account reversibly and blocks its existing session | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-132 | direct found-item claim requires identity check and confirmed handover | direct found-item claim requires identity check and confirmed handover | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-133 | failed verification before handover rejects the old pair and queues both reports for new matches | failed verification before handover rejects the old pair and queues both reports for new matches | All assertions passed | PASS | Medium/P2 | — | — |
| UNIT-134 | a direct found-item claim can be declined before handover and the item is searchable again | a direct found-item claim can be declined before handover and the item is searchable again | All assertions passed | PASS | Medium/P2 | — | — |
| PG-001 | first-use OTP grants password setup only; replay and non-KU email rejected | first-use OTP grants password setup only; replay and non-KU email rejected | All assertions passed | PASS | Medium/P2 | — | — |
| PG-002 | password creation is one-use, salted and cannot promote a new user to staff | password creation is one-use, salted and cannot promote a new user to staff | All assertions passed | PASS | Medium/P2 | — | — |
| PG-003 | staff can log in with their username while student IDs cannot be used as usernames | staff can log in with their username while student IDs cannot be used as usernames | All assertions passed | PASS | Medium/P2 | — | — |
| PG-004 | users can update their profile image without changing identity fields | users can update their profile image without changing identity fields | All assertions passed | PASS | Medium/P2 | — | — |
| PG-005 | User Management changes are reflected in the user's profile | User Management changes are reflected in the user's profile | All assertions passed | PASS | Medium/P2 | — | — |
| PG-006 | Staff has operational permissions; role demotion and Inactive affect open sessions | Staff has operational permissions; role demotion and Inactive affect open sessions | All assertions passed | PASS | Medium/P2 | — | — |
| PG-007 | AES-GCM rejects tampering and stores claim evidence as ciphertext | AES-GCM rejects tampering and stores claim evidence as ciphertext | All assertions passed | PASS | Medium/P2 | — | — |
| PG-008 | automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox | automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox | All assertions passed | PASS | Medium/P2 | — | — |
| PG-009 | public filters include brand/model/time but never reveal identity evidence | public filters include brand/model/time but never reveal identity evidence | All assertions passed | PASS | Medium/P2 | — | — |
| PG-010 | report creation stores new form fields, encrypted private evidence and durable matching job atomically | report creation stores new form fields, encrypted private evidence and durable matching job atomically | All assertions passed | PASS | Medium/P2 | — | — |
| PG-011 | Google login is disabled by default and only links verified KU roster accounts | Google login is disabled by default and only links verified KU roster accounts | All assertions passed | PASS | Medium/P2 | — | — |
| PG-012 | found reports accept only active collection points and store the canonical point name | found reports accept only active collection points and store the canonical point name | All assertions passed | PASS | Medium/P2 | — | — |
| PG-013 | forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions | forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions | All assertions passed | PASS | Medium/P2 | — | — |
| PG-014 | scheduler dispatches due daily backup, records success and does not rerun it immediately | scheduler dispatches due daily backup, records success and does not rerun it immediately | All assertions passed | PASS | Medium/P2 | — | — |
| PG-015 | PDF export is protected, validates scope and produces a real embedded-font PDF | PDF export is protected, validates scope and produces a real embedded-font PDF | All assertions passed | PASS | Medium/P2 | — | — |
| PG-016 | manual migration is idempotent and preserves existing reports | manual migration is idempotent and preserves existing reports | All assertions passed | PASS | Medium/P2 | — | — |
| PG-017 | all new admin resources reject unauthenticated and regular user sessions | all new admin resources reject unauthenticated and regular user sessions | All assertions passed | PASS | Medium/P2 | — | — |
| PG-018 | existing admin login remains functional | existing admin login remains functional | All assertions passed | PASS | Medium/P2 | — | — |
| PG-019 | point management validates coordinates and prevents duplicate names | point management validates coordinates and prevents duplicate names | All assertions passed | PASS | Medium/P2 | — | — |
| PG-020 | item handling records private attributes and point without permitting direct return | item handling records private attributes and point without permitting direct return | All assertions passed | PASS | Medium/P2 | — | — |
| PG-021 | public listing exposes the basic description but keeps identifying details private | public listing exposes the basic description but keeps identifying details private | All assertions passed | PASS | Medium/P2 | — | — |
| PG-022 | matching requires visual evidence and persists scores plus deduplicated notifications | matching requires visual evidence and persists scores plus deduplicated notifications | All assertions passed | PASS | Medium/P2 | — | — |
| PG-023 | admin match confirmation notifies both reporters with the confirmation time | admin match confirmation notifies both reporters with the confirmation time | All assertions passed | PASS | Medium/P2 | — | — |
| PG-024 | claim enforces own lost report, prevents duplicate submission and requires manual identity check | claim enforces own lost report, prevents duplicate submission and requires manual identity check | All assertions passed | PASS | Medium/P2 | — | — |
| PG-025 | release changes both reports atomically, retains audit, and prevents more claims | release changes both reports atomically, retains audit, and prevents more claims | All assertions passed | PASS | Medium/P2 | — | — |
| PG-026 | new ticket can be investigated; notes and status are audited | new ticket can be investigated; notes and status are audited | All assertions passed | PASS | Medium/P2 | — | — |
| PG-027 | user registry can be created and edited without deleting previous reports | user registry can be created and edited without deleting previous reports | All assertions passed | PASS | Medium/P2 | — | — |
| PG-028 | settings reject invalid policy and apply retention only to new reports | settings reject invalid policy and apply retention only to new reports | All assertions passed | PASS | Medium/P2 | — | — |
| PG-029 | notifications can only be marked read by their owner | notifications can only be marked read by their owner | All assertions passed | PASS | Medium/P2 | — | — |
| PG-030 | search filters, daily/monthly/yearly statistics and real Excel workbook are usable | search filters, daily/monthly/yearly statistics and real Excel workbook are usable | All assertions passed | PASS | Medium/P2 | — | — |
| PG-031 | privacy correction requires identity verification, updates users and prevents replay | privacy correction requires identity verification, updates users and prevents replay | All assertions passed | PASS | Medium/P2 | — | — |
| PG-032 | personal-data export contains only the owner data and never authentication secrets | personal-data export contains only the owner data and never authentication secrets | All assertions passed | PASS | Medium/P2 | — | — |
| PG-033 | erasure completion requires external evidence and does not automatically destroy records | erasure completion requires external evidence and does not automatically destroy records | All assertions passed | PASS | Medium/P2 | — | — |
| PG-034 | withdrawal closes an account reversibly and blocks its existing session | withdrawal closes an account reversibly and blocks its existing session | All assertions passed | PASS | Medium/P2 | — | — |
| PG-035 | direct found-item claim requires identity check and confirmed handover | direct found-item claim requires identity check and confirmed handover | All assertions passed | PASS | Medium/P2 | — | — |
| PG-036 | failed verification before handover rejects the old pair and queues both reports for new matches | failed verification before handover rejects the old pair and queues both reports for new matches | not ok 36 - failed verification before handover rejects the old pair and queues both reports for new matches<br>  ---<br>  duration_ms: 333.3075<br>  type: 'test'<br>  location: 'C:\\IT_PROJECT_GitHub\\FOUNDLOST\\test\\workflow.test.cjs:933:1'<br>  failureType: 'testCodeFailure'<br>  error: \|-<br>    The expression evaluated to a falsy value:<br>    <br>      assert.ok(visible.body.matches.some(( | FAIL | Medium/P2 | QA-TEST-06 | — |
| PG-037 | a direct found-item claim can be declined before handover and the item is searchable again | a direct found-item claim can be declined before handover and the item is searchable again | All assertions passed | PASS | Medium/P2 | — | — |
| WEB-001 | primary screens pass automated WCAG AA checks on desktop and mobile | primary screens pass automated WCAG AA checks on desktop and mobile | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-002 | public administrator login is accessible without an existing session | public administrator login is accessible without an existing session | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-003 | skip link and signout confirmation work with keyboard and accessible dialog | skip link and signout confirmation work with keyboard and accessible dialog | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-004 | admin login and all console navigation work with real API data | admin login and all console navigation work with real API data | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-005 | staff portal contains the six operational pages | staff portal contains the six operational pages | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-006 | console pages fit desktop and mobile and capture real-data screenshots | console pages fit desktop and mobile and capture real-data screenshots | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-007 | collection point editor saves, traps dialog focus and closes with Escape | collection point editor saves, traps dialog focus and closes with Escape | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-008 | statistics downloads a real Excel workbook and has printable report layout | statistics downloads a real Excel workbook and has printable report layout | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-009 | user submits hidden-attribute claim and staff approves then releases the item | user submits hidden-attribute claim and staff approves then releases the item | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-010 | failed search removes old cards and retry returns new results | failed search removes old cards and retry returns new results | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-011 | map follows pagination without inventing hidden/custom-location markers | map follows pagination without inventing hidden/custom-location markers | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-012 | signin keeps recovery below password and removes the first-use shortcut | signin keeps recovery below password and removes the first-use shortcut | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-013 | signup and OTP follow the desktop and mobile layouts | signup and OTP follow the desktop and mobile layouts | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-014 | first-use email OTP, password creation, logout and password login work end to end | first-use email OTP, password creation, logout and password login work end to end | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-015 | login, privacy and public listing filters fit a narrow screen | login, privacy and public listing filters fit a narrow screen | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-016 | login and filter action pairs have equal sizes on desktop and mobile | login and filter action pairs have equal sizes on desktop and mobile | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-017 | lost form offers item colours and no card colour | lost form offers item colours and no card colour | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-018 | found form offers item colours and no card colour | found form offers item colours and no card colour | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-019 | designed user screens work without horizontal overflow on mobile and desktop | designed user screens work without horizontal overflow on mobile and desktop | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-020 | public screens fit desktop and mobile | public screens fit desktop and mobile | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-021 | catalogue cards open a usable detail page | catalogue cards open a usable detail page | Error: [2mexpect([22m[31mlocator[39m[2m).[22mtoBeVisible[2m([22m[2m)[22m failed<br><br>Locator: locator('.fl-item-card').first()<br>Expected: visible<br>Timeout: 5000ms<br>Error: element(s) not found<br><br>Call log:<br>[2m  - Expect "toBeVisible" locator('.fl-item-card').first() with timeout 5000ms[22m<br>[2m  - waiting for locator('.fl-item-card').first()[22m<br><br><br>  45 \|   a | FAIL | Medium/P2 | QA-TEST-01 | PASS |
| WEB-022 | profile and item details display API values on desktop and mobile | profile and item details display API values on desktop and mobile | TypeError: Cannot read properties of undefined (reading 'item_id')<br><br>  63 \|       const { items } = await response.json();<br>  64 \|       const item = items[0];<br>> 65 \|       await page.goto(`/items/${kind}/${item.item_id}`);<br>     \|                                              ^<br>  66 \|       await expect(page.locator(".item-detail-sheet h1")).toHaveText(item.item_name);<br>  67  | FAIL | Medium/P2 | QA-TEST-01 | PASS |
| WEB-023 | found report offers only configured collection points | found report offers only configured collection points | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-024 | Prompt loads and applies across public, auth, admin, and app screens | Prompt loads and applies across public, auth, admin, and app screens | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-025 | login has inline localized feedback, focuses invalid fields and keeps password bytes | login has inline localized feedback, focuses invalid fields and keeps password bytes | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-026 | blank numbers stay blank and genuine zero is submitted as a number | blank numbers stay blank and genuine zero is submitted as a number | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-027 | whitespace-only request blocked before API at /services | whitespace-only request blocked before API at /services | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-028 | whitespace-only request blocked before API at /privacy | whitespace-only request blocked before API at /privacy | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-029 | OTP explains disabled button and updates the digit count in both languages | OTP explains disabled button and updates the digit count in both languages | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-030 | a dropped image satisfies upload validation and reset removes old errors | a dropped image satisfies upload validation and reset removes old errors | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-031 | staff direct claim review explains missing note and identity confirmation | staff direct claim review explains missing note and identity confirmation | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-032 | staff can decline an approved claim before handover with a reason | staff can decline an approved claim before handover with a reason | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-033 | language switch keeps the local welcome layout and keyboard skip link | language switch keeps the local welcome layout and keyboard skip link | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-034 | report form submits only the selected physical colour | report form submits only the selected physical colour | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-035 | ineligible visual evidence prevents submitting a claim | ineligible visual evidence prevents submitting a claim | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-036 | KU Google button logs an existing roster account in without changing its role | KU Google button logs an existing roster account in without changing its role | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-037 | rail labels are visible on expansion and cards ignore image aspect ratio | rail labels are visible on expansion and cards ignore image aspect ratio | Error: [2mexpect([22m[31mreceived[39m[2m).[22mtoBeCloseTo[2m([22m[32mexpected[39m[2m, [22mprecision[2m)[22m<br><br>Expected: [32m140[39m<br>Received: [31m147.99996948242188[39m<br><br>Expected precision:    1<br>Expected difference: < [32m0.05[39m<br>Received difference:   [31m7.999969482421875[39m<br><br>  30 \|     // Translated hover rectangles can differ by floating-point | FAIL | Medium/P2 | QA-TEST-02 | — |
| WEB-038 | detail recovery explains unmatched reports and handles matching service errors | detail recovery explains unmatched reports and handles matching service errors | Error: [2mexpect([22m[31mlocator[39m[2m).[22mtoBeVisible[2m([22m[2m)[22m failed<br><br>Locator: getByRole('link', { name: 'ลงประกาศของหาย', exact: true })<br>Expected: visible<br>Timeout: 5000ms<br>Error: element(s) not found<br><br>Call log:<br>[2m  - Expect "toBeVisible" getByRole('link', { name: 'ลงประกาศของหาย', exact: true }) with timeout 5000ms[22m<br>[2m  - waiting for getByRol | FAIL | Medium/P2 | QA-TEST-03 | — |
| WEB-039 | item-by-ID endpoint authenticates, hides evidence and returns useful errors | item-by-ID endpoint authenticates, hides evidence and returns useful errors | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-040 | language controls live only in settings and persist at 320px | language controls live only in settings and persist at 320px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-041 | language controls live only in settings and persist at 1440px | language controls live only in settings and persist at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-042 | public pages do not show floating language controls | public pages do not show floating language controls | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-043 | English search, status and personal data stay separate at 390px | English search, status and personal data stay separate at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-044 | English search, status and personal data stay separate at 1440px | English search, status and personal data stay separate at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-045 | English validation and API errors update when switching languages | English validation and API errors update when switching languages | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-046 | Google button locale follows the UI and Google/OTP errors are translated | Google button locale follows the UI and Google/OTP errors are translated | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-047 | English system notifications preserve names and unknown free text | English system notifications preserve names and unknown free text | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-048 | English post saves original Thai data and language switching does not change API records | English post saves original Thai data and language switching does not change API records | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-049 | English switch translates authentication, persists locale and preserves draft values | English switch translates authentication, persists locale and preserves draft values | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-050 | English profile, listing and administration retain names and API values | English profile, listing and administration retain names and API values | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-051 | English authentication, privacy and report forms fit mobile without runtime errors | English authentication, privacy and report forms fit mobile without runtime errors | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-052 | map marker selection replaces desktop details for found, lost and deposit points | map marker selection replaces desktop details for found, lost and deposit points | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-053 | sidebar selection highlights its marker and Escape restores focus without modal trapping | sidebar selection highlights its marker and Escape restores focus without modal trapping | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-054 | mobile selection uses the same details card, does not cover the dock, and closes on Escape | mobile selection uses the same details card, does not cover the dock, and closes on Escape | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-055 | keyboard markers support Space, reduced motion and locale changes without translating item data | keyboard markers support Space, reduced motion and locale changes without translating item data | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-056 | selecting a marker outside the first five brings its matching sidebar row into view and filtering clears selection | selecting a marker outside the first five brings its matching sidebar row into view and filtering clears selection | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-057 | selected details and keyboard-accessible markers pass automated AA checks | selected details and keyboard-accessible markers pass automated AA checks | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-058 | matching console separates text and image zero scores and queues safe rescanning | matching console separates text and image zero scores and queues safe rescanning | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-059 | legacy scores are not presented as image-checked 100 percent matches | legacy scores are not presented as image-checked 100 percent matches | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-060 | user matching refreshes pending jobs and displays localized evidence without private AI reasons | user matching refreshes pending jobs and displays localized evidence without private AI reasons | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-061 | staff-confirmed pairs allow a claim without presenting failed visual evidence as ownership proof | staff-confirmed pairs allow a claim without presenting failed visual evidence as ownership proof | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-062 | failed visual analysis is distinct from a completed search with no matches | failed visual analysis is distinct from a completed search with no matches | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-063 | desktop rail overlays without moving layout on hover and keyboard focus at 701px | desktop rail overlays without moving layout on hover and keyboard focus at 701px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-064 | desktop rail overlays without moving layout on hover and keyboard focus at 1024px | desktop rail overlays without moving layout on hover and keyboard focus at 1024px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-065 | desktop rail overlays without moving layout on hover and keyboard focus at 1440px | desktop rail overlays without moving layout on hover and keyboard focus at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-066 | desktop rail overlays without moving layout on hover and keyboard focus at 1920px | desktop rail overlays without moving layout on hover and keyboard focus at 1920px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-067 | quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 390px | quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-068 | quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 1440px | quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-069 | quick filter scrollbar has clearance and desktop rail icons remain aligned on hover | quick filter scrollbar has clearance and desktop rail icons remain aligned on hover | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-070 | development form opens without repeated full reloads | development form opens without repeated full reloads | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-071 | lost Figma form stays usable at 320px | lost Figma form stays usable at 320px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-072 | found Figma form stays usable at 320px | found Figma form stays usable at 320px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-073 | lost Figma form stays usable at 375px | lost Figma form stays usable at 375px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-074 | found Figma form stays usable at 375px | found Figma form stays usable at 375px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-075 | lost Figma form stays usable at 390px | lost Figma form stays usable at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-076 | found Figma form stays usable at 390px | found Figma form stays usable at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-077 | lost Figma form stays usable at 700px | lost Figma form stays usable at 700px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-078 | found Figma form stays usable at 700px | found Figma form stays usable at 700px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-079 | lost Figma form stays usable at 701px | lost Figma form stays usable at 701px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-080 | found Figma form stays usable at 701px | found Figma form stays usable at 701px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-081 | lost Figma form stays usable at 1024px | lost Figma form stays usable at 1024px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-082 | found Figma form stays usable at 1024px | found Figma form stays usable at 1024px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-083 | lost Figma form stays usable at 1440px | lost Figma form stays usable at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-084 | found Figma form stays usable at 1440px | found Figma form stays usable at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-085 | English forms and errors remain accessible at 375px | English forms and errors remain accessible at 375px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-086 | English forms and errors remain accessible at 1440px | English forms and errors remain accessible at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-087 | mobile map traps focus, closes with Escape, and resizing preserves the draft | mobile map traps focus, closes with Escape, and resizing preserves the draft | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-088 | search has one advanced menu and synchronized quick filters at 390px | search has one advanced menu and synchronized quick filters at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-089 | lost posting matches layout and confirms successful API save at 390px | lost posting matches layout and confirms successful API save at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-090 | found posting matches layout and confirms successful API save at 390px | found posting matches layout and confirms successful API save at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-091 | search has one advanced menu and synchronized quick filters at 1440px | search has one advanced menu and synchronized quick filters at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-092 | lost posting matches layout and confirms successful API save at 1440px | lost posting matches layout and confirms successful API save at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-093 | found posting matches layout and confirms successful API save at 1440px | found posting matches layout and confirms successful API save at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-094 | failed post keeps form input, displays error and never claims success | failed post keeps form input, displays error and never claims success | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-095 | missing fields and unsupported images show feedback without submitting | missing fields and unsupported images show feedback without submitting | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-096 | report choices match responsive geometry and navigate at 320px | report choices match responsive geometry and navigate at 320px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-097 | report choices match responsive geometry and navigate at 390px | report choices match responsive geometry and navigate at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-098 | report choices match responsive geometry and navigate at 700px | report choices match responsive geometry and navigate at 700px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-099 | report choices match responsive geometry and navigate at 701px | report choices match responsive geometry and navigate at 701px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-100 | report choices match responsive geometry and navigate at 1024px | report choices match responsive geometry and navigate at 1024px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-101 | report choices match responsive geometry and navigate at 1440px | report choices match responsive geometry and navigate at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-102 | keyboard, backdrop, repeated opening, scroll lock and short screens work | keyboard, backdrop, repeated opening, scroll lock and short screens work | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-103 | English and high contrast variants remain usable with reduced motion | English and high contrast variants remain usable with reduced motion | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-104 | record the original Figma palette contrast limitation without hiding violations | record the original Figma palette contrast limitation without hiding violations | Error: [2mexpect([22m[31mreceived[39m[2m).[22mtoBeCloseTo[2m([22m[32mexpected[39m[2m, [22mprecision[2m)[22m<br><br>Expected: [32m2.62[39m<br>Received: [31m6.232268509031551[39m<br><br>Expected precision:    1<br>Expected difference: < [32m0.05[39m<br>Received difference:   [31m3.6122685090315505[39m<br><br>  250 \|       });<br>  251 \|     });<br>> 252 \|   expect(palette[0] | FAIL | Medium/P2 | QA-TEST-04 | — |
| WEB-105 | system notifications appear in the notification list and can be marked read | system notifications appear in the notification list and can be marked read | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-106 | public layouts fit narrow mobile and tablet | public layouts fit narrow mobile and tablet | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-107 | pressed state is visible without layout shift and disabled actions remain disabled | pressed state is visible without layout shift and disabled actions remain disabled | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-108 | confirmation fits short screens, traps focus and restores the trigger | confirmation fits short screens, traps focus and restores the trigger | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-109 | admin modal stays inside a short screen and closes without saving | admin modal stays inside a short screen and closes without saving | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-110 | admin table text and map controls retain usable proportions | admin table text and map controls retain usable proportions | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-111 | all application layouts at 320px | all application layouts at 320px | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-112 | all application layouts at 390px | all application layouts at 390px | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-113 | all application layouts at 768px | all application layouts at 768px | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-114 | all application layouts at 1440px | all application layouts at 1440px | SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON<br><br>  59 \|     await request.get("http://127.0.0.1:4181/__fixture/session")<br>  60 \|   ).json();<br>> 61 \|   const admin = await (<br>     \|                 ^<br>  62 \|     await request.post("http://127.0.0.1:4181/api/admin/login", {<br>  63 \|       data: { username: "e2e-admin", password: "test-password-only" },<br>   | FAIL | Medium/P2 | QA-TEST-05 | PASS |
| WEB-115 | search controls, cards and dock stay balanced at 320px | search controls, cards and dock stay balanced at 320px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-116 | settings language and photo controls have consistent sizes at 320px | settings language and photo controls have consistent sizes at 320px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-117 | search controls, cards and dock stay balanced at 390px | search controls, cards and dock stay balanced at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-118 | settings language and photo controls have consistent sizes at 390px | settings language and photo controls have consistent sizes at 390px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-119 | search controls, cards and dock stay balanced at 768px | search controls, cards and dock stay balanced at 768px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-120 | settings language and photo controls have consistent sizes at 768px | settings language and photo controls have consistent sizes at 768px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-121 | search controls, cards and dock stay balanced at 1440px | search controls, cards and dock stay balanced at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| WEB-122 | settings language and photo controls have consistent sizes at 1440px | settings language and photo controls have consistent sizes at 1440px | All browser assertions passed | PASS | Medium/P2 | — | — |
| ROLE-001 | guest GET /api/admin/manage/operations | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-002 | student GET /api/admin/manage/operations | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-003 | guest GET /api/admin/manage/staff-notifications | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-004 | student GET /api/admin/manage/staff-notifications | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-005 | guest GET /api/admin/manage/privacy-requests | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-006 | student GET /api/admin/manage/privacy-requests | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-007 | guest PATCH /api/admin/manage/privacy-requests/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-008 | student PATCH /api/admin/manage/privacy-requests/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-009 | guest GET /api/admin/manage/settings | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-010 | student GET /api/admin/manage/settings | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-011 | guest PUT /api/admin/manage/settings | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-012 | student PUT /api/admin/manage/settings | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-013 | guest POST /api/admin/manage/retention/run | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-014 | student POST /api/admin/manage/retention/run | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-015 | guest GET /api/admin/manage/points | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-016 | student GET /api/admin/manage/points | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-017 | guest POST /api/admin/manage/points | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-018 | student POST /api/admin/manage/points | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-019 | guest PUT /api/admin/manage/points/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-020 | student PUT /api/admin/manage/points/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-021 | guest GET /api/admin/manage/users | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-022 | student GET /api/admin/manage/users | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-023 | guest POST /api/admin/manage/users | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-024 | student POST /api/admin/manage/users | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-025 | guest PUT /api/admin/manage/users/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-026 | student PUT /api/admin/manage/users/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-027 | guest GET /api/admin/manage/items/found | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-028 | student GET /api/admin/manage/items/found | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-029 | guest PATCH /api/admin/manage/items/found/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-030 | student PATCH /api/admin/manage/items/found/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-031 | guest GET /api/admin/manage/audit | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-032 | student GET /api/admin/manage/audit | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-033 | guest GET /api/admin/manage/matches | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-034 | student GET /api/admin/manage/matches | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-035 | guest PATCH /api/admin/manage/matches/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-036 | student PATCH /api/admin/manage/matches/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-037 | guest POST /api/admin/manage/matches/rescan | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-038 | student POST /api/admin/manage/matches/rescan | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-039 | guest GET /api/admin/manage/claims | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-040 | student GET /api/admin/manage/claims | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-041 | guest GET /api/admin/manage/claims/history | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-042 | student GET /api/admin/manage/claims/history | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-043 | guest PATCH /api/admin/manage/claims/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-044 | student PATCH /api/admin/manage/claims/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-045 | guest GET /api/admin/manage/tickets | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-046 | student GET /api/admin/manage/tickets | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-047 | guest POST /api/admin/manage/tickets | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-048 | student POST /api/admin/manage/tickets | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-049 | guest PATCH /api/admin/manage/tickets/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-050 | student PATCH /api/admin/manage/tickets/999999 | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-051 | guest GET /api/admin/manage/errors | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-052 | student GET /api/admin/manage/errors | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-053 | guest GET /api/admin/manage/statistics | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-054 | student GET /api/admin/manage/statistics | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-055 | guest GET /api/admin/manage/export | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-056 | student GET /api/admin/manage/export | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-057 | guest GET /api/admin/manage/export/pdf | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-058 | student GET /api/admin/manage/export/pdf | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-059 | staff GET /api/admin/manage/points | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-060 | super-admin GET /api/admin/manage/points | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-061 | staff GET /api/admin/manage/items/lost | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-062 | super-admin GET /api/admin/manage/items/lost | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-063 | staff GET /api/admin/manage/items/found | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-064 | super-admin GET /api/admin/manage/items/found | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-065 | staff GET /api/admin/manage/matches | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-066 | super-admin GET /api/admin/manage/matches | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-067 | staff GET /api/admin/manage/claims | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-068 | super-admin GET /api/admin/manage/claims | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-069 | staff GET /api/admin/manage/claims/history | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-070 | super-admin GET /api/admin/manage/claims/history | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-071 | staff GET /api/admin/manage/tickets | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-072 | super-admin GET /api/admin/manage/tickets | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-073 | staff GET /api/admin/manage/statistics | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-074 | super-admin GET /api/admin/manage/statistics | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-075 | staff GET /api/admin/manage/staff-notifications | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-076 | super-admin GET /api/admin/manage/staff-notifications | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-077 | staff GET /api/admin/manage/users | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-078 | super-admin GET /api/admin/manage/users | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-079 | staff GET /api/admin/manage/operations | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-080 | super-admin GET /api/admin/manage/operations | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-081 | staff GET /api/admin/manage/privacy-requests | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-082 | super-admin GET /api/admin/manage/privacy-requests | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-083 | staff POST /api/admin/manage/users | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-084 | staff PUT /api/admin/manage/users/999999 | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-085 | staff POST /api/admin/manage/points | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-086 | staff PUT /api/admin/manage/points/999999 | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-087 | staff PUT /api/admin/manage/settings | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-088 | staff GET /api/admin/users | 403 | 403 | PASS | High/P1 | — | — |
| ROLE-089 | guest GET /api/me/points | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-090 | student GET /api/me/points | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-091 | guest GET /api/me/claims | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-092 | student GET /api/me/claims | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-093 | guest GET /api/me/notifications | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-094 | student GET /api/me/notifications | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-095 | guest GET /api/me/privacy/requests | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-096 | student GET /api/me/privacy/requests | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-097 | student POST /api/me/claims | 201 | 201 | PASS | High/P1 | — | — |
| ROLE-098 | staff PATCH /api/admin/manage/claims/1 | 400 | 400 | PASS | High/P1 | — | — |
| ROLE-099 | staff PATCH /api/admin/manage/claims/1 | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-100 | staff PATCH /api/admin/manage/claims/1 | 400 | 400 | PASS | High/P1 | — | — |
| ROLE-101 | staff PATCH /api/admin/manage/claims/1 | 200 | 200 | PASS | High/P1 | — | — |
| ROLE-102 | staff DB assertion handover persisted states | returned/returned | returned/returned | PASS | High/P1 | — | — |
| ROLE-103 | staff PATCH /api/admin/manage/claims/1 | 409 | 409 | PASS | High/P1 | — | — |
| ROLE-104 | inactive-staff GET /api/admin/manage/claims | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-105 | inactive-student GET /api/me/profile | 401 | 401 | PASS | High/P1 | — | — |
| ROLE-106 | invalid-token GET /api/admin/profile | 401 | 401 | PASS | High/P1 | — | — |
| OP-01 | Database connection and core tables | All core tables readable | {"counts":{"users":61,"lost":7,"found":8,"points":132},"version":"16.10 (Debian 16.10-1.pgdg13+1)"} | PASS | Medium/P2 | — | — |
| OP-02 | Required fields and duplicate identity | 0 blank identity fields and 0 duplicate emails/IDs | {"blanks":0,"duplicate_email":0,"duplicate_id":0} | PASS | Medium/P2 | — | — |
| OP-03 | Lost/found and match relationships | 0 orphaned reports or matching pairs | {"code":"ERR_ASSERTION","message":"The expression evaluated to a falsy value:\n\n  assert.ok(Object.values(row).every(n=>n===0))\n"} | FAIL | High/P1 | QA-DATA-01 | — |
| OP-04 | Role availability | Active staff and admin available; report only aggregate counts | {"roles":[{"role":"staff","is_active":true,"n":1},{"role":"student","is_active":true,"n":60}],"admin":1} | PASS | Medium/P2 | — | — |
| OP-05 | Database FK/unique/primary constraints | Constraints present | [{"contype":"c","n":17},{"contype":"f","n":16},{"contype":"p","n":22},{"contype":"u","n":10}] | PASS | Medium/P2 | — | — |
| OP-06 | Original uploaded image files | Every referenced local image exists | {"code":"ERR_ASSERTION","message":"Referenced images missing: 2\n\n2 !== 0\n"} | FAIL | Medium/P2 | QA-DATA-02 | — |
| OP-07 | Encryption key availability | Key loads with correct size; no bytes disclosed | {"keyValid":true} | PASS | Medium/P2 | — | — |
| OP-08 | GET /health | HTTP 200 | {"http":200} | PASS | Medium/P2 | — | — |
| OP-09 | GET /api/me/profile | HTTP 401 | {"http":401} | PASS | Medium/P2 | — | — |
| OP-10 | GET /api/admin/profile | HTTP 401 | {"http":401} | PASS | Medium/P2 | — | — |
| OP-11 | GET /api/admin/manage/users | HTTP 401 | {"http":401} | PASS | Medium/P2 | — | — |
| OP-12 | GET /matching/all | HTTP 401 | {"http":401} | PASS | Medium/P2 | — | — |
| OP-13 | GET /assets/blocked.html | HTTP 404 | {"http":404} | PASS | Medium/P2 | — | — |
| OP-14 | GET /api/privacy-policy | HTTP 200 | {"http":200} | PASS | Medium/P2 | — | — |
| OP-15 | Google public configuration | Configured exact KU domain; no ID exported | {"http":200,"enabled":true,"hostedDomain":"ku.th"} | PASS | Medium/P2 | — | — |
| OP-16 | Security response headers | No framework version; nosniff, CSP and cache protections | {"frameworkHidden":true,"nosniff":true,"csp":true,"noStore":true} | PASS | Medium/P2 | — | — |
| OP-17 | Bounded health performance | 20 successful responses within a generous 2s local basic-check bound | {"scope":"20 sequential local SELECT-backed health requests only, not load/AI/production SLA","requests":20,"p50_ms":6,"p95_ms":8} | PASS | Medium/P2 | — | — |
| OP-18 | Source data counts preserved | Before/after counts identical | {"unchanged":true} | PASS | Medium/P2 | — | — |
| OP-19 | Disallowed CORS origin error classification | Untrusted origin rejected with a controlled 4xx, not server failure | {"code":"ERR_ASSERTION","message":"The expression evaluated to a falsy value:\n\n  assert.ok(r.status>=400&&r.status<500)\n"} | FAIL | Medium/P2 | QA-API-01 | — |
| OP-20 | Malformed JSON error handling | HTTP 400 and service remains healthy | {"malformed":400,"health":200} | PASS | Medium/P2 | — | — |
| OP-21 | Oversized JSON request rejected | HTTP 413 before authentication/database changes | {"http":413} | PASS | Medium/P2 | — | — |
| PG-OP-01 | Full startup, schema checks and /health succeed | Full startup, schema checks and /health succeed | [object Object] | PASS | High/P1 | — | — |
| PG-OP-02 | Super Admin authenticates and invalid credentials fail | Super Admin authenticates and invalid credentials fail | [object Object] | PASS | High/P1 | — | — |
| PG-OP-03 | CRUD persists across separate database connections | CRUD persists across separate database connections | [object Object] | PASS | High/P1 | — | — |
| QA-01 | Source lint | Command succeeds | exit 0 | PASS | Medium/P2 | — | — |
| QA-02 | Production build | Command succeeds | exit 0; existing main bundle >500kB warning remains | PASS | Medium/P2 | — | — |
| QA-03 | UI dictionary completeness | Command succeeds | {<br>  "total": 650,<br>  "missing": []<br>} | PASS | Medium/P2 | — | — |
| QA-04 | Frontend dependency audit | No reported dependency vulnerabilities | {"info":0,"low":0,"moderate":0,"high":2,"critical":0,"total":2} | FAIL | High/P1 | QA-SEC-01 | — |
| QA-05 | Backend dependency audit | No reported dependency vulnerabilities | {"info":0,"low":0,"moderate":0,"high":0,"critical":0,"total":0} | PASS | Medium/P2 | — | — |
| EXT-01 | Real KU Google account login | Real KU Google account login | No authorised human Google session/account supplied; verifier/browser tests are explicit doubles | BLOCKED | Medium/P2 | — | — |
| EXT-02 | SMTP/push delivery to a real recipient | SMTP/push delivery to a real recipient | No approved real recipient/provider confirmation; no messages sent | BLOCKED | Medium/P2 | — | — |
| EXT-03 | Production TLS and release readiness | Production TLS and release readiness | Production deployment/certificate not selected; privacy approval flag is not set in inspected local environment | BLOCKED | Medium/P2 | — | — |
| EXT-04 | AI precision/recall on labelled KU dataset | AI precision/recall on labelled KU dataset | No labelled held-out dataset/model cache for real inference in this checkout; synthetic logic is not accuracy proof | BLOCKED | Medium/P2 | — | — |
| EXT-05 | 500-user end-to-end load and soak on deployment | 500-user end-to-end load and soak on deployment | Only 20 bounded local health/SELECT requests measured; no production load permission/environment agreed | NOT RUN | Medium/P2 | — | — |
| EXT-06 | 99% availability over a Bangkok calendar month | 99% availability over a Bangkok calendar month | Requires a full external monitoring period; cannot infer uptime from a point-in-time check | NOT RUN | Medium/P2 | — | — |
| EXT-07 | Manual screen-reader and zoom certification of every state | Manual screen-reader and zoom certification of every state | Automated AA/keyboard checks run; dedicated assistive-technology audit not performed | NOT RUN | Medium/P2 | — | — |
| EXT-08 | Pixel-perfect Figma comparison for every screen/state | Pixel-perfect Figma comparison for every screen/state | No newly verified Figma design context/reference mapping in this QA run; screenshots/responsive checks do not establish exact equivalence | BLOCKED | Medium/P2 | — | — |

## Preconditions, steps, test data and evidence per case

### UNIT-001 — audit: coordinates accept zero/bounds and reject invalid or incomplete pairs

- Module: test/audit-regression.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: audit: coordinates accept zero/bounds and reject invalid or incomplete pairs
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/audit-regression.test.cjs:12
- Evidence: [unit.log](unit.log)

### UNIT-002 — audit: date ranges reject invalid dates and reverse ranges

- Module: test/audit-regression.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: audit: date ranges reject invalid dates and reverse ranges
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/audit-regression.test.cjs:33
- Evidence: [unit.log](unit.log)

### UNIT-003 — audit: legacy schema migration, coordinates and admin filters work on isolated DB

- Module: test/audit-regression.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: audit: legacy schema migration, coordinates and admin filters work on isolated DB
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/audit-regression.test.cjs:47
- Evidence: [unit.log](unit.log)

### UNIT-004 — audit: report cleanup deletes only failed request files, keeping saved reports and older files

- Module: test/audit-regression.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: audit: report cleanup deletes only failed request files, keeping saved reports and older files
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/audit-regression.test.cjs:103
- Evidence: [unit.log](unit.log)

### UNIT-005 — audit: map loads all pages, keeps unknown places, and respects hidden coordinates

- Module: test/audit-regression.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: audit: map loads all pages, keeps unknown places, and respects hidden coordinates
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/audit-regression.test.cjs:146
- Evidence: [unit.log](unit.log)

### UNIT-006 — read-only UI audit detects mismatches and leaked fields while comparing JSON dates correctly

- Module: test/audit-ui-data.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: read-only UI audit detects mismatches and leaked fields while comparing JSON dates correctly
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/audit-ui-data.test.cjs:7
- Evidence: [unit.log](unit.log)

### UNIT-007 — Express hides its version header

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Express hides its version header
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:29
- Evidence: [unit.log](unit.log)

### UNIT-008 — uploaded images can be displayed by the web client on another origin

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: uploaded images can be displayed by the web client on another origin
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:33
- Evidence: [unit.log](unit.log)

### UNIT-009 — legacy AVIF images are served while non-image assets remain blocked

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: legacy AVIF images are served while non-image assets remain blocked
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:48
- Evidence: [unit.log](unit.log)

### UNIT-010 — CORS accepts server-to-server, allowlisted, and local development origins

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: CORS accepts server-to-server, allowlisted, and local development origins
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:76
- Evidence: [unit.log](unit.log)

### UNIT-011 — CORS rejects malformed and untrusted origins

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: CORS rejects malformed and untrusted origins
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:83
- Evidence: [unit.log](unit.log)

### UNIT-012 — mail transport requires credentials and enforces TLS

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: mail transport requires credentials and enforces TLS
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:92
- Evidence: [unit.log](unit.log)

### UNIT-013 — OTP generator returns a cryptographically generated six-digit value

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: OTP generator returns a cryptographically generated six-digit value
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:110
- Evidence: [unit.log](unit.log)

### UNIT-014 — bearer parser requires one opaque token

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: bearer parser requires one opaque token
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:116
- Evidence: [unit.log](unit.log)

### UNIT-015 — session middleware rejects missing credentials while optional auth stays public

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: session middleware rejects missing credentials while optional auth stays public
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:122
- Evidence: [unit.log](unit.log)

### UNIT-016 — email validation rejects malformed input

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: email validation rejects malformed input
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:140
- Evidence: [unit.log](unit.log)

### UNIT-017 — item validation normalizes valid data and reports invalid fields

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: item validation normalizes valid data and reports invalid fields
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:150
- Evidence: [unit.log](unit.log)

### UNIT-018 — AI response helpers parse plain and fenced JSON safely

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: AI response helpers parse plain and fenced JSON safely
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:177
- Evidence: [unit.log](unit.log)

### UNIT-019 — AI score normalization and disabled mode are deterministic

- Module: test/backend.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: AI score normalization and disabled mode are deterministic
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backend.test.cjs:186
- Evidence: [unit.log](unit.log)

### UNIT-020 — backup refuses relative or missing executable paths before starting a dump

- Module: test/backup-executables.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: backup refuses relative or missing executable paths before starting a dump
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backup-executables.test.cjs:8
- Evidence: [unit.log](unit.log)

### UNIT-021 — restore check rejects an unsafe target and an unrecognized backup

- Module: test/backup-executables.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: restore check rejects an unsafe target and an unrecognized backup
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/backup-executables.test.cjs:39
- Evidence: [unit.log](unit.log)

### UNIT-022 — suggested and custom physical colors both affect matching

- Module: test/card-colors.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: suggested and custom physical colors both affect matching
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/card-colors.test.cjs:43
- Evidence: [unit.log](unit.log)

### UNIT-023 — item colour validation accepts a palette hex and ignores old card colour input

- Module: test/card-colors.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: item colour validation accepts a palette hex and ignores old card colour input
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/card-colors.test.cjs:51
- Evidence: [unit.log](unit.log)

### UNIT-024 — lost and found posts persist physical colour without a card colour

- Module: test/card-colors.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost and found posts persist physical colour without a card colour
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/card-colors.test.cjs:64
- Evidence: [unit.log](unit.log)

### UNIT-025 — decorative card colours never affect matching text evidence

- Module: test/card-colors.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: decorative card colours never affect matching text evidence
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/card-colors.test.cjs:105
- Evidence: [unit.log](unit.log)

### UNIT-026 — legacy picker values move once with audit and rescan, while physical descriptions and existing card choices survive

- Module: test/card-colors.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: legacy picker values move once with audit and rescan, while physical descriptions and existing card choices survive
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/card-colors.test.cjs:134
- Evidence: [unit.log](unit.log)

### UNIT-027 — 30 labelled illustrations and complete reports use valid fields and balanced categories

- Module: test/demo-seed.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: 30 labelled illustrations and complete reports use valid fields and balanced categories
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/demo-seed.test.cjs:14
- Evidence: [unit.log](unit.log)

### UNIT-028 — seed keeps original accounts and reports, has all point links and no outgoing side effects

- Module: test/demo-seed.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: seed keeps original accounts and reports, has all point links and no outgoing side effects
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/demo-seed.test.cjs:28
- Evidence: [unit.log](unit.log)

### UNIT-029 — a collection point collision rolls back the whole seed rather than repurposing real data

- Module: test/demo-seed.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a collection point collision rolls back the whole seed rather than repurposing real data
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/demo-seed.test.cjs:43
- Evidence: [unit.log](unit.log)

### UNIT-030 — local demo staff uses username, cannot become admin, expires and is blocked in production

- Module: test/demo-staff.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: local demo staff uses username, cannot become admin, expires and is blocked in production
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/demo-staff.test.cjs:7
- Evidence: [unit.log](unit.log)

### UNIT-031 — required fields reject empty/whitespace but never modify original input

- Module: test/form-validation.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: required fields reject empty/whitespace but never modify original input
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/form-validation.test.cjs:12
- Evidence: [unit.log](unit.log)

### UNIT-032 — required selects, files, checkboxes and field constraints have specific feedback

- Module: test/form-validation.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: required selects, files, checkboxes and field constraints have specific feedback
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/form-validation.test.cjs:30
- Evidence: [unit.log](unit.log)

### UNIT-033 — numeric conversion happens at submission, rejects blanks and preserves real zero

- Module: test/form-validation.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: numeric conversion happens at submission, rejects blanks and preserves real zero
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/form-validation.test.cjs:64
- Evidence: [unit.log](unit.log)

### UNIT-034 — Google authentication accepts only a verified exact KU domain and a valid server-verified token

- Module: test/google-ku-domain.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Google authentication accepts only a verified exact KU domain and a valid server-verified token
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/google-ku-domain.test.cjs:4
- Evidence: [unit.log](unit.log)

### UNIT-035 — local vision uses normalized AI feature cosine rather than filename or text similarity

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: local vision uses normalized AI feature cosine rather than filename or text similarity
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:56
- Evidence: [unit.log](unit.log)

### UNIT-036 — missing, external, profile, query, encoded traversal and nonexistent paths never reach AI

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: missing, external, profile, query, encoded traversal and nonexistent paths never reach AI
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:77
- Evidence: [unit.log](unit.log)

### UNIT-037 — the cache hashes actual file bytes and invalidates overwrites, even with the same filename

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: the cache hashes actual file bytes and invalidates overwrites, even with the same filename
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:113
- Evidence: [unit.log](unit.log)

### UNIT-038 — blank, tiny, malformed, oversized and pixel-bomb images cannot produce a visual match

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: blank, tiny, malformed, oversized and pixel-bomb images cannot produce a visual match
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:131
- Evidence: [unit.log](unit.log)

### UNIT-039 — upload directory junctions and image symlinks cannot escape the item upload root

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: upload directory junctions and image symlinks cannot escape the item upload root
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:175
- Evidence: [unit.log](unit.log)

### UNIT-040 — an image-file symlink is rejected even when its target is another permitted item image

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: an image-file symlink is rejected even when its target is another permitted item image
- Actual: Not executed: Windows host does not permit creating the requested file symlink
- Initial status: BLOCKED; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:199
- Evidence: [unit.log](unit.log)

### UNIT-041 — concurrent repeated comparisons share inference for each actual image content

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: concurrent repeated comparisons share inference for each actual image content
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:228
- Evidence: [unit.log](unit.log)

### UNIT-042 — failed or malformed embeddings report unavailable instead of falling back to a match

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: failed or malformed embeddings report unavailable instead of falling back to a match
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:247
- Evidence: [unit.log](unit.log)

### UNIT-043 — embedding cache is bounded to 128 entries, retains content keys and evicts old images

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: embedding cache is bounded to 128 entries, retains content keys and evicts old images
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:269
- Evidence: [unit.log](unit.log)

### UNIT-044 — a single worker serializes inference, bounds its queue and terminates timed-out execution

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a single worker serializes inference, bounds its queue and terminates timed-out execution
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:304
- Evidence: [unit.log](unit.log)

### UNIT-045 — test injection is unavailable outside the test environment

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: test injection is unavailable outside the test environment
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:338
- Evidence: [unit.log](unit.log)

### UNIT-046 — offline real DINOv2 inference separates a synthetic key from a backpack

- Module: test/local-vision.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: offline real DINOv2 inference separates a synthetic key from a backpack
- Actual: Not executed: optional real-model smoke is off and backend/.cache/matching-models is absent
- Initial status: BLOCKED; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/local-vision.test.cjs:357
- Evidence: [unit.log](unit.log)

### UNIT-047 — localized JSX translates UI branches without translating names, free text or API values

- Module: test/localization.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: localized JSX translates UI branches without translating names, free text or API values
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/localization.test.cjs:6
- Evidence: [unit.log](unit.log)

### UNIT-048 — English dictionary contains non-empty translations including backend validation errors

- Module: test/localization.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English dictionary contains non-empty translations including backend validation errors
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/localization.test.cjs:83
- Evidence: [unit.log](unit.log)

### UNIT-049 — known notifications translate only the system envelope and preserve captured data

- Module: test/localization.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: known notifications translate only the system envelope and preserve captured data
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/localization.test.cjs:94
- Evidence: [unit.log](unit.log)

### UNIT-050 — approved cleanup preserves unrelated records, old account and credentials

- Module: test/maintenance-cleanup.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: approved cleanup preserves unrelated records, old account and credentials
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/maintenance-cleanup.test.cjs:20
- Evidence: [unit.log](unit.log)

### UNIT-051 — an import identity conflict rolls back deleted items and jobs

- Module: test/maintenance-cleanup.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: an import identity conflict rolls back deleted items and jobs
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/maintenance-cleanup.test.cjs:30
- Evidence: [unit.log](unit.log)

### UNIT-052 — an approved item gaining an owner prevents deletion and rolls back

- Module: test/maintenance-cleanup.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: an approved item gaining an owner prevents deletion and rolls back
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/maintenance-cleanup.test.cjs:40
- Evidence: [unit.log](unit.log)

### UNIT-053 — labelled datasets reject leakage, missing labels and repeated ids

- Module: test/matching-evaluation.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: labelled datasets reject leakage, missing labels and repeated ids
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching-evaluation.test.cjs:16
- Evidence: [unit.log](unit.log)

### UNIT-054 — evaluation reports false positives and cannot claim accuracy when no predictions exist

- Module: test/matching-evaluation.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: evaluation reports false positives and cannot claim accuracy when no predictions exist
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching-evaluation.test.cjs:42
- Evidence: [unit.log](unit.log)

### UNIT-055 — identical report text cannot override unrelated photographs

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: identical report text cannot override unrelated photographs
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:133
- Evidence: [unit.log](unit.log)

### UNIT-056 — automatic match notifications require a score of at least 95

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: automatic match notifications require a score of at least 95
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:153
- Evidence: [unit.log](unit.log)

### UNIT-057 — different selected item colors keep an otherwise similar pair below the alert threshold

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: different selected item colors keep an otherwise similar pair below the alert threshold
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:175
- Evidence: [unit.log](unit.log)

### UNIT-058 — missing, invalid or low-quality photographs never create an automatic match

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: missing, invalid or low-quality photographs never create an automatic match
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:185
- Evidence: [unit.log](unit.log)

### UNIT-059 — an unavailable vision model fails closed and leaves matching pending

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: an unavailable vision model fails closed and leaves matching pending
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:215
- Evidence: [unit.log](unit.log)

### UNIT-060 — the durable worker retries unavailable vision rather than completing the job

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: the durable worker retries unavailable vision rather than completing the job
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:230
- Evidence: [unit.log](unit.log)

### UNIT-061 — durable jobs preserve PostgreSQL timestamp precision when completing work

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: durable jobs preserve PostgreSQL timestamp precision when completing work
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:255
- Evidence: [unit.log](unit.log)

### UNIT-062 — a report requeued during inference remains pending after the old job finishes

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a report requeued during inference remains pending after the old job finishes
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:277
- Evidence: [unit.log](unit.log)

### UNIT-063 — overlapping worker flushes never run duplicate inference for one report

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: overlapping worker flushes never run duplicate inference for one report
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:306
- Evidence: [unit.log](unit.log)

### UNIT-064 — a true pair after the first vision batch is eventually evaluated before completion

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a true pair after the first vision batch is eventually evaluated before completion
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:340
- Evidence: [unit.log](unit.log)

### UNIT-065 — continuation preserves eligible results from the first vision batch

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: continuation preserves eligible results from the first vision batch
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:400
- Evidence: [unit.log](unit.log)

### UNIT-066 — unavailable tail inference retries that candidate without rescanning completed batches

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: unavailable tail inference retries that candidate without rescanning completed batches
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:442
- Evidence: [unit.log](unit.log)

### UNIT-067 — lowering the administrator threshold does not bypass the visual minimum

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lowering the administrator threshold does not bypass the visual minimum
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:494
- Evidence: [unit.log](unit.log)

### UNIT-068 — a high visual score is not evidence when both images were not compared

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a high visual score is not evidence when both images were not compared
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:513
- Evidence: [unit.log](unit.log)

### UNIT-069 — high visual similarity cannot override object contradictions

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: high visual similarity cannot override object contradictions
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:532
- Evidence: [unit.log](unit.log)

### UNIT-070 — a visually supported pair persists auditable scores without asserting 100% certainty

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a visually supported pair persists auditable scores without asserting 100% certainty
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:570
- Evidence: [unit.log](unit.log)

### UNIT-071 — scanning one's own two reports does not call vision or create a match

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: scanning one's own two reports does not call vision or create a match
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:602
- Evidence: [unit.log](unit.log)

### UNIT-072 — matching requests require an owner session and queue expensive work

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: matching requests require an owner session and queue expensive work
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:617
- Evidence: [unit.log](unit.log)

### UNIT-073 — legacy text-only 100% matches stay hidden and cannot authorize claims

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: legacy text-only 100% matches stay hidden and cannot authorize claims
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:643
- Evidence: [unit.log](unit.log)

### UNIT-074 — staff-confirmed legacy pairs remain usable but never bypass physical claim verification

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: staff-confirmed legacy pairs remain usable but never bypass physical claim verification
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:670
- Evidence: [unit.log](unit.log)

### UNIT-075 — rechecking a previously supported pair invalidates conflicting visual evidence

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: rechecking a previously supported pair invalidates conflicting visual evidence
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:690
- Evidence: [unit.log](unit.log)

### UNIT-076 — a manually rejected pair cannot be reactivated by a high-scoring model

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a manually rejected pair cannot be reactivated by a high-scoring model
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:722
- Evidence: [unit.log](unit.log)

### UNIT-077 — public matching JSON cannot expose arbitrary or raw internal AI metadata

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public matching JSON cannot expose arbitrary or raw internal AI metadata
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:739
- Evidence: [unit.log](unit.log)

### UNIT-078 — SQL and JavaScript both reject malformed or out-of-range automatic visual evidence

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: SQL and JavaScript both reject malformed or out-of-range automatic visual evidence
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:779
- Evidence: [unit.log](unit.log)

### UNIT-079 — human-reviewed legacy output cannot expose model metadata or unrecognized provider/version strings

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: human-reviewed legacy output cannot expose model metadata or unrecognized provider/version strings
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:831
- Evidence: [unit.log](unit.log)

### UNIT-080 — retention alerts ignore inactive legacy pairs but preserve staff-confirmed owners and active claims

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: retention alerts ignore inactive legacy pairs but preserve staff-confirmed owners and active claims
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:865
- Evidence: [unit.log](unit.log)

### UNIT-081 — exhausted vision jobs are unavailable, not completed searches with no matches

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: exhausted vision jobs are unavailable, not completed searches with no matches
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:956
- Evidence: [unit.log](unit.log)

### UNIT-082 — matching job failures owned by another user do not mark the current search unavailable

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: matching job failures owned by another user do not mark the current search unavailable
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:973
- Evidence: [unit.log](unit.log)

### UNIT-083 — changed source and candidate inputs during vision cannot activate stale evidence

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: changed source and candidate inputs during vision cannot activate stale evidence
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:988
- Evidence: [unit.log](unit.log)

### UNIT-084 — expired inference leases cannot activate a pair or complete a newer worker's job

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: expired inference leases cannot activate a pair or complete a newer worker's job
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:1011
- Evidence: [unit.log](unit.log)

### UNIT-085 — an already expired lease is rejected before any visual inference starts

- Module: test/matching.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: an already expired lease is rejected before any visual inference starts
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/matching.test.cjs:1033
- Evidence: [unit.log](unit.log)

### UNIT-086 — monitor rejects a false-green health response, HTTP errors and TLS failures

- Module: test/monitor.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: monitor rejects a false-green health response, HTTP errors and TLS failures
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/monitor.test.cjs:4
- Evidence: [unit.log](unit.log)

### UNIT-087 — monthly availability never counts gaps or future time as proven uptime

- Module: test/monitor.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: monthly availability never counts gaps or future time as proven uptime
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/monitor.test.cjs:54
- Evidence: [unit.log](unit.log)

### UNIT-088 — verified roster normalizes email for comparison and keeps student identity

- Module: test/roster-repair.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: verified roster normalizes email for comparison and keeps student identity
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/roster-repair.test.cjs:32
- Evidence: [unit.log](unit.log)

### UNIT-089 — roster rejects duplicate IDs and malformed addresses before repair

- Module: test/roster-repair.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: roster rejects duplicate IDs and malformed addresses before repair
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/roster-repair.test.cjs:104
- Evidence: [unit.log](unit.log)

### UNIT-090 — dry run reports only corrupted matching accounts and never starts a write transaction

- Module: test/roster-repair.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: dry run reports only corrupted matching accounts and never starts a write transaction
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/roster-repair.test.cjs:124
- Evidence: [unit.log](unit.log)

### UNIT-091 — repair updates guarded name fields and rolls back if a user changed meanwhile

- Module: test/roster-repair.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: repair updates guarded name fields and rolls back if a user changed meanwhile
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/roster-repair.test.cjs:174
- Evidence: [unit.log](unit.log)

### UNIT-092 — first-use OTP grants password setup only; replay and non-KU email rejected

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: first-use OTP grants password setup only; replay and non-KU email rejected
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:70
- Evidence: [unit.log](unit.log)

### UNIT-093 — password creation is one-use, salted and cannot promote a new user to staff

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: password creation is one-use, salted and cannot promote a new user to staff
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:101
- Evidence: [unit.log](unit.log)

### UNIT-094 — staff can log in with their username while student IDs cannot be used as usernames

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: staff can log in with their username while student IDs cannot be used as usernames
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:155
- Evidence: [unit.log](unit.log)

### UNIT-095 — users can update their profile image without changing identity fields

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: users can update their profile image without changing identity fields
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:174
- Evidence: [unit.log](unit.log)

### UNIT-096 — User Management changes are reflected in the user's profile

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: User Management changes are reflected in the user's profile
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:203
- Evidence: [unit.log](unit.log)

### UNIT-097 — Staff has operational permissions; role demotion and Inactive affect open sessions

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Staff has operational permissions; role demotion and Inactive affect open sessions
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:232
- Evidence: [unit.log](unit.log)

### UNIT-098 — AES-GCM rejects tampering and stores claim evidence as ciphertext

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: AES-GCM rejects tampering and stores claim evidence as ciphertext
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:278
- Evidence: [unit.log](unit.log)

### UNIT-099 — automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:298
- Evidence: [unit.log](unit.log)

### UNIT-100 — public filters include brand/model/time but never reveal identity evidence

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public filters include brand/model/time but never reveal identity evidence
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:335
- Evidence: [unit.log](unit.log)

### UNIT-101 — report creation stores new form fields, encrypted private evidence and durable matching job atomically

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report creation stores new form fields, encrypted private evidence and durable matching job atomically
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:350
- Evidence: [unit.log](unit.log)

### UNIT-102 — Google login is disabled by default and only links verified KU roster accounts

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Google login is disabled by default and only links verified KU roster accounts
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:389
- Evidence: [unit.log](unit.log)

### UNIT-103 — found reports accept only active collection points and store the canonical point name

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found reports accept only active collection points and store the canonical point name
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:496
- Evidence: [unit.log](unit.log)

### UNIT-104 — forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:545
- Evidence: [unit.log](unit.log)

### UNIT-105 — scheduler dispatches due daily backup, records success and does not rerun it immediately

- Module: test/security.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: scheduler dispatches due daily backup, records success and does not rerun it immediately
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:598
- Evidence: [unit.log](unit.log)

### UNIT-106 — new report profiles persist, are reused, refresh, and cascade on deletion

- Module: test/visual-profiles.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: new report profiles persist, are reused, refresh, and cascade on deletion
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/visual-profiles.test.cjs:7
- Evidence: [unit.log](unit.log)

### UNIT-107 — offline training uses approved claims and staff-rejected pairs, not rejected claims

- Module: test/visual-training-labels.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: offline training uses approved claims and staff-rejected pairs, not rejected claims
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/visual-training-labels.test.cjs:7
- Evidence: [unit.log](unit.log)

### UNIT-108 — weight training refuses datasets with too few confirmed positives or rejected negatives

- Module: test/visual-training.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: weight training refuses datasets with too few confirmed positives or rejected negatives
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/visual-training.test.cjs:30
- Evidence: [unit.log](unit.log)

### UNIT-109 — training and validation never share a lost or found report

- Module: test/visual-training.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: training and validation never share a lost or found report
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/visual-training.test.cjs:37
- Evidence: [unit.log](unit.log)

### UNIT-110 — shared candidate items cannot leak between splits

- Module: test/visual-training.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: shared candidate items cannot leak between splits
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/visual-training.test.cjs:58
- Evidence: [unit.log](unit.log)

### UNIT-111 — the same photo reused under another report id stays in one split

- Module: test/visual-training.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: the same photo reused under another report id stays in one split
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/visual-training.test.cjs:70
- Evidence: [unit.log](unit.log)

### UNIT-112 — PDF export is protected, validates scope and produces a real embedded-font PDF

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: PDF export is protected, validates scope and produces a real embedded-font PDF
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:33
- Evidence: [unit.log](unit.log)

### UNIT-113 — manual migration is idempotent and preserves existing reports

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: manual migration is idempotent and preserves existing reports
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:137
- Evidence: [unit.log](unit.log)

### UNIT-114 — all new admin resources reject unauthenticated and regular user sessions

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: all new admin resources reject unauthenticated and regular user sessions
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:156
- Evidence: [unit.log](unit.log)

### UNIT-115 — existing admin login remains functional

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: existing admin login remains functional
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:182
- Evidence: [unit.log](unit.log)

### UNIT-116 — point management validates coordinates and prevents duplicate names

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: point management validates coordinates and prevents duplicate names
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:204
- Evidence: [unit.log](unit.log)

### UNIT-117 — item handling records private attributes and point without permitting direct return

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: item handling records private attributes and point without permitting direct return
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:231
- Evidence: [unit.log](unit.log)

### UNIT-118 — public listing exposes the basic description but keeps identifying details private

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public listing exposes the basic description but keeps identifying details private
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:266
- Evidence: [unit.log](unit.log)

### UNIT-119 — matching requires visual evidence and persists scores plus deduplicated notifications

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: matching requires visual evidence and persists scores plus deduplicated notifications
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:275
- Evidence: [unit.log](unit.log)

### UNIT-120 — admin match confirmation notifies both reporters with the confirmation time

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: admin match confirmation notifies both reporters with the confirmation time
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:304
- Evidence: [unit.log](unit.log)

### UNIT-121 — claim enforces own lost report, prevents duplicate submission and requires manual identity check

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: claim enforces own lost report, prevents duplicate submission and requires manual identity check
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:342
- Evidence: [unit.log](unit.log)

### UNIT-122 — release changes both reports atomically, retains audit, and prevents more claims

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: release changes both reports atomically, retains audit, and prevents more claims
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:410
- Evidence: [unit.log](unit.log)

### UNIT-123 — new ticket can be investigated; notes and status are audited

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: new ticket can be investigated; notes and status are audited
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:460
- Evidence: [unit.log](unit.log)

### UNIT-124 — user registry can be created and edited without deleting previous reports

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: user registry can be created and edited without deleting previous reports
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:497
- Evidence: [unit.log](unit.log)

### UNIT-125 — settings reject invalid policy and apply retention only to new reports

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: settings reject invalid policy and apply retention only to new reports
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:530
- Evidence: [unit.log](unit.log)

### UNIT-126 — notifications can only be marked read by their owner

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: notifications can only be marked read by their owner
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:601
- Evidence: [unit.log](unit.log)

### UNIT-127 — search filters, daily/monthly/yearly statistics and real Excel workbook are usable

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search filters, daily/monthly/yearly statistics and real Excel workbook are usable
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:632
- Evidence: [unit.log](unit.log)

### UNIT-128 — privacy correction requires identity verification, updates users and prevents replay

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: privacy correction requires identity verification, updates users and prevents replay
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:665
- Evidence: [unit.log](unit.log)

### UNIT-129 — personal-data export contains only the owner data and never authentication secrets

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: personal-data export contains only the owner data and never authentication secrets
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:720
- Evidence: [unit.log](unit.log)

### UNIT-130 — erasure completion requires external evidence and does not automatically destroy records

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: erasure completion requires external evidence and does not automatically destroy records
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:739
- Evidence: [unit.log](unit.log)

### UNIT-131 — withdrawal closes an account reversibly and blocks its existing session

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: withdrawal closes an account reversibly and blocks its existing session
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:790
- Evidence: [unit.log](unit.log)

### UNIT-132 — direct found-item claim requires identity check and confirmed handover

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: direct found-item claim requires identity check and confirmed handover
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:837
- Evidence: [unit.log](unit.log)

### UNIT-133 — failed verification before handover rejects the old pair and queues both reports for new matches

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: failed verification before handover rejects the old pair and queues both reports for new matches
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:933
- Evidence: [unit.log](unit.log)

### UNIT-134 — a direct found-item claim can be declined before handover and the item is searchable again

- Module: test/workflow.test.cjs
- Preconditions: Isolated PGlite PostgreSQL engine; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a direct found-item claim can be declined before handover and the item is searchable again
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:1002
- Evidence: [unit.log](unit.log)

### PG-001 — first-use OTP grants password setup only; replay and non-KU email rejected

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: first-use OTP grants password setup only; replay and non-KU email rejected
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:70
- Evidence: [postgres.log](postgres.log)

### PG-002 — password creation is one-use, salted and cannot promote a new user to staff

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: password creation is one-use, salted and cannot promote a new user to staff
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:101
- Evidence: [postgres.log](postgres.log)

### PG-003 — staff can log in with their username while student IDs cannot be used as usernames

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: staff can log in with their username while student IDs cannot be used as usernames
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:155
- Evidence: [postgres.log](postgres.log)

### PG-004 — users can update their profile image without changing identity fields

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: users can update their profile image without changing identity fields
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:174
- Evidence: [postgres.log](postgres.log)

### PG-005 — User Management changes are reflected in the user's profile

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: User Management changes are reflected in the user's profile
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:203
- Evidence: [postgres.log](postgres.log)

### PG-006 — Staff has operational permissions; role demotion and Inactive affect open sessions

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Staff has operational permissions; role demotion and Inactive affect open sessions
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:232
- Evidence: [postgres.log](postgres.log)

### PG-007 — AES-GCM rejects tampering and stores claim evidence as ciphertext

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: AES-GCM rejects tampering and stores claim evidence as ciphertext
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:278
- Evidence: [postgres.log](postgres.log)

### PG-008 — automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: automatic retention produces distinct reminders/expiry for reporter and staff, with deduplicated encrypted outbox
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:298
- Evidence: [postgres.log](postgres.log)

### PG-009 — public filters include brand/model/time but never reveal identity evidence

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public filters include brand/model/time but never reveal identity evidence
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:335
- Evidence: [postgres.log](postgres.log)

### PG-010 — report creation stores new form fields, encrypted private evidence and durable matching job atomically

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report creation stores new form fields, encrypted private evidence and durable matching job atomically
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:350
- Evidence: [postgres.log](postgres.log)

### PG-011 — Google login is disabled by default and only links verified KU roster accounts

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Google login is disabled by default and only links verified KU roster accounts
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:389
- Evidence: [postgres.log](postgres.log)

### PG-012 — found reports accept only active collection points and store the canonical point name

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found reports accept only active collection points and store the canonical point name
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:496
- Evidence: [postgres.log](postgres.log)

### PG-013 — forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: forgot-password OTP locks after five wrong guesses, resets the password and revokes old sessions
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:545
- Evidence: [postgres.log](postgres.log)

### PG-014 — scheduler dispatches due daily backup, records success and does not rerun it immediately

- Module: test/security.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: scheduler dispatches due daily backup, records success and does not rerun it immediately
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/security.test.cjs:598
- Evidence: [postgres.log](postgres.log)

### PG-015 — PDF export is protected, validates scope and produces a real embedded-font PDF

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: PDF export is protected, validates scope and produces a real embedded-font PDF
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:33
- Evidence: [postgres.log](postgres.log)

### PG-016 — manual migration is idempotent and preserves existing reports

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: manual migration is idempotent and preserves existing reports
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:137
- Evidence: [postgres.log](postgres.log)

### PG-017 — all new admin resources reject unauthenticated and regular user sessions

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: all new admin resources reject unauthenticated and regular user sessions
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:156
- Evidence: [postgres.log](postgres.log)

### PG-018 — existing admin login remains functional

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: existing admin login remains functional
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:182
- Evidence: [postgres.log](postgres.log)

### PG-019 — point management validates coordinates and prevents duplicate names

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: point management validates coordinates and prevents duplicate names
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:204
- Evidence: [postgres.log](postgres.log)

### PG-020 — item handling records private attributes and point without permitting direct return

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: item handling records private attributes and point without permitting direct return
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:231
- Evidence: [postgres.log](postgres.log)

### PG-021 — public listing exposes the basic description but keeps identifying details private

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public listing exposes the basic description but keeps identifying details private
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:266
- Evidence: [postgres.log](postgres.log)

### PG-022 — matching requires visual evidence and persists scores plus deduplicated notifications

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: matching requires visual evidence and persists scores plus deduplicated notifications
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:275
- Evidence: [postgres.log](postgres.log)

### PG-023 — admin match confirmation notifies both reporters with the confirmation time

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: admin match confirmation notifies both reporters with the confirmation time
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:304
- Evidence: [postgres.log](postgres.log)

### PG-024 — claim enforces own lost report, prevents duplicate submission and requires manual identity check

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: claim enforces own lost report, prevents duplicate submission and requires manual identity check
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:342
- Evidence: [postgres.log](postgres.log)

### PG-025 — release changes both reports atomically, retains audit, and prevents more claims

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: release changes both reports atomically, retains audit, and prevents more claims
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:410
- Evidence: [postgres.log](postgres.log)

### PG-026 — new ticket can be investigated; notes and status are audited

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: new ticket can be investigated; notes and status are audited
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:460
- Evidence: [postgres.log](postgres.log)

### PG-027 — user registry can be created and edited without deleting previous reports

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: user registry can be created and edited without deleting previous reports
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:497
- Evidence: [postgres.log](postgres.log)

### PG-028 — settings reject invalid policy and apply retention only to new reports

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: settings reject invalid policy and apply retention only to new reports
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:530
- Evidence: [postgres.log](postgres.log)

### PG-029 — notifications can only be marked read by their owner

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: notifications can only be marked read by their owner
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:601
- Evidence: [postgres.log](postgres.log)

### PG-030 — search filters, daily/monthly/yearly statistics and real Excel workbook are usable

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search filters, daily/monthly/yearly statistics and real Excel workbook are usable
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:632
- Evidence: [postgres.log](postgres.log)

### PG-031 — privacy correction requires identity verification, updates users and prevents replay

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: privacy correction requires identity verification, updates users and prevents replay
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:665
- Evidence: [postgres.log](postgres.log)

### PG-032 — personal-data export contains only the owner data and never authentication secrets

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: personal-data export contains only the owner data and never authentication secrets
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:720
- Evidence: [postgres.log](postgres.log)

### PG-033 — erasure completion requires external evidence and does not automatically destroy records

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: erasure completion requires external evidence and does not automatically destroy records
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:739
- Evidence: [postgres.log](postgres.log)

### PG-034 — withdrawal closes an account reversibly and blocks its existing session

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: withdrawal closes an account reversibly and blocks its existing session
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:790
- Evidence: [postgres.log](postgres.log)

### PG-035 — direct found-item claim requires identity check and confirmed handover

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: direct found-item claim requires identity check and confirmed handover
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:837
- Evidence: [postgres.log](postgres.log)

### PG-036 — failed verification before handover rejects the old pair and queues both reports for new matches

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: failed verification before handover rejects the old pair and queues both reports for new matches
- Actual: not ok 36 - failed verification before handover rejects the old pair and queues both reports for new matches
  ---
  duration_ms: 333.3075
  type: 'test'
  location: 'C:\\IT_PROJECT_GitHub\\FOUNDLOST\\test\\workflow.test.cjs:933:1'
  failureType: 'testCodeFailure'
  error: |-
    The expression evaluated to a falsy value:

      assert.ok(visible.body.matches.some((row) => row.match.item_id === alternative))

  code: 'ERR_ASSERTION'
  name: 'AssertionError'
  expected: true
  actual: false
  operator: '=='
  stack: |-
    TestContext.<anonymous> (C:\IT_PROJECT_GitHub\FOUNDLOST\test\workflow.test.cjs:998:10)
    process.processTicksAndRejections (node:internal/process/task_queues:105:5)
    async Test.run (node:internal/test_runner/test:1054:7)
    async Test.processPendingSubtests (node:internal/test_runner/test:744:7)
  ...
# Subtest: a direct found-item claim can be declined before handover and the item is searchable again
ok 37 - a direct found-item claim can be declined before handover and the item is searchable again
  ---
  duration_ms: 142.9551
  type: 'test'
  ...
1..37
# tests 37
# suites 0
# pass 36
# fail 1
# cancelled 0
# skipped 0
# todo 0
# duration_ms 15854.9075

- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-06
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:933
- Evidence: [postgres.log](postgres.log)

### PG-037 — a direct found-item claim can be declined before handover and the item is searchable again

- Module: test/workflow.test.cjs
- Preconditions: Fresh real PostgreSQL 16 database, synthetic records; deleted after test; migrations/fixture setup as declared in test file
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a direct found-item claim can be declined before handover and the item is searchable again
- Actual: All assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/workflow.test.cjs:1002
- Evidence: [postgres.log](postgres.log)

### WEB-001 — primary screens pass automated WCAG AA checks on desktop and mobile

- Module: accessibility.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: primary screens pass automated WCAG AA checks on desktop and mobile
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/accessibility.spec.js:65
- Evidence: [browser-results.json#d316df4bad39fab891ed-8a9d55701e653c67e1e6](browser-results.json)

### WEB-002 — public administrator login is accessible without an existing session

- Module: accessibility.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public administrator login is accessible without an existing session
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/accessibility.spec.js:129
- Evidence: [browser-results.json#d316df4bad39fab891ed-6ebec5e3964181048fe4](browser-results.json)

### WEB-003 — skip link and signout confirmation work with keyboard and accessible dialog

- Module: accessibility.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: skip link and signout confirmation work with keyboard and accessible dialog
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/accessibility.spec.js:138
- Evidence: [browser-results.json#d316df4bad39fab891ed-a3417a5207ae358d1b5e](browser-results.json)

### WEB-004 — admin login and all console navigation work with real API data

- Module: admin.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: admin login and all console navigation work with real API data
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/admin.spec.js:46
- Evidence: [browser-results.json#73482573f1568b679d78-0a56f0de96bf70a35749](browser-results.json)

### WEB-005 — staff portal contains the six operational pages

- Module: admin.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: staff portal contains the six operational pages
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/admin.spec.js:81
- Evidence: [browser-results.json#73482573f1568b679d78-0266efda148feb9ebe2a](browser-results.json)

### WEB-006 — console pages fit desktop and mobile and capture real-data screenshots

- Module: admin.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: console pages fit desktop and mobile and capture real-data screenshots
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/admin.spec.js:112
- Evidence: [browser-results.json#73482573f1568b679d78-06dcfd475514e6860038](browser-results.json)

### WEB-007 — collection point editor saves, traps dialog focus and closes with Escape

- Module: admin.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: collection point editor saves, traps dialog focus and closes with Escape
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/admin.spec.js:150
- Evidence: [browser-results.json#73482573f1568b679d78-3eaa1db0cdbd6ffaaa43](browser-results.json)

### WEB-008 — statistics downloads a real Excel workbook and has printable report layout

- Module: admin.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: statistics downloads a real Excel workbook and has printable report layout
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/admin.spec.js:170
- Evidence: [browser-results.json#73482573f1568b679d78-528728bb1d3d60cdf633](browser-results.json)

### WEB-009 — user submits hidden-attribute claim and staff approves then releases the item

- Module: admin.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: user submits hidden-attribute claim and staff approves then releases the item
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/admin.spec.js:190
- Evidence: [browser-results.json#73482573f1568b679d78-4ba78d3923acaf916470](browser-results.json)

### WEB-010 — failed search removes old cards and retry returns new results

- Module: audit-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: failed search removes old cards and retry returns new results
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/audit-regression.spec.js:11
- Evidence: [browser-results.json#72652b23863ffa3bf64c-417473040b6e8e4c913b](browser-results.json)

### WEB-011 — map follows pagination without inventing hidden/custom-location markers

- Module: audit-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: map follows pagination without inventing hidden/custom-location markers
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/audit-regression.spec.js:47
- Evidence: [browser-results.json#72652b23863ffa3bf64c-051d979518dc2bcb1f0e](browser-results.json)

### WEB-012 — signin keeps recovery below password and removes the first-use shortcut

- Module: auth-design.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: signin keeps recovery below password and removes the first-use shortcut
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/auth-design.spec.js:3
- Evidence: [browser-results.json#6da31c2cabaab1175e9f-b33c4a2c871b25369145](browser-results.json)

### WEB-013 — signup and OTP follow the desktop and mobile layouts

- Module: auth-design.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: signup and OTP follow the desktop and mobile layouts
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/auth-design.spec.js:20
- Evidence: [browser-results.json#6da31c2cabaab1175e9f-d8d329617d02d838c8d9](browser-results.json)

### WEB-014 — first-use email OTP, password creation, logout and password login work end to end

- Module: auth.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: first-use email OTP, password creation, logout and password login work end to end
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/auth.spec.js:2
- Evidence: [browser-results.json#d5ed79a6b333c2ba7209-5a87dc8387a0b336c0b7](browser-results.json)

### WEB-015 — login, privacy and public listing filters fit a narrow screen

- Module: auth.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: login, privacy and public listing filters fit a narrow screen
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/auth.spec.js:59
- Evidence: [browser-results.json#d5ed79a6b333c2ba7209-ddc51993af214b73afc8](browser-results.json)

### WEB-016 — login and filter action pairs have equal sizes on desktop and mobile

- Module: button-sizing.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: login and filter action pairs have equal sizes on desktop and mobile
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/button-sizing.spec.js:3
- Evidence: [browser-results.json#bbd4797d020ccaa4e92b-d026472ea6252bef4944](browser-results.json)

### WEB-017 — lost form offers item colours and no card colour

- Module: card-colors.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost form offers item colours and no card colour
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/card-colors.spec.js:4
- Evidence: [browser-results.json#db3f4f51b4c666877c19-827f29cbe61938393309](browser-results.json)

### WEB-018 — found form offers item colours and no card colour

- Module: card-colors.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found form offers item colours and no card colour
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/card-colors.spec.js:4
- Evidence: [browser-results.json#db3f4f51b4c666877c19-4ec7fb0b437c748100f8](browser-results.json)

### WEB-019 — designed user screens work without horizontal overflow on mobile and desktop

- Module: design-responsive.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: designed user screens work without horizontal overflow on mobile and desktop
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/design-responsive.spec.js:12
- Evidence: [browser-results.json#8ccb31a92ccd0d693022-bf8bde49030faa6f7fe5](browser-results.json)

### WEB-020 — public screens fit desktop and mobile

- Module: design-responsive.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public screens fit desktop and mobile
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/design-responsive.spec.js:31
- Evidence: [browser-results.json#8ccb31a92ccd0d693022-b987d6c31c63ac774276](browser-results.json)

### WEB-021 — catalogue cards open a usable detail page

- Module: design-responsive.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: catalogue cards open a usable detail page
- Actual: Error: [2mexpect([22m[31mlocator[39m[2m).[22mtoBeVisible[2m([22m[2m)[22m failed

Locator: locator('.fl-item-card').first()
Expected: visible
Timeout: 5000ms
Error: element(s) not found

Call log:
[2m  - Expect "toBeVisible" locator('.fl-item-card').first() with timeout 5000ms[22m
[2m  - waiting for locator('.fl-item-card').first()[22m


  45 |   await page.goto("/foundPage");
  46 |   const card = page.locator(".fl-item-card").first();
> 47 |   await expect(card).toBeVisible();
     |                      ^
  48 |   await card.click();
  49 |   await expect(page).toHaveURL(/\/items\/found\/\d+/);
  50 |   await expect(page.locator(".item-detail-sheet h1")).toBeVisible();
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\design-responsive.spec.js:47:22
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-01
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/design-responsive.spec.js:43
- Evidence: [browser-results.json#8ccb31a92ccd0d693022-8413148541d0366b9de2](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#8ccb31a92ccd0d693022-8413148541d0366b9de2

### WEB-022 — profile and item details display API values on desktop and mobile

- Module: design-responsive.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: profile and item details display API values on desktop and mobile
- Actual: TypeError: Cannot read properties of undefined (reading 'item_id')

  63 |       const { items } = await response.json();
  64 |       const item = items[0];
> 65 |       await page.goto(`/items/${kind}/${item.item_id}`);
     |                                              ^
  66 |       await expect(page.locator(".item-detail-sheet h1")).toHaveText(item.item_name);
  67 |       await expect(page.locator(".item-detail-place")).toContainText(item[`${kind}_location`]);
  68 |       await expect(page.locator(".item-detail-description")).toHaveText(item.description || "ไม่มีรายละเอียดเพิ่มเติม");
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\design-responsive.spec.js:65:46
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-01
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/design-responsive.spec.js:53
- Evidence: [browser-results.json#8ccb31a92ccd0d693022-86d8e3d18c617b097d63](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#8ccb31a92ccd0d693022-86d8e3d18c617b097d63

### WEB-023 — found report offers only configured collection points

- Module: design-responsive.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found report offers only configured collection points
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/design-responsive.spec.js:75
- Evidence: [browser-results.json#8ccb31a92ccd0d693022-b2bb3d54be32f43ca78c](browser-results.json)

### WEB-024 — Prompt loads and applies across public, auth, admin, and app screens

- Module: font.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Prompt loads and applies across public, auth, admin, and app screens
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/font.spec.js:3
- Evidence: [browser-results.json#0fc46787847a9080401a-743bc539498f9d92c6fa](browser-results.json)

### WEB-025 — login has inline localized feedback, focuses invalid fields and keeps password bytes

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: login has inline localized feedback, focuses invalid fields and keeps password bytes
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:23
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-86132139919f855a47ac](browser-results.json)

### WEB-026 — blank numbers stay blank and genuine zero is submitted as a number

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: blank numbers stay blank and genuine zero is submitted as a number
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:64
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-fb4761fde4f8b47dcb7b](browser-results.json)

### WEB-027 — whitespace-only request blocked before API at /services

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: whitespace-only request blocked before API at /services
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:120
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-7d92bc2375cdf7088cf8](browser-results.json)

### WEB-028 — whitespace-only request blocked before API at /privacy

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: whitespace-only request blocked before API at /privacy
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:120
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-b9c02c17edb0b8355612](browser-results.json)

### WEB-029 — OTP explains disabled button and updates the digit count in both languages

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: OTP explains disabled button and updates the digit count in both languages
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:149
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-44c5762b21c25d3261ad](browser-results.json)

### WEB-030 — a dropped image satisfies upload validation and reset removes old errors

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: a dropped image satisfies upload validation and reset removes old errors
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:171
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-07cbb505f65c52487c7d](browser-results.json)

### WEB-031 — staff direct claim review explains missing note and identity confirmation

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: staff direct claim review explains missing note and identity confirmation
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:212
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-ea71cb508d4f64a38b37](browser-results.json)

### WEB-032 — staff can decline an approved claim before handover with a reason

- Module: form-validation.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: staff can decline an approved claim before handover with a reason
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/form-validation.spec.js:260
- Evidence: [browser-results.json#f5f833b1f3ed8e7bc188-b22a19e3dbf81ce510e0](browser-results.json)

### WEB-033 — language switch keeps the local welcome layout and keyboard skip link

- Module: github-features.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: language switch keeps the local welcome layout and keyboard skip link
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/github-features.spec.js:16
- Evidence: [browser-results.json#7db16c8f6a7a104e5e0f-66d3a680b89c6d3aa1c8](browser-results.json)

### WEB-034 — report form submits only the selected physical colour

- Module: github-features.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report form submits only the selected physical colour
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/github-features.spec.js:31
- Evidence: [browser-results.json#7db16c8f6a7a104e5e0f-e1aa2b9631a9e396beb0](browser-results.json)

### WEB-035 — ineligible visual evidence prevents submitting a claim

- Module: github-features.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: ineligible visual evidence prevents submitting a claim
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/github-features.spec.js:63
- Evidence: [browser-results.json#7db16c8f6a7a104e5e0f-4ee9d91787fa0bdbb250](browser-results.json)

### WEB-036 — KU Google button logs an existing roster account in without changing its role

- Module: google-auth.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: KU Google button logs an existing roster account in without changing its role
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/google-auth.spec.js:5
- Evidence: [browser-results.json#9d0b0c7b14b9f2c1cf1c-1515f2f97d5ed63949a4](browser-results.json)

### WEB-037 — rail labels are visible on expansion and cards ignore image aspect ratio

- Module: item-layout.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: rail labels are visible on expansion and cards ignore image aspect ratio
- Actual: Error: [2mexpect([22m[31mreceived[39m[2m).[22mtoBeCloseTo[2m([22m[32mexpected[39m[2m, [22mprecision[2m)[22m

Expected: [32m140[39m
Received: [31m147.99996948242188[39m

Expected precision:    1
Expected difference: < [32m0.05[39m
Received difference:   [31m7.999969482421875[39m

  30 |     // Translated hover rectangles can differ by floating-point subpixels.
  31 |     for (const size of sizes) {
> 32 |       expect(size.card).toBeCloseTo(width > 700 ? 350 : 140, 1);
     |                         ^
  33 |       expect(size.image).toBeCloseTo(width > 700 ? 190 : 80, 1);
  34 |     }
  35 |     if (width > 700) {
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\item-layout.spec.js:32:25
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-02
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/item-layout.spec.js:12
- Evidence: [browser-results.json#d7ad3d3174d1bfe1275d-ab51d2bb555366151ef3](browser-results.json)

### WEB-038 — detail recovery explains unmatched reports and handles matching service errors

- Module: item-layout.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: detail recovery explains unmatched reports and handles matching service errors
- Actual: Error: [2mexpect([22m[31mlocator[39m[2m).[22mtoBeVisible[2m([22m[2m)[22m failed

Locator: getByRole('link', { name: 'ลงประกาศของหาย', exact: true })
Expected: visible
Timeout: 5000ms
Error: element(s) not found

Call log:
[2m  - Expect "toBeVisible" getByRole('link', { name: 'ลงประกาศของหาย', exact: true }) with timeout 5000ms[22m
[2m  - waiting for getByRole('link', { name: 'ลงประกาศของหาย', exact: true })[22m


  58 |   await page.goto("/items/found/1");
  59 |   await page.getByRole("button", { name: "ยืนยันความเป็นเจ้าของ", exact: true }).click();
> 60 |   await expect(page.getByRole("link", { name: "ลงประกาศของหาย", exact: true })).toBeVisible();
     |                                                                                 ^
  61 |   await expect(page.getByRole("button", { name: "ส่งคำขอให้เจ้าหน้าที่" })).toHaveCount(0);
  62 |   await page.getByRole("button", { name: "ยกเลิก", exact: true }).click();
  63 |   await page.route(api + "/matching/all", (route) => route.fulfill({ status: 503, json: { error: "ไม่สามารถโหลดรายการยืนยันเจ้าของได้" } }));
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\item-layout.spec.js:60:81
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-03
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/item-layout.spec.js:51
- Evidence: [browser-results.json#d7ad3d3174d1bfe1275d-9cc04857bf64c39a98fc](browser-results.json)

### WEB-039 — item-by-ID endpoint authenticates, hides evidence and returns useful errors

- Module: item-layout.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: item-by-ID endpoint authenticates, hides evidence and returns useful errors
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/item-layout.spec.js:67
- Evidence: [browser-results.json#d7ad3d3174d1bfe1275d-1b5bfd86cf71ef14a797](browser-results.json)

### WEB-040 — language controls live only in settings and persist at 320px

- Module: language-settings.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: language controls live only in settings and persist at 320px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/language-settings.spec.js:23
- Evidence: [browser-results.json#2174ae091f7532347d9f-f4ccb25f6ecb0c0ca56e](browser-results.json)

### WEB-041 — language controls live only in settings and persist at 1440px

- Module: language-settings.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: language controls live only in settings and persist at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/language-settings.spec.js:23
- Evidence: [browser-results.json#2174ae091f7532347d9f-9ed6723396044b6ff588](browser-results.json)

### WEB-042 — public pages do not show floating language controls

- Module: language-settings.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public pages do not show floating language controls
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/language-settings.spec.js:75
- Evidence: [browser-results.json#2174ae091f7532347d9f-f0703cc17ce7e26d1a71](browser-results.json)

### WEB-043 — English search, status and personal data stay separate at 390px

- Module: localization-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English search, status and personal data stay separate at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization-regression.spec.js:15
- Evidence: [browser-results.json#2e3f485774437c6a9174-953063d2faa177eb0764](browser-results.json)

### WEB-044 — English search, status and personal data stay separate at 1440px

- Module: localization-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English search, status and personal data stay separate at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization-regression.spec.js:15
- Evidence: [browser-results.json#2e3f485774437c6a9174-af46b9843f05e7dff0f1](browser-results.json)

### WEB-045 — English validation and API errors update when switching languages

- Module: localization-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English validation and API errors update when switching languages
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization-regression.spec.js:92
- Evidence: [browser-results.json#2e3f485774437c6a9174-fa2c823b9d18f55f647a](browser-results.json)

### WEB-046 — Google button locale follows the UI and Google/OTP errors are translated

- Module: localization-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: Google button locale follows the UI and Google/OTP errors are translated
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization-regression.spec.js:129
- Evidence: [browser-results.json#2e3f485774437c6a9174-589dae6dc66fd551261b](browser-results.json)

### WEB-047 — English system notifications preserve names and unknown free text

- Module: localization-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English system notifications preserve names and unknown free text
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization-regression.spec.js:184
- Evidence: [browser-results.json#2e3f485774437c6a9174-5ab8832a296d8e991bcf](browser-results.json)

### WEB-048 — English post saves original Thai data and language switching does not change API records

- Module: localization-regression.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English post saves original Thai data and language switching does not change API records
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization-regression.spec.js:251
- Evidence: [browser-results.json#2e3f485774437c6a9174-1250c6685ed4e267b1bb](browser-results.json)

### WEB-049 — English switch translates authentication, persists locale and preserves draft values

- Module: localization.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English switch translates authentication, persists locale and preserves draft values
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization.spec.js:3
- Evidence: [browser-results.json#01125cb6fe6ee1f06ddc-f6662b74050e7437099b](browser-results.json)

### WEB-050 — English profile, listing and administration retain names and API values

- Module: localization.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English profile, listing and administration retain names and API values
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization.spec.js:30
- Evidence: [browser-results.json#01125cb6fe6ee1f06ddc-401c157766ff9092680e](browser-results.json)

### WEB-051 — English authentication, privacy and report forms fit mobile without runtime errors

- Module: localization.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English authentication, privacy and report forms fit mobile without runtime errors
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/localization.spec.js:75
- Evidence: [browser-results.json#01125cb6fe6ee1f06ddc-d19eea49d27be7fb98d4](browser-results.json)

### WEB-052 — map marker selection replaces desktop details for found, lost and deposit points

- Module: map-selection.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: map marker selection replaces desktop details for found, lost and deposit points
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/map-selection.spec.js:98
- Evidence: [browser-results.json#4439ced05724e4ad0f42-521036cef0e8c394ec6a](browser-results.json)

### WEB-053 — sidebar selection highlights its marker and Escape restores focus without modal trapping

- Module: map-selection.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: sidebar selection highlights its marker and Escape restores focus without modal trapping
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/map-selection.spec.js:164
- Evidence: [browser-results.json#4439ced05724e4ad0f42-db2475d9c30c091b1ba5](browser-results.json)

### WEB-054 — mobile selection uses the same details card, does not cover the dock, and closes on Escape

- Module: map-selection.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: mobile selection uses the same details card, does not cover the dock, and closes on Escape
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/map-selection.spec.js:187
- Evidence: [browser-results.json#4439ced05724e4ad0f42-db1e0e9d1b84fa3b0f49](browser-results.json)

### WEB-055 — keyboard markers support Space, reduced motion and locale changes without translating item data

- Module: map-selection.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: keyboard markers support Space, reduced motion and locale changes without translating item data
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/map-selection.spec.js:252
- Evidence: [browser-results.json#4439ced05724e4ad0f42-ab4c1c7313bbab6fc938](browser-results.json)

### WEB-056 — selecting a marker outside the first five brings its matching sidebar row into view and filtering clears selection

- Module: map-selection.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: selecting a marker outside the first five brings its matching sidebar row into view and filtering clears selection
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/map-selection.spec.js:286
- Evidence: [browser-results.json#4439ced05724e4ad0f42-23544e69dfa99c00690a](browser-results.json)

### WEB-057 — selected details and keyboard-accessible markers pass automated AA checks

- Module: map-selection.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: selected details and keyboard-accessible markers pass automated AA checks
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/map-selection.spec.js:314
- Evidence: [browser-results.json#4439ced05724e4ad0f42-93379c85bf49071681e8](browser-results.json)

### WEB-058 — matching console separates text and image zero scores and queues safe rescanning

- Module: matching.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: matching console separates text and image zero scores and queues safe rescanning
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/matching.spec.js:56
- Evidence: [browser-results.json#44c5b42b8e5e8438523c-e269cf4f49a2a63d3c21](browser-results.json)

### WEB-059 — legacy scores are not presented as image-checked 100 percent matches

- Module: matching.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: legacy scores are not presented as image-checked 100 percent matches
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/matching.spec.js:93
- Evidence: [browser-results.json#44c5b42b8e5e8438523c-5b2ae9a29da96e87d612](browser-results.json)

### WEB-060 — user matching refreshes pending jobs and displays localized evidence without private AI reasons

- Module: matching.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: user matching refreshes pending jobs and displays localized evidence without private AI reasons
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/matching.spec.js:120
- Evidence: [browser-results.json#44c5b42b8e5e8438523c-a1c1e3d06334732f4e84](browser-results.json)

### WEB-061 — staff-confirmed pairs allow a claim without presenting failed visual evidence as ownership proof

- Module: matching.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: staff-confirmed pairs allow a claim without presenting failed visual evidence as ownership proof
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/matching.spec.js:182
- Evidence: [browser-results.json#44c5b42b8e5e8438523c-8d4f987ccbfb9b285ff2](browser-results.json)

### WEB-062 — failed visual analysis is distinct from a completed search with no matches

- Module: matching.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: failed visual analysis is distinct from a completed search with no matches
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/matching.spec.js:226
- Evidence: [browser-results.json#44c5b42b8e5e8438523c-b24c575769eecf99e24e](browser-results.json)

### WEB-063 — desktop rail overlays without moving layout on hover and keyboard focus at 701px

- Module: navbar-quick-filter.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: desktop rail overlays without moving layout on hover and keyboard focus at 701px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/navbar-quick-filter.spec.js:32
- Evidence: [browser-results.json#a28ec709d7112b28597e-c4793db8936e1d42963f](browser-results.json)

### WEB-064 — desktop rail overlays without moving layout on hover and keyboard focus at 1024px

- Module: navbar-quick-filter.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: desktop rail overlays without moving layout on hover and keyboard focus at 1024px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/navbar-quick-filter.spec.js:32
- Evidence: [browser-results.json#a28ec709d7112b28597e-b5a9ead3d84d3844568c](browser-results.json)

### WEB-065 — desktop rail overlays without moving layout on hover and keyboard focus at 1440px

- Module: navbar-quick-filter.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: desktop rail overlays without moving layout on hover and keyboard focus at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/navbar-quick-filter.spec.js:32
- Evidence: [browser-results.json#a28ec709d7112b28597e-cb8462a9d2c44d1d98e3](browser-results.json)

### WEB-066 — desktop rail overlays without moving layout on hover and keyboard focus at 1920px

- Module: navbar-quick-filter.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: desktop rail overlays without moving layout on hover and keyboard focus at 1920px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/navbar-quick-filter.spec.js:32
- Evidence: [browser-results.json#a28ec709d7112b28597e-0e72b8d069cb4a0a0394](browser-results.json)

### WEB-067 — quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 390px

- Module: navbar-quick-filter.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/navbar-quick-filter.spec.js:102
- Evidence: [browser-results.json#a28ec709d7112b28597e-49dcf26d25d4d0467ee8](browser-results.json)

### WEB-068 — quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 1440px

- Module: navbar-quick-filter.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: quick filters apply immediately, retain applied fields, reset pagination and sync advanced filters at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/navbar-quick-filter.spec.js:102
- Evidence: [browser-results.json#a28ec709d7112b28597e-db73c9a1152b4688957e](browser-results.json)

### WEB-069 — quick filter scrollbar has clearance and desktop rail icons remain aligned on hover

- Module: navigation-spacing.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: quick filter scrollbar has clearance and desktop rail icons remain aligned on hover
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/navigation-spacing.spec.js:3
- Evidence: [browser-results.json#2b03eb8e0865c28900a4-76acb5af314498d9d718](browser-results.json)

### WEB-070 — development form opens without repeated full reloads

- Module: posting-dev-smoke.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: development form opens without repeated full reloads
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-dev-smoke.spec.js:3
- Evidence: [browser-results.json#69f33ac625f37a02e028-d42a8ffd59656bf09437](browser-results.json)

### WEB-071 — lost Figma form stays usable at 320px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost Figma form stays usable at 320px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-9c1c174a3d49d9b01ede](browser-results.json)

### WEB-072 — found Figma form stays usable at 320px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found Figma form stays usable at 320px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-aaf7d2c3c60587876a91](browser-results.json)

### WEB-073 — lost Figma form stays usable at 375px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost Figma form stays usable at 375px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-df8f81fc7c04cfa9fe13](browser-results.json)

### WEB-074 — found Figma form stays usable at 375px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found Figma form stays usable at 375px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-b70961f41bb62b2fb6e8](browser-results.json)

### WEB-075 — lost Figma form stays usable at 390px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost Figma form stays usable at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-0eb99fe4769f92343918](browser-results.json)

### WEB-076 — found Figma form stays usable at 390px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found Figma form stays usable at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-142d2ac4104ec750ff12](browser-results.json)

### WEB-077 — lost Figma form stays usable at 700px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost Figma form stays usable at 700px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-b2b0f91d0e9618029928](browser-results.json)

### WEB-078 — found Figma form stays usable at 700px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found Figma form stays usable at 700px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-0881f14c0244a8318d03](browser-results.json)

### WEB-079 — lost Figma form stays usable at 701px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost Figma form stays usable at 701px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-f6aded991d0d6f3df271](browser-results.json)

### WEB-080 — found Figma form stays usable at 701px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found Figma form stays usable at 701px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-49fe45655997d1fff317](browser-results.json)

### WEB-081 — lost Figma form stays usable at 1024px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost Figma form stays usable at 1024px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-1891087273202a154941](browser-results.json)

### WEB-082 — found Figma form stays usable at 1024px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found Figma form stays usable at 1024px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-a9a00c584ed9599a4bda](browser-results.json)

### WEB-083 — lost Figma form stays usable at 1440px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost Figma form stays usable at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-e61b94e115d50561033e](browser-results.json)

### WEB-084 — found Figma form stays usable at 1440px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found Figma form stays usable at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:24
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-b0978ebecb424a82cc5a](browser-results.json)

### WEB-085 — English forms and errors remain accessible at 375px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English forms and errors remain accessible at 375px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:118
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-ef0791f17ae3e64a4835](browser-results.json)

### WEB-086 — English forms and errors remain accessible at 1440px

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English forms and errors remain accessible at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:118
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-f52a97814dca7523a838](browser-results.json)

### WEB-087 — mobile map traps focus, closes with Escape, and resizing preserves the draft

- Module: posting-figma.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: mobile map traps focus, closes with Escape, and resizing preserves the draft
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-figma.spec.js:143
- Evidence: [browser-results.json#28bc029e8f4cbe55ec10-82e752c3338f72019f43](browser-results.json)

### WEB-088 — search has one advanced menu and synchronized quick filters at 390px

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search has one advanced menu and synchronized quick filters at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:40
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-22b6803f4a8040080780](browser-results.json)

### WEB-089 — lost posting matches layout and confirms successful API save at 390px

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost posting matches layout and confirms successful API save at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:76
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-42317b4f19d19d57f602](browser-results.json)

### WEB-090 — found posting matches layout and confirms successful API save at 390px

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found posting matches layout and confirms successful API save at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:76
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-b5ec792a598766e932dd](browser-results.json)

### WEB-091 — search has one advanced menu and synchronized quick filters at 1440px

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search has one advanced menu and synchronized quick filters at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:40
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-a77ce48ec6bccb30b505](browser-results.json)

### WEB-092 — lost posting matches layout and confirms successful API save at 1440px

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: lost posting matches layout and confirms successful API save at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:76
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-6e20bd5e2393a3655d9c](browser-results.json)

### WEB-093 — found posting matches layout and confirms successful API save at 1440px

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: found posting matches layout and confirms successful API save at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:76
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-599adfd38450b16ef8bc](browser-results.json)

### WEB-094 — failed post keeps form input, displays error and never claims success

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: failed post keeps form input, displays error and never claims success
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:131
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-67361c29eb551061f62c](browser-results.json)

### WEB-095 — missing fields and unsupported images show feedback without submitting

- Module: posting-ui.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: missing fields and unsupported images show feedback without submitting
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/posting-ui.spec.js:150
- Evidence: [browser-results.json#8eee0eef0991a8e9022a-151b399191c2d1d4437b](browser-results.json)

### WEB-096 — report choices match responsive geometry and navigate at 320px

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report choices match responsive geometry and navigate at 320px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:27
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-f7690b779865b383e5a9](browser-results.json)

### WEB-097 — report choices match responsive geometry and navigate at 390px

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report choices match responsive geometry and navigate at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:27
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-f2adc5a330e5e7028acf](browser-results.json)

### WEB-098 — report choices match responsive geometry and navigate at 700px

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report choices match responsive geometry and navigate at 700px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:27
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-865a64e52f6b76e8e127](browser-results.json)

### WEB-099 — report choices match responsive geometry and navigate at 701px

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report choices match responsive geometry and navigate at 701px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:27
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-7f2b347a27131b5fd56a](browser-results.json)

### WEB-100 — report choices match responsive geometry and navigate at 1024px

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report choices match responsive geometry and navigate at 1024px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:27
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-82d6c808c148b7e5a1fe](browser-results.json)

### WEB-101 — report choices match responsive geometry and navigate at 1440px

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: report choices match responsive geometry and navigate at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:27
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-a92f8e4134bf6e759355](browser-results.json)

### WEB-102 — keyboard, backdrop, repeated opening, scroll lock and short screens work

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: keyboard, backdrop, repeated opening, scroll lock and short screens work
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:128
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-b88a11052d12d44f4493](browser-results.json)

### WEB-103 — English and high contrast variants remain usable with reduced motion

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: English and high contrast variants remain usable with reduced motion
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:168
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-fa009fd10a0ad2c446b8](browser-results.json)

### WEB-104 — record the original Figma palette contrast limitation without hiding violations

- Module: report-choice.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: record the original Figma palette contrast limitation without hiding violations
- Actual: Error: [2mexpect([22m[31mreceived[39m[2m).[22mtoBeCloseTo[2m([22m[32mexpected[39m[2m, [22mprecision[2m)[22m

Expected: [32m2.62[39m
Received: [31m6.232268509031551[39m

Expected precision:    1
Expected difference: < [32m0.05[39m
Received difference:   [31m3.6122685090315505[39m

  250 |       });
  251 |     });
> 252 |   expect(palette[0].contrast).toBeCloseTo(2.62, 1);
      |                               ^
  253 |   expect(palette[1].contrast).toBeCloseTo(3.47, 1);
  254 |   await info.attach("default-palette-calculated-contrast", {
  255 |     body: JSON.stringify(palette, null, 2),
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\report-choice.spec.js:252:31
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-04
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/report-choice.spec.js:208
- Evidence: [browser-results.json#0ff332f0a0ac0b52ea8d-df5df6b383ef98792b78](browser-results.json)

### WEB-105 — system notifications appear in the notification list and can be marked read

- Module: system-notifications.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: system notifications appear in the notification list and can be marked read
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/system-notifications.spec.js:3
- Evidence: [browser-results.json#07efc960020b6cfd66d8-9938c2e402758d7aa968](browser-results.json)

### WEB-106 — public layouts fit narrow mobile and tablet

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: public layouts fit narrow mobile and tablet
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:26
- Evidence: [browser-results.json#d8cd524334d792f16653-5942ec8b7ef323218852](browser-results.json)

### WEB-107 — pressed state is visible without layout shift and disabled actions remain disabled

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: pressed state is visible without layout shift and disabled actions remain disabled
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:84:3
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:80
- Evidence: [browser-results.json#d8cd524334d792f16653-291e3a6e5291c93e1cbe](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-291e3a6e5291c93e1cbe

### WEB-108 — confirmation fits short screens, traps focus and restores the trigger

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: confirmation fits short screens, traps focus and restores the trigger
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:110:3
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:106
- Evidence: [browser-results.json#d8cd524334d792f16653-a06b3618bcdf35a98ce7](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-a06b3618bcdf35a98ce7

### WEB-109 — admin modal stays inside a short screen and closes without saving

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: admin modal stays inside a short screen and closes without saving
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:139:3
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:138
- Evidence: [browser-results.json#d8cd524334d792f16653-e116f9c1e1a10fed62bb](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-e116f9c1e1a10fed62bb

### WEB-110 — admin table text and map controls retain usable proportions

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: admin table text and map controls retain usable proportions
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:160:3
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:156
- Evidence: [browser-results.json#d8cd524334d792f16653-0ae65e2ce04e869d2fdb](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-0ae65e2ce04e869d2fdb

### WEB-111 — all application layouts at 320px

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: all application layouts at 320px
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:186:5
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:181
- Evidence: [browser-results.json#d8cd524334d792f16653-a9104231d5ef796b9bc7](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-a9104231d5ef796b9bc7

### WEB-112 — all application layouts at 390px

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: all application layouts at 390px
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:186:5
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:181
- Evidence: [browser-results.json#d8cd524334d792f16653-935af935188ab95f7595](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-935af935188ab95f7595

### WEB-113 — all application layouts at 768px

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: all application layouts at 768px
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:186:5
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:181
- Evidence: [browser-results.json#d8cd524334d792f16653-954be6aa12855ce48700](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-954be6aa12855ce48700

### WEB-114 — all application layouts at 1440px

- Module: ui-consistency.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: all application layouts at 1440px
- Actual: SyntaxError: Unexpected token 'T', "Too many r"... is not valid JSON

  59 |     await request.get("http://127.0.0.1:4181/__fixture/session")
  60 |   ).json();
> 61 |   const admin = await (
     |                 ^
  62 |     await request.post("http://127.0.0.1:4181/api/admin/login", {
  63 |       data: { username: "e2e-admin", password: "test-password-only" },
  64 |     })
    at session (C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:61:17)
    at C:\IT_PROJECT_GitHub\FOUNDLOST\test\e2e\ui-consistency.spec.js:186:5
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-TEST-05
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-consistency.spec.js:181
- Evidence: [browser-results.json#d8cd524334d792f16653-5d3402937c1cd51cc254](browser-results.json)
- Diagnostic rerun: PASS (no app changes); rerun-results.json#d8cd524334d792f16653-5d3402937c1cd51cc254

### WEB-115 — search controls, cards and dock stay balanced at 320px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search controls, cards and dock stay balanced at 320px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:35
- Evidence: [browser-results.json#a303da26727784904ca4-bd7e5f4082a6e3fe8eeb](browser-results.json)

### WEB-116 — settings language and photo controls have consistent sizes at 320px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: settings language and photo controls have consistent sizes at 320px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:138
- Evidence: [browser-results.json#a303da26727784904ca4-378b3037e46053241c87](browser-results.json)

### WEB-117 — search controls, cards and dock stay balanced at 390px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search controls, cards and dock stay balanced at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:35
- Evidence: [browser-results.json#a303da26727784904ca4-71dc7ae1e0ac9db79606](browser-results.json)

### WEB-118 — settings language and photo controls have consistent sizes at 390px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: settings language and photo controls have consistent sizes at 390px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:138
- Evidence: [browser-results.json#a303da26727784904ca4-e34b0b3db3d3557a55e3](browser-results.json)

### WEB-119 — search controls, cards and dock stay balanced at 768px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search controls, cards and dock stay balanced at 768px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:35
- Evidence: [browser-results.json#a303da26727784904ca4-b4d2e7fa4dbd6041a22b](browser-results.json)

### WEB-120 — settings language and photo controls have consistent sizes at 768px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: settings language and photo controls have consistent sizes at 768px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:138
- Evidence: [browser-results.json#a303da26727784904ca4-ed1645b2f04fcea16bce](browser-results.json)

### WEB-121 — search controls, cards and dock stay balanced at 1440px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: search controls, cards and dock stay balanced at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:35
- Evidence: [browser-results.json#a303da26727784904ca4-a7b8b50936c0a6e36f9e](browser-results.json)

### WEB-122 — settings language and photo controls have consistent sizes at 1440px

- Module: ui-polish.spec.js
- Preconditions: Edge Chromium + Vite 4173 + Express 4181 with synthetic PGlite fixture; workers=1; original timeout; live Google/SMTP replaced by explicit test doubles
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic fixtures only; exact boundary/input values are in the referenced test body
- Expected: settings language and photo controls have consistent sizes at 1440px
- Actual: All browser assertions passed
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:/IT_PROJECT_GitHub/FOUNDLOST/test/e2e/ui-polish.spec.js:138
- Evidence: [browser-results.json#a303da26727784904ca4-babe34302ad52da280c0](browser-results.json)

### ROLE-001 — guest GET /api/admin/manage/operations

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-001](role-results.json)

### ROLE-002 — student GET /api/admin/manage/operations

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-002](role-results.json)

### ROLE-003 — guest GET /api/admin/manage/staff-notifications

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-003](role-results.json)

### ROLE-004 — student GET /api/admin/manage/staff-notifications

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-004](role-results.json)

### ROLE-005 — guest GET /api/admin/manage/privacy-requests

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-005](role-results.json)

### ROLE-006 — student GET /api/admin/manage/privacy-requests

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-006](role-results.json)

### ROLE-007 — guest PATCH /api/admin/manage/privacy-requests/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-007](role-results.json)

### ROLE-008 — student PATCH /api/admin/manage/privacy-requests/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-008](role-results.json)

### ROLE-009 — guest GET /api/admin/manage/settings

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-009](role-results.json)

### ROLE-010 — student GET /api/admin/manage/settings

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-010](role-results.json)

### ROLE-011 — guest PUT /api/admin/manage/settings

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-011](role-results.json)

### ROLE-012 — student PUT /api/admin/manage/settings

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-012](role-results.json)

### ROLE-013 — guest POST /api/admin/manage/retention/run

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-013](role-results.json)

### ROLE-014 — student POST /api/admin/manage/retention/run

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-014](role-results.json)

### ROLE-015 — guest GET /api/admin/manage/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-015](role-results.json)

### ROLE-016 — student GET /api/admin/manage/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-016](role-results.json)

### ROLE-017 — guest POST /api/admin/manage/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-017](role-results.json)

### ROLE-018 — student POST /api/admin/manage/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-018](role-results.json)

### ROLE-019 — guest PUT /api/admin/manage/points/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-019](role-results.json)

### ROLE-020 — student PUT /api/admin/manage/points/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-020](role-results.json)

### ROLE-021 — guest GET /api/admin/manage/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-021](role-results.json)

### ROLE-022 — student GET /api/admin/manage/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-022](role-results.json)

### ROLE-023 — guest POST /api/admin/manage/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-023](role-results.json)

### ROLE-024 — student POST /api/admin/manage/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-024](role-results.json)

### ROLE-025 — guest PUT /api/admin/manage/users/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-025](role-results.json)

### ROLE-026 — student PUT /api/admin/manage/users/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-026](role-results.json)

### ROLE-027 — guest GET /api/admin/manage/items/found

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-027](role-results.json)

### ROLE-028 — student GET /api/admin/manage/items/found

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-028](role-results.json)

### ROLE-029 — guest PATCH /api/admin/manage/items/found/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-029](role-results.json)

### ROLE-030 — student PATCH /api/admin/manage/items/found/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-030](role-results.json)

### ROLE-031 — guest GET /api/admin/manage/audit

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-031](role-results.json)

### ROLE-032 — student GET /api/admin/manage/audit

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-032](role-results.json)

### ROLE-033 — guest GET /api/admin/manage/matches

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-033](role-results.json)

### ROLE-034 — student GET /api/admin/manage/matches

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-034](role-results.json)

### ROLE-035 — guest PATCH /api/admin/manage/matches/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-035](role-results.json)

### ROLE-036 — student PATCH /api/admin/manage/matches/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-036](role-results.json)

### ROLE-037 — guest POST /api/admin/manage/matches/rescan

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-037](role-results.json)

### ROLE-038 — student POST /api/admin/manage/matches/rescan

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-038](role-results.json)

### ROLE-039 — guest GET /api/admin/manage/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-039](role-results.json)

### ROLE-040 — student GET /api/admin/manage/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-040](role-results.json)

### ROLE-041 — guest GET /api/admin/manage/claims/history

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-041](role-results.json)

### ROLE-042 — student GET /api/admin/manage/claims/history

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-042](role-results.json)

### ROLE-043 — guest PATCH /api/admin/manage/claims/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-043](role-results.json)

### ROLE-044 — student PATCH /api/admin/manage/claims/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-044](role-results.json)

### ROLE-045 — guest GET /api/admin/manage/tickets

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-045](role-results.json)

### ROLE-046 — student GET /api/admin/manage/tickets

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-046](role-results.json)

### ROLE-047 — guest POST /api/admin/manage/tickets

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-047](role-results.json)

### ROLE-048 — student POST /api/admin/manage/tickets

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-048](role-results.json)

### ROLE-049 — guest PATCH /api/admin/manage/tickets/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-049](role-results.json)

### ROLE-050 — student PATCH /api/admin/manage/tickets/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-050](role-results.json)

### ROLE-051 — guest GET /api/admin/manage/errors

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-051](role-results.json)

### ROLE-052 — student GET /api/admin/manage/errors

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-052](role-results.json)

### ROLE-053 — guest GET /api/admin/manage/statistics

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-053](role-results.json)

### ROLE-054 — student GET /api/admin/manage/statistics

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-054](role-results.json)

### ROLE-055 — guest GET /api/admin/manage/export

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-055](role-results.json)

### ROLE-056 — student GET /api/admin/manage/export

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-056](role-results.json)

### ROLE-057 — guest GET /api/admin/manage/export/pdf

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-057](role-results.json)

### ROLE-058 — student GET /api/admin/manage/export/pdf

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-058](role-results.json)

### ROLE-059 — staff GET /api/admin/manage/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-059](role-results.json)

### ROLE-060 — super-admin GET /api/admin/manage/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-060](role-results.json)

### ROLE-061 — staff GET /api/admin/manage/items/lost

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-061](role-results.json)

### ROLE-062 — super-admin GET /api/admin/manage/items/lost

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-062](role-results.json)

### ROLE-063 — staff GET /api/admin/manage/items/found

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-063](role-results.json)

### ROLE-064 — super-admin GET /api/admin/manage/items/found

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-064](role-results.json)

### ROLE-065 — staff GET /api/admin/manage/matches

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-065](role-results.json)

### ROLE-066 — super-admin GET /api/admin/manage/matches

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-066](role-results.json)

### ROLE-067 — staff GET /api/admin/manage/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-067](role-results.json)

### ROLE-068 — super-admin GET /api/admin/manage/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-068](role-results.json)

### ROLE-069 — staff GET /api/admin/manage/claims/history

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-069](role-results.json)

### ROLE-070 — super-admin GET /api/admin/manage/claims/history

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-070](role-results.json)

### ROLE-071 — staff GET /api/admin/manage/tickets

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-071](role-results.json)

### ROLE-072 — super-admin GET /api/admin/manage/tickets

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-072](role-results.json)

### ROLE-073 — staff GET /api/admin/manage/statistics

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-073](role-results.json)

### ROLE-074 — super-admin GET /api/admin/manage/statistics

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-074](role-results.json)

### ROLE-075 — staff GET /api/admin/manage/staff-notifications

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-075](role-results.json)

### ROLE-076 — super-admin GET /api/admin/manage/staff-notifications

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-076](role-results.json)

### ROLE-077 — staff GET /api/admin/manage/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-077](role-results.json)

### ROLE-078 — super-admin GET /api/admin/manage/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-078](role-results.json)

### ROLE-079 — staff GET /api/admin/manage/operations

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-079](role-results.json)

### ROLE-080 — super-admin GET /api/admin/manage/operations

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-080](role-results.json)

### ROLE-081 — staff GET /api/admin/manage/privacy-requests

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-081](role-results.json)

### ROLE-082 — super-admin GET /api/admin/manage/privacy-requests

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-082](role-results.json)

### ROLE-083 — staff POST /api/admin/manage/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-083](role-results.json)

### ROLE-084 — staff PUT /api/admin/manage/users/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-084](role-results.json)

### ROLE-085 — staff POST /api/admin/manage/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-085](role-results.json)

### ROLE-086 — staff PUT /api/admin/manage/points/999999

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-086](role-results.json)

### ROLE-087 — staff PUT /api/admin/manage/settings

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-087](role-results.json)

### ROLE-088 — staff GET /api/admin/users

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 403
- Actual: 403
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-088](role-results.json)

### ROLE-089 — guest GET /api/me/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-089](role-results.json)

### ROLE-090 — student GET /api/me/points

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-090](role-results.json)

### ROLE-091 — guest GET /api/me/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-091](role-results.json)

### ROLE-092 — student GET /api/me/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-092](role-results.json)

### ROLE-093 — guest GET /api/me/notifications

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-093](role-results.json)

### ROLE-094 — student GET /api/me/notifications

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-094](role-results.json)

### ROLE-095 — guest GET /api/me/privacy/requests

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-095](role-results.json)

### ROLE-096 — student GET /api/me/privacy/requests

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-096](role-results.json)

### ROLE-097 — student POST /api/me/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 201
- Actual: 201
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-097](role-results.json)

### ROLE-098 — staff PATCH /api/admin/manage/claims/1

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 400
- Actual: 400
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-098](role-results.json)

### ROLE-099 — staff PATCH /api/admin/manage/claims/1

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-099](role-results.json)

### ROLE-100 — staff PATCH /api/admin/manage/claims/1

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 400
- Actual: 400
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-100](role-results.json)

### ROLE-101 — staff PATCH /api/admin/manage/claims/1

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 200
- Actual: 200
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-101](role-results.json)

### ROLE-102 — staff DB assertion handover persisted states

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: returned/returned
- Actual: returned/returned
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-102](role-results.json)

### ROLE-103 — staff PATCH /api/admin/manage/claims/1

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 409
- Actual: 409
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-103](role-results.json)

### ROLE-104 — inactive-staff GET /api/admin/manage/claims

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-104](role-results.json)

### ROLE-105 — inactive-student GET /api/me/profile

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-105](role-results.json)

### ROLE-106 — invalid-token GET /api/admin/profile

- Module: Role/API matrix
- Preconditions: Fresh isolated real PostgreSQL; guest/student/Staff/Super Admin synthetic accounts; no production data
- Steps: Create synthetic sessions; issue the specified method/endpoint as the specified role; verify status or persisted handover state
- Test data: qa-student/qa-finder/qa-staff; synthetic hidden scratch; no actual identity information
- Expected: 401
- Actual: 401
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\role-matrix.cjs
- Evidence: [role-results.json#ROLE-106](role-results.json)

### OP-01 — Database connection and core tables

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: All core tables readable
- Actual: {"counts":{"users":61,"lost":7,"found":8,"points":132},"version":"16.10 (Debian 16.10-1.pgdg13+1)"}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-01](runtime-final.json)

### OP-02 — Required fields and duplicate identity

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: 0 blank identity fields and 0 duplicate emails/IDs
- Actual: {"blanks":0,"duplicate_email":0,"duplicate_id":0}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-02](runtime-final.json)

### OP-03 — Lost/found and match relationships

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: 0 orphaned reports or matching pairs
- Actual: {"code":"ERR_ASSERTION","message":"The expression evaluated to a falsy value:\n\n  assert.ok(Object.values(row).every(n=>n===0))\n"}
- Initial status: FAIL; Severity/Priority: High/P1; Bug ID: QA-DATA-01
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-03](runtime-final.json)

### OP-04 — Role availability

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: Active staff and admin available; report only aggregate counts
- Actual: {"roles":[{"role":"staff","is_active":true,"n":1},{"role":"student","is_active":true,"n":60}],"admin":1}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-04](runtime-final.json)

### OP-05 — Database FK/unique/primary constraints

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: Constraints present
- Actual: [{"contype":"c","n":17},{"contype":"f","n":16},{"contype":"p","n":22},{"contype":"u","n":10}]
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-05](runtime-final.json)

### OP-06 — Original uploaded image files

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: Every referenced local image exists
- Actual: {"code":"ERR_ASSERTION","message":"Referenced images missing: 2\n\n2 !== 0\n"}
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-DATA-02
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-06](runtime-final.json)

### OP-07 — Encryption key availability

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: Key loads with correct size; no bytes disclosed
- Actual: {"keyValid":true}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-07](runtime-final.json)

### OP-08 — GET /health

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 200
- Actual: {"http":200}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-08](runtime-final.json)

### OP-09 — GET /api/me/profile

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 401
- Actual: {"http":401}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-09](runtime-final.json)

### OP-10 — GET /api/admin/profile

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 401
- Actual: {"http":401}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-10](runtime-final.json)

### OP-11 — GET /api/admin/manage/users

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 401
- Actual: {"http":401}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-11](runtime-final.json)

### OP-12 — GET /matching/all

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 401
- Actual: {"http":401}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-12](runtime-final.json)

### OP-13 — GET /assets/blocked.html

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 404
- Actual: {"http":404}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-13](runtime-final.json)

### OP-14 — GET /api/privacy-policy

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 200
- Actual: {"http":200}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-14](runtime-final.json)

### OP-15 — Google public configuration

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: Configured exact KU domain; no ID exported
- Actual: {"http":200,"enabled":true,"hostedDomain":"ku.th"}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-15](runtime-final.json)

### OP-16 — Security response headers

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: No framework version; nosniff, CSP and cache protections
- Actual: {"frameworkHidden":true,"nosniff":true,"csp":true,"noStore":true}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-16](runtime-final.json)

### OP-17 — Bounded health performance

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: 20 successful responses within a generous 2s local basic-check bound
- Actual: {"scope":"20 sequential local SELECT-backed health requests only, not load/AI/production SLA","requests":20,"p50_ms":6,"p95_ms":8}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-17](runtime-final.json)

### OP-18 — Source data counts preserved

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: Before/after counts identical
- Actual: {"unchanged":true}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-18](runtime-final.json)

### OP-19 — Disallowed CORS origin error classification

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: Untrusted origin rejected with a controlled 4xx, not server failure
- Actual: {"code":"ERR_ASSERTION","message":"The expression evaluated to a falsy value:\n\n  assert.ok(r.status>=400&&r.status<500)\n"}
- Initial status: FAIL; Severity/Priority: Medium/P2; Bug ID: QA-API-01
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-19](runtime-final.json)

### OP-20 — Malformed JSON error handling

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 400 and service remains healthy
- Actual: {"malformed":400,"health":200}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-20](runtime-final.json)

### OP-21 — Oversized JSON request rejected

- Module: Selected local runtime/database
- Preconditions: Local foundlost_db port 5434; database transaction READ ONLY; temporary API listener without scheduler
- Steps: Run bounded read-only metadata/HTTP assertion from inspect-runtime.cjs
- Test data: Aggregate counts / existing local paths / unauthenticated requests only; no real identities exported
- Expected: HTTP 413 before authentication/database changes
- Actual: {"http":413}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\inspect-runtime.cjs
- Evidence: [runtime-final.json#OP-21](runtime-final.json)

### PG-OP-01 — Full startup, schema checks and /health succeed

- Module: Full startup / real PostgreSQL persistence
- Preconditions: Fresh temporary PostgreSQL database; NODE_ENV=test; scheduler and outbound delivery disabled
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic administrator and qa-persist records only
- Expected: Full startup, schema checks and /health succeed
- Actual: [object Object]
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\startup-postgres.cjs
- Evidence: [startup-results.json#PG-OP-01](startup-results.json)

### PG-OP-02 — Super Admin authenticates and invalid credentials fail

- Module: Full startup / real PostgreSQL persistence
- Preconditions: Fresh temporary PostgreSQL database; NODE_ENV=test; scheduler and outbound delivery disabled
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic administrator and qa-persist records only
- Expected: Super Admin authenticates and invalid credentials fail
- Actual: [object Object]
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\startup-postgres.cjs
- Evidence: [startup-results.json#PG-OP-02](startup-results.json)

### PG-OP-03 — CRUD persists across separate database connections

- Module: Full startup / real PostgreSQL persistence
- Preconditions: Fresh temporary PostgreSQL database; NODE_ENV=test; scheduler and outbound delivery disabled
- Steps: Execute the referenced automated test and inspect its assertions; do not change expectations
- Test data: Synthetic administrator and qa-persist records only
- Expected: CRUD persists across separate database connections
- Actual: [object Object]
- Initial status: PASS; Severity/Priority: High/P1; Bug ID: none
- Source: C:\IT_PROJECT\output\qa-20261021\startup-postgres.cjs
- Evidence: [startup-results.json#PG-OP-03](startup-results.json)

### QA-01 — Source lint

- Module: Static/build/dependency checks
- Preconditions: Source working tree unchanged; local test dependencies available
- Steps: C:\WINDOWS\system32\cmd.exe /d /s /c npm run lint
- Test data: Current source and dependency locks; no package updates
- Expected: Command succeeds
- Actual: exit 0
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [lint.log](lint.log)

### QA-02 — Production build

- Module: Static/build/dependency checks
- Preconditions: Source working tree unchanged; local test dependencies available
- Steps: C:\Program Files\nodejs\node.exe node_modules/vite/bin/vite.js build
- Test data: Current source and dependency locks; no package updates
- Expected: Command succeeds
- Actual: exit 0; existing main bundle >500kB warning remains
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [build.log](build.log)

### QA-03 — UI dictionary completeness

- Module: Static/build/dependency checks
- Preconditions: Source working tree unchanged; local test dependencies available
- Steps: C:\Program Files\nodejs\node.exe tools/extract-ui-strings.mjs --check
- Test data: Current source and dependency locks; no package updates
- Expected: Command succeeds
- Actual: {
  "total": 650,
  "missing": []
}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [i18n.log](i18n.log)

### QA-04 — Frontend dependency audit

- Module: Static/build/dependency checks
- Preconditions: Source working tree unchanged; local test dependencies available
- Steps: C:\WINDOWS\system32\cmd.exe /d /s /c npm audit --json
- Test data: Current source and dependency locks; no package updates
- Expected: No reported dependency vulnerabilities
- Actual: {"info":0,"low":0,"moderate":0,"high":2,"critical":0,"total":2}
- Initial status: FAIL; Severity/Priority: High/P1; Bug ID: QA-SEC-01
- Source: see evidence
- Evidence: [audit.log](audit.log)

### QA-05 — Backend dependency audit

- Module: Static/build/dependency checks
- Preconditions: Source working tree unchanged; local test dependencies available
- Steps: C:\WINDOWS\system32\cmd.exe /d /s /c npm --prefix backend audit --json
- Test data: Current source and dependency locks; no package updates
- Expected: No reported dependency vulnerabilities
- Actual: {"info":0,"low":0,"moderate":0,"high":0,"critical":0,"total":0}
- Initial status: PASS; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [audit-backend.log](audit-backend.log)

### EXT-01 — Real KU Google account login

- Module: External/manual acceptance
- Preconditions: No authorised human Google session/account supplied; verifier/browser tests are explicit doubles
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: Real KU Google account login
- Actual: No authorised human Google session/account supplied; verifier/browser tests are explicit doubles
- Initial status: BLOCKED; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)

### EXT-02 — SMTP/push delivery to a real recipient

- Module: External/manual acceptance
- Preconditions: No approved real recipient/provider confirmation; no messages sent
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: SMTP/push delivery to a real recipient
- Actual: No approved real recipient/provider confirmation; no messages sent
- Initial status: BLOCKED; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)

### EXT-03 — Production TLS and release readiness

- Module: External/manual acceptance
- Preconditions: Production deployment/certificate not selected; privacy approval flag is not set in inspected local environment
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: Production TLS and release readiness
- Actual: Production deployment/certificate not selected; privacy approval flag is not set in inspected local environment
- Initial status: BLOCKED; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)

### EXT-04 — AI precision/recall on labelled KU dataset

- Module: External/manual acceptance
- Preconditions: No labelled held-out dataset/model cache for real inference in this checkout; synthetic logic is not accuracy proof
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: AI precision/recall on labelled KU dataset
- Actual: No labelled held-out dataset/model cache for real inference in this checkout; synthetic logic is not accuracy proof
- Initial status: BLOCKED; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)

### EXT-05 — 500-user end-to-end load and soak on deployment

- Module: External/manual acceptance
- Preconditions: Only 20 bounded local health/SELECT requests measured; no production load permission/environment agreed
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: 500-user end-to-end load and soak on deployment
- Actual: Only 20 bounded local health/SELECT requests measured; no production load permission/environment agreed
- Initial status: NOT RUN; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)

### EXT-06 — 99% availability over a Bangkok calendar month

- Module: External/manual acceptance
- Preconditions: Requires a full external monitoring period; cannot infer uptime from a point-in-time check
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: 99% availability over a Bangkok calendar month
- Actual: Requires a full external monitoring period; cannot infer uptime from a point-in-time check
- Initial status: NOT RUN; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)

### EXT-07 — Manual screen-reader and zoom certification of every state

- Module: External/manual acceptance
- Preconditions: Automated AA/keyboard checks run; dedicated assistive-technology audit not performed
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: Manual screen-reader and zoom certification of every state
- Actual: Automated AA/keyboard checks run; dedicated assistive-technology audit not performed
- Initial status: NOT RUN; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)

### EXT-08 — Pixel-perfect Figma comparison for every screen/state

- Module: External/manual acceptance
- Preconditions: No newly verified Figma design context/reference mapping in this QA run; screenshots/responsive checks do not establish exact equivalence
- Steps: Obtain missing prerequisite and execute dedicated acceptance test
- Test data: Not used
- Expected: Pixel-perfect Figma comparison for every screen/state
- Actual: No newly verified Figma design context/reference mapping in this QA run; screenshots/responsive checks do not establish exact equivalence
- Initial status: BLOCKED; Severity/Priority: Medium/P2; Bug ID: none
- Source: see evidence
- Evidence: [TEST_PLAN.md](TEST_PLAN.md)
