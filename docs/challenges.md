Challenges | crAPI
==================

crAPI covers the [OWASP API Security Top 10 2019][t10] and includes few other
common attacks.

The table below provides some guidance on what you should focus to find and
exploit the existing vulnerabilities.

| Category                                                            | Level  | Challenge                                    |
|:--------------------------------------------------------------------|:-------|:---------------------------------------------|
| Security Misconfiguration                                           | Easy   | Data flow                                    |
| Broken Object Level Authentication                                  | Easy   | Contact mechanic form                        |
| Excessive Data Exposure                                             | Easy   | Change video                                 |
| Mass Assignment                                                     | Easy   | Change video name                            |
| Broken Object Level Authentication                                  | Medium | Get car location                             |
| Broken Authentication,<br/> Lack of Resource & Rate Limiting        | Medium | Forgot Password                              |
| Excessive Data Exposure                                             | Medium | Community posts                              |
| Lack of Resource & Rate Limiting                                    | Medium | Contact mechanic                             |
| Broken Function Level Authorization                                 | Medium | Profile Video                                |
| Server Side Request Forgery                                         | Medium | Contact mechanic                             |
| Injection & Mass Assignment                                         | Medium | Apply coupon                                 |
| Mass Assignment                                                     | Medium | Return item                                  |
| Broken Object Level Authentication,<br/> Improper Assets Management | Hard   | Change email address - Full account takeover |
| Remote Code Execution                                               | Hard   | Share video                                  |

[t10]: https://raw.githubusercontent.com/OWASP/API-Security/master/2019/en/dist/owasp-api-security-top-10.pdf