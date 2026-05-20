# PassForge 🔐

<div align="center">

![NIST](https://img.shields.io/badge/NIST-800--63B-blue?style=for-the-badge)
![OWASP](https://img.shields.io/badge/OWASP-ASVS-orange?style=for-the-badge)
![MITRE](https://img.shields.io/badge/MITRE-T1110-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-success?style=for-the-badge)

### Enterprise-Grade Password Security Intelligence Platform

Real-time password analysis engine implementing entropy calculations, brute-force modeling, breach detection simulation, and standards-aligned credential security enforcement.

🔗 **Live Demo:** https://vasikaran24.github.io/passforge/

</div>

---

# 📌 Overview

PassForge is a professional password security intelligence platform designed for cybersecurity practitioners, SOC analysts, AppSec engineers, and IAM security workflows.

Unlike traditional password checkers that rely only on basic complexity rules, PassForge performs advanced security analysis using:

- Shannon Entropy calculations
- Brute-force attack modeling
- Threat intelligence concepts
- Pattern and anomaly detection
- NIST SP 800-63B policy alignment
- OWASP ASVS authentication validation
- MITRE ATT&CK technique mapping

All password analysis is performed entirely client-side for maximum privacy and security.

---

# 🚀 Features

## 🔐 Password Security Analysis

- Real-time password strength analysis
- Shannon entropy calculation
- Keyspace permutation analysis
- Brute-force crack-time estimation
- Common password detection
- Sequential pattern detection
- Repeated character detection
- Keyboard walk detection
- Dictionary word analysis
- Threat exposure scoring

---

## ⚡ Attack Scenario Modeling

PassForge simulates multiple real-world password attack scenarios:

| Attack Type | Estimated Guess Rate |
|-------------|----------------------|
| Online Throttled | 100 req/hr |
| Online Unthrottled | 10 req/sec |
| Offline Slow Hash | 10K/sec |
| Offline Fast Hash | 1B/sec |
| GPU Cluster Attack | 100B/sec |

---

## 🔑 Secure Password Generator

Built using the Web Crypto API:

```javascript
crypto.getRandomValues()
```

Generator modes:
- Secure Random Passwords
- Passphrase Generator
- Strong PIN Generator

---

# 🛡️ Security Standards Alignment

| Standard | Implementation |
|----------|----------------|
| NIST SP 800-63B | Password policy enforcement |
| OWASP ASVS | Authentication security validation |
| MITRE ATT&CK T1110 | Brute-force attack alignment |
| CWE-521 | Weak password detection |
| Web Crypto API | Cryptographically secure randomness |

---

# 🎯 MITRE ATT&CK Alignment

| Technique ID | Technique |
|--------------|-----------|
| T1110 | Brute Force |
| T1110.001 | Password Guessing |
| T1110.002 | Password Cracking |
| T1110.003 | Password Spraying |
| T1078 | Valid Accounts |

---

# 📂 Project Structure

```bash
passforge/
│
├── index.html
├── README.md
├── LICENSE
│
├── assets/
│   ├── screenshots/
│   └── diagrams/
│
├── src/
│   ├── engine/
│   ├── ui/
│   └── data/
│
└── tests/
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/vasikaran24/passforge.git
cd passforge
```

---

## Run Locally

### Option 1 — Direct Browser Launch

```bash
open index.html
```

---

### Option 2 — Local HTTP Server

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

---

# 🌐 Live Demo

🔗 https://vasikaran24.github.io/passforge/

---

# 📸 Screenshots

## Dashboard
(Add screenshot here)

## Password Analysis
(Add screenshot here)

## Secure Password Generator
(Add screenshot here)

---

# 🔒 Security Design Decisions

## Zero Dependencies

PassForge intentionally avoids third-party npm dependencies to reduce:
- Supply-chain attack risks
- Malicious package exposure
- External tracking

---

## Client-Side Privacy

Passwords never leave the browser.

No backend logging.
No credential storage.
No telemetry collection.

---

## Cryptographically Secure Randomness

Uses:

```javascript
crypto.getRandomValues()
```

instead of insecure pseudo-random generators like:

```javascript
Math.random()
```

---

# 📊 Skills Demonstrated

This project demonstrates:

- Security Engineering
- Threat Modeling
- Cryptography Fundamentals
- Detection Engineering
- Secure Frontend Development
- Authentication Security
- OWASP ASVS Compliance
- NIST 800-63B Implementation
- MITRE ATT&CK Mapping
- JavaScript Security Tooling

---

# 👨‍💻 Target Roles

✅ SOC Analyst  
✅ Security Engineer  
✅ AppSec Engineer  
✅ IAM Engineer  
✅ Detection Engineer  
✅ Junior Cybersecurity Analyst  

---

# 📈 Future Enhancements

- Real HaveIBeenPwned API integration
- zxcvbn password scoring
- SIEM telemetry export
- AI-powered password analysis
- Enterprise audit backend
- CSV bulk password auditing
- LDAP/Active Directory integration
- Browser extension support

---

# 📚 References

| Resource | Link |
|----------|------|
| NIST SP 800-63B | https://pages.nist.gov/800-63-3/sp800-63b.html |
| OWASP ASVS | https://owasp.org/www-project-application-security-verification-standard/ |
| MITRE ATT&CK T1110 | https://attack.mitre.org/techniques/T1110/ |
| CWE-521 | https://cwe.mitre.org/data/definitions/521.html |
| Web Crypto API | https://developer.mozilla.org/en-US/docs/Web/API/Crypto/getRandomValues |

---

# 📜 License

MIT License

---

<div align="center">

## PassForge 🔐

Enterprise Password Security Intelligence Platform

Built for cybersecurity practitioners.

</div>
