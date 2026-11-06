# GlobalTech World Computer Institute
## Cybersecurity Department
### CEH Practical Examination — Web Application Hacking · Repository README

## Candidate declaration

> I confirm that this practical examination is my own work. I carried out all testing ethically and lawfully, only against the authorised tc-corp-server lab VM in an isolated laboratory, and at no point accessed, scanned or attacked any system I do not own or am not authorised to test.

## Candidate details

| | |
|---|---|
| Full name | Elizabeth Oluwatolani Peter Odubiyi |
| Student ID / cohort | Cybersecurity2026 |
| Date submitted | 6 November 2026 |
| Tasks answered | Task 1 (SQL Injection) and Task 2 (HTTP Interception & Traffic Analysis) |

## Lab environment

- Attacker: Kali Linux (IP: `10.10.1.6`)
- Target server: tc-corp-server — TechCapacity vulnerable lab VM (IP: `10.10.1.246`) — isolated / host-only, no internet exposure
- Apps on the target: OWASP Mutillidae II (Task 1), DVWA (Task 2)
- Tools used: Firefox, Burp Suite Community Edition (intercepting proxy, manual SQL injection testing)

## Contents

- [`task-1-sql-injection/report.md`](task-1-sql-injection/report.md) — SQL injection, authentication bypass against OWASP Mutillidae II
- [`task-2-traffic-analysis/report.md`](task-2-traffic-analysis/report.md) — HTTP interception & traffic analysis of DVWA via Burp Suite

## How to read this submission

Each task has its own folder with a report write-up and a screenshots folder. Every screenshot has a short caption explaining what it shows. Payloads and captured requests are listed in the order they were tried/captured.

---
Submitted for assessment — GlobalTech World Computer Institute, Cybersecurity Department.
