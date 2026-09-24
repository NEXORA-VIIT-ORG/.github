# Security Policy

## NEXORA Student Chapter – VIIT

Security awareness is a foundational skill for modern software development. **NEXORA Student Chapter – VIIT** takes security seriously to protect our student projects, repositories, and learning environments.

---

## 1. Secrets Prevention & Confidentiality

To protect our organization and contributors, **NEVER commit sensitive credentials to any repository**.

### Prohibited Items:
- **Passwords**
- **API Keys** (e.g., OpenAI keys, AWS access keys, Stripe secret keys, Firebase admin keys)
- **Access Tokens** (e.g., GitHub Personal Access Tokens, OAuth tokens)
- **Private Keys** (e.g., SSH keys, SSL/TLS certificates, RSA private keys)
- **`.env` files** containing secret environment variables
- **Database Connection Strings** with embedded credentials

### Best Practices for Students:
1. Always add `.env`, `*.pem`, `*.key`, and config files with real credentials to your project's `.gitignore`.
2. Use environment variable templates (e.g., `.env.example` containing placeholder values like `API_KEY=your_key_here`).
3. If you accidentally commit a secret, **rely on git history cleanups and rotate/revoke the secret immediately**. Inform a `technical-team` mentor for assistance.

---

## 2. Responsible Vulnerability Disclosure

If you discover a security vulnerability or leaked secret in any project under `NEXORA-VIIT-ORG`, please report it responsibly:

1. **Do NOT open a public GitHub issue** to report a security vulnerability.
2. Contact the `technical-team` privately via the official NEXORA communication channel or directly by reaching out to a Technical Lead or Technical Member.
3. Provide details of the vulnerability (affected repository, file path, nature of the issue).
4. Our team will review the issue, revoke any exposed credentials, apply necessary patches, and acknowledge your report.

---

## 3. Cybersecurity Project Guidelines

NEXORA encourages cybersecurity learning, ethical hacking research, and defensive security development. However, all cybersecurity activities must strictly adhere to legal and ethical boundaries:

- **Authorized Systems Only**: Students must **ONLY** test systems, applications, or networks that they own or have explicit written authorization to test.
- **No Offensive Exploitation**: Do not attempt unauthorized penetration testing, vulnerability scanning, or denial-of-service attacks against college networks, external websites, or peer infrastructure.
- **Educational Scope**: Cybersecurity project repositories under NEXORA focus on defensive techniques, secure coding standards, educational CTFs, and vulnerability mitigation.
- **No Offensive Instructions**: Repositories must not host malware binaries, malicious payloads, or instructions intended for unauthorized offensive exploitation.

---

## 4. Security Code Reviews

All Pull Requests in NEXORA undergo security checks by `technical-team` members to verify:
- Absence of hardcoded credentials.
- Proper input validation and output encoding (preventing SQL injection, XSS, etc.).
- Safe dependency management and absence of known vulnerable packages.
