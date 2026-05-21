# Event ID 4625 — Failed Logon

## Description
An account failed to log on.

---

## Why It Matters
Important for detecting:
- brute-force attacks
- password spraying
- credential stuffing
- unauthorized access attempts

---

## Key Fields
- Account Name
- Source IP
- Logon Type
- Failure Reason
- Workstation Name

---

## SOC Investigation Questions
- Were multiple accounts targeted?
- Was the source IP internal or external?
- Were failures followed by successful login?
- Is the account privileged?

---

## Detection Ideas
- Multiple failed logins from same IP
- Multiple usernames targeted
- Failed login spike
- Geographic anomalies

---

## MITRE ATT&CK Mapping
- T1110 — Brute Force

---

## Severity
Medium → High depending on frequency and target.

---

## Notes
(Add your own learning notes here.)
