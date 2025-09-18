# OWASP Top 10 Checklist – Task 1 (Juice Shop)

| OWASP Top 10 Category              | Vulnerability Found? | Notes |
|-----------------------------------|----------------------|-------|
| A01: Broken Access Control        | ❌                  | Not tested in this task |
| A02: Cryptographic Failures       | ❌                  | Not tested |
| A03: Injection (SQL Injection)    | ✅                  | Login bypass confirmed |
| A04: Insecure Design              | ⚠️                  | Poor validation of inputs |
| A05: Security Misconfiguration    | ✅                  | Findings in ZAP scan |
| A06: Vulnerable & Outdated Components | ❌              | Not tested |
| A07: Identification & Authentication Failures | ✅      | Weak login handling (via SQLi) |
| A08: Software & Data Integrity Failures | ❌           | Not tested |
| A09: Security Logging & Monitoring Failures | ⚠️       | No logs visible during testing |
| A10: Server-Side Request Forgery (SSRF) | ❌           | Not tested |
