# Security Policy

## 🔒 Security Overview

CyberResume ATS Pro is a **100% client-side static web application**.

- ✅ No backend server
- ✅ No database
- ✅ No user accounts
- ✅ No data collection or transmission
- ✅ All resume data stays in your browser memory only
- ✅ Nothing is sent to any server
- ✅ HTTPS enforced via GitHub Pages

## Supported Versions

| Version | Supported |
| ------- | --------- |
| Latest (main branch) | ✅ Yes |

## Reporting a Vulnerability

If you discover a security vulnerability, please:

1. **Do NOT** open a public GitHub issue
2. Email: your-email@domain.com
3. Include: description, steps to reproduce, potential impact

We will respond within 48 hours and patch within 7 days for critical issues.

## Scope

Since this is a static front-end only app, the main security concerns are:

- XSS vulnerabilities in resume rendering
- Malicious content injection via form inputs
- Third-party dependency risks (we use zero external JS dependencies)

## Privacy

Your resume data is **never stored, transmitted, or collected**.  
It exists only in your browser's memory during your session.  
Closing the tab permanently deletes all data.
