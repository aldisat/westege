# westege

# WSTG Automation Matrix

Legend: **Automatable** = bisa full pipeline | **Semi-manual** = tools nemu kandidat, verify manual | **Manual** = butuh analisis/logic manual

| No | Kode WSTG | Test | Kategori |
|---|---|---|---|
| 1 | WSTG-INFO-01 | Conduct Search Engine Discovery Reconnaissance for Information Leakage | Semi-manual |
| 2 | WSTG-INFO-02 | Fingerprint Web Server | Automatable |
| 3 | WSTG-INFO-03 | Review Webserver Metafiles for Information Leakage | Automatable |
| 4 | WSTG-INFO-04 | Enumerate Applications on Webserver | Automatable |
| 5 | WSTG-INFO-05 | Review Web Page Content for Information Leakage | Automatable |
| 6 | WSTG-INFO-06 | Identify Application Entry Points | Automatable |
| 7 | WSTG-INFO-07 | Map Execution Paths Through Application | Semi-manual |
| 8 | WSTG-INFO-08 | Fingerprint Web Application Framework | Automatable |
| 9 | WSTG-INFO-09 | Fingerprint Web Application | Automatable |
| 10 | WSTG-INFO-10 | Map Application Architecture | Manual |
| 11 | WSTG-CONF-01 | Test Network Infrastructure Configuration | Automatable |
| 12 | WSTG-CONF-02 | Test Application Platform Configuration | Automatable |
| 13 | WSTG-CONF-03 | Test File Extensions Handling for Sensitive Information | Automatable |
| 14 | WSTG-CONF-04 | Review Old Backup and Unreferenced Files for Sensitive Information | Automatable |
| 15 | WSTG-CONF-05 | Enumerate Infrastructure and Application Admin Interfaces | Automatable |
| 16 | WSTG-CONF-06 | Test HTTP Methods | Automatable |
| 17 | WSTG-CONF-07 | Test HTTP Strict Transport Security | Automatable |
| 18 | WSTG-CONF-08 | Test RIA Cross Domain Policy | Automatable |
| 19 | WSTG-CONF-09 | Test File Permission | Manual |
| 20 | WSTG-CONF-10 | Test for Subdomain Takeover | Automatable |
| 21 | WSTG-CONF-11 | Test Cloud Storage | Automatable |
| 22 | WSTG-CONF-12 | Testing for Content Security Policy | Automatable |
| 23 | WSTG-CONF-13 | Test Path Confusion | Semi-manual |
| 24 | WSTG-CONF-14 | Test Other HTTP Security Header Misconfigurations | Automatable |
| 25 | WSTG-IDNT-01 | Test Role Definitions | Manual |
| 26 | WSTG-IDNT-02 | Test User Registration Process | Manual |
| 27 | WSTG-IDNT-03 | Test Account Provisioning Process | Manual |
| 28 | WSTG-IDNT-04 | Testing for Account Enumeration and Guessable User Account | Semi-manual |
| 29 | WSTG-IDNT-05 | Testing for Weak or Unenforced Username Policy | Semi-manual |
| 30 | WSTG-ATHN-01 | Testing for Credentials Transported over an Encrypted Channel | Automatable |
| 31 | WSTG-ATHN-02 | Testing for Default Credentials | Automatable |
| 32 | WSTG-ATHN-03 | Testing for Weak Lock Out Mechanism | Semi-manual |
| 33 | WSTG-ATHN-04 | Testing for Bypassing Authentication Schema | Semi-manual |
| 34 | WSTG-ATHN-05 | Testing for Vulnerable Remember Password | Manual |
| 35 | WSTG-ATHN-06 | Testing for Browser Cache Weaknesses | Semi-manual |
| 36 | WSTG-ATHN-07 | Testing for Weak Authentication Methods | Manual |
| 37 | WSTG-ATHN-08 | Testing for Weak Security Question Answer | Manual |
| 38 | WSTG-ATHN-09 | Testing for Weak Password Change or Reset Functionalities | Manual |
| 39 | WSTG-ATHN-10 | Testing for Weaker Authentication in Alternative Channel | Manual |
| 40 | WSTG-ATHN-11 | Testing Multi-Factor Authentication (MFA) | Manual |
| 41 | WSTG-ATHZ-01 | Testing Directory Traversal File Include | Semi-manual |
| 42 | WSTG-ATHZ-02 | Testing for Bypassing Authorization Schema | Manual |
| 43 | WSTG-ATHZ-03 | Testing for Privilege Escalation | Manual |
| 44 | WSTG-ATHZ-04 | Testing for Insecure Direct Object References | Semi-manual |
| 45 | WSTG-ATHZ-05 | Testing for OAuth Weaknesses | Semi-manual |
| 46 | WSTG-SESS-01 | Testing for Session Management Schema | Manual |
| 47 | WSTG-SESS-02 | Testing for Cookies Attributes | Automatable |
| 48 | WSTG-SESS-03 | Testing for Session Fixation | Manual |
| 49 | WSTG-SESS-04 | Testing for Exposed Session Variables | Manual |
| 50 | WSTG-SESS-05 | Testing for Cross Site Request Forgery | Semi-manual |
| 51 | WSTG-SESS-06 | Testing for Logout Functionality | Manual |
| 52 | WSTG-SESS-07 | Testing Session Timeout | Manual |
| 53 | WSTG-SESS-08 | Testing for Session Puzzling | Manual |
| 54 | WSTG-SESS-09 | Testing for Session Hijacking | Manual |
| 55 | WSTG-SESS-10 | Testing JSON Web Tokens | Automatable |
| 56 | WSTG-SESS-11 | Testing for Concurrent Sessions | Manual |
| 57 | WSTG-INPV-01 | Testing for Reflected Cross Site Scripting | Semi-manual |
| 58 | WSTG-INPV-02 | Testing for Stored Cross Site Scripting | Semi-manual |
| 59 | WSTG-INPV-03 | Testing for HTTP Verb Tampering | Semi-manual |
| 60 | WSTG-INPV-04 | Testing for HTTP Parameter Pollution | Semi-manual |
| 61 | WSTG-INPV-05 | Testing for SQL Injection | Semi-manual |
| 62 | WSTG-INPV-06 | Testing for LDAP Injection | Manual |
| 63 | WSTG-INPV-07 | Testing for XML Injection | Semi-manual |
| 64 | WSTG-INPV-08 | Testing for SSI Injection | Manual |
| 65 | WSTG-INPV-09 | Testing for XPath Injection | Manual |
| 66 | WSTG-INPV-10 | Testing for IMAP SMTP Injection | Manual |
| 67 | WSTG-INPV-11 | Testing for Code Injection | Semi-manual |
| 68 | WSTG-INPV-12 | Testing for Command Injection | Semi-manual |
| 69 | WSTG-INPV-13 | Testing for Buffer Overflow | Manual |
| 70 | WSTG-INPV-13 | Testing for Format String Injection | Manual |
| 71 | WSTG-INPV-14 | Testing for Incubated Vulnerability | Manual |
| 72 | WSTG-INPV-15 | Testing for HTTP Splitting Smuggling | Semi-manual |
| 73 | WSTG-INPV-16 | Testing for HTTP Incoming Requests | Manual |
| 74 | WSTG-INPV-17 | Testing for Host Header Injection | Semi-manual |
| 75 | WSTG-INPV-18 | Testing for Server-side Template Injection | Semi-manual |
| 76 | WSTG-INPV-19 | Testing for Server-Side Request Forgery | Semi-manual |
| 77 | WSTG-INPV-20 | Testing for Mass Assignment | Semi-manual |
| 78 | WSTG-ERRH-01 | Testing for Improper Error Handling | Semi-manual |
| 79 | WSTG-ERRH-02 | Testing for Stack Traces | Semi-manual |
| 80 | WSTG-CRYP-01 | Testing for Weak Transport Layer Security | Automatable |
| 81 | WSTG-CRYP-02 | Testing for Padding Oracle | Semi-manual |
| 82 | WSTG-CRYP-03 | Testing for Sensitive Information Sent via Unencrypted Channels | Semi-manual |
| 83 | WSTG-CRYP-04 | Testing for Weak Encryption | Automatable |
| 84 | WSTG-BUSL-01 | Test Business Logic Data Validation | Manual |
| 85 | WSTG-BUSL-02 | Test Ability to Forge Requests | Manual |
| 86 | WSTG-BUSL-03 | Test Integrity Checks | Manual |
| 87 | WSTG-BUSL-04 | Test for Process Timing | Manual |
| 88 | WSTG-BUSL-05 | Test Number of Times a Function Can Be Used Limits | Manual |
| 89 | WSTG-BUSL-06 | Testing for the Circumvention of Work Flows | Manual |
| 90 | WSTG-BUSL-07 | Test Defenses Against Application Misuse | Manual |
| 91 | WSTG-BUSL-08 | Test Upload of Unexpected File Types | Semi-manual |
| 92 | WSTG-BUSL-09 | Test Upload of Malicious Files | Semi-manual |
| 93 | WSTG-BUSL-10 | Test Payment Functionality | Manual |
| 94 | WSTG-CLNT-01 | Testing for DOM-Based Cross Site Scripting | Semi-manual |
| 95 | WSTG-CLNT-02 | Testing for JavaScript Execution | Manual |
| 96 | WSTG-CLNT-03 | Testing for HTML Injection | Manual |
| 97 | WSTG-CLNT-04 | Testing for Client-side URL Redirect | Automatable |
| 98 | WSTG-CLNT-05 | Testing for CSS Injection | Manual |
| 99 | WSTG-CLNT-06 | Testing for Client-side Resource Manipulation | Manual |
| 100 | WSTG-CLNT-07 | Testing Cross Origin Resource Sharing | Automatable |
| 101 | WSTG-CLNT-08 | Testing for Cross Site Flashing | Manual |
| 102 | WSTG-CLNT-09 | Testing for Clickjacking | Automatable |
| 103 | WSTG-CLNT-10 | Testing WebSockets | Semi-manual |
| 104 | WSTG-CLNT-11 | Testing Web Messaging | Manual |
| 105 | WSTG-CLNT-12 | Testing Browser Storage | Semi-manual |
| 106 | WSTG-CLNT-13 | Testing for Cross Site Script Inclusion | Semi-manual |
| 107 | WSTG-CLNT-14 | Testing for Reverse Tabnabbing | Automatable |
| 108 | WSTG-APIT-01 | API Reconnaissance | Automatable |
| 109 | WSTG-APIT-02 | API Broken Object Level Authorization | Semi-manual |
| 110 | WSTG-APIT-99 | Testing GraphQL | Automatable |
