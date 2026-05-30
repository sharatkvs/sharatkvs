<h1 align="center">Hi, I'm K V S Sharat Chandra</h1>
<h3 align="center">Cybersecurity Analyst · Bug Bounty Hunter </h3>

<br/>

<p align="center">
  <a href="https://www.linkedin.com/in/sharat-chandra-561707256/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://x.com/Sharatchandra_1" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
  &nbsp;
  &nbsp;
  <a href="https://bugcrowd.com/h/Sharat_Chandra" target="_blank">
    <img src="https://img.shields.io/badge/Bugcrowd-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white" />
  </a>
</p>

---

## About Me

I'm a cybersecurity professional currently working as a VAPT Intern at **iGaruda Secure Cyber Solutions**, where I do web application and network penetration testing for real clients every day.

On the side I hunt bugs on Bugcrowd — 9 valid vulnerabilities submitted so far, sitting at the **84th percentile globally** for high-severity findings, with a **88.89% submission accuracy rate**. Got Hall of Fame recognition from **NASA**, **McDonald's**, and **Broadcom** along the way.


---

## What I Work On

**Web Application Security**
Testing for OWASP Top 10, authentication flaws, IDOR, business logic vulnerabilities, and misconfigured servers. Comfortable with both manual testing and automation.

**API Security**
REST and GraphQL API testing — broken object level authorization, excessive data exposure, improper rate limiting, JWT vulnerabilities. APIs are often where the real findings hide.

**Mobile Security (Android)**
Static and dynamic analysis of Android APKs. Looking for insecure data storage, improper certificate validation, hardcoded secrets, and exposed components.

**Thick Client Security**
Testing desktop applications for traffic interception vulnerabilities, insecure local storage, DLL hijacking, and memory-based exposures using tools like Wireshark and Burp Suite.

**Network Security & Threat Intelligence**
Network penetration testing, OSINT, exposed asset discovery, leaked credential hunting, and SOC alert monitoring using Wazuh SIEM.

---

## Currently Learning

I never stop at what I already know. Right now I'm going deeper into:

- **Malware Analysis** — understanding how malicious software behaves at the binary level
- **Reverse Engineering** — assembly language, static and dynamic analysis of binaries
- **Azure Security** — cloud attack surface, misconfigurations, identity and access management
- **Secure Code Review** — reading source code to find vulnerabilities before they ship
- **Active Directory Attacks** — Kerberoasting, Pass-the-Hash, BloodHound enumeration

---

## Tools I Use Regularly

| Category | Tools |
|----------|-------|
| Web Testing | Burp Suite, OWASP ZAP, SQLMap, Nikto, Gobuster |
| Network | Nmap, Wireshark, Metasploit, Nessus, Acunetix |
| SIEM / SOC | Wazuh |
| API Testing | Postman, Burp Suite |
| OSINT & Recon | Custom Python tools, Shodan |
| OS | Kali Linux, Ubuntu, Windows |

---

## Projects I Built

### ReconX — Web Recon & Security Posture Scanner
A reconnaissance tool I wrote in Python with zero external dependencies.
Point it at any domain and it automatically runs 10 security checks:
DNS enumeration, subdomain discovery, port scanning, SSL inspection,
security header analysis, CORS misconfiguration detection, sensitive file exposure,
WAF identification, technology fingerprinting, and cookie security auditing.
Saves a full HTML report at the end.

Everything runs on Python's standard library — no pip install, no setup.

→ [View Repository](https://github.com/sharatkvs/reconx)

---

### JWTBreaker — JWT Security Testing Toolkit
An offensive toolkit for testing JWT authentication vulnerabilities.
Implements four real attack techniques from scratch:

- **alg:none attack** — strips the signature, tests if the server accepts unsigned tokens (CVE-2015-9235)
- **Secret cracking** — brute-forces weak HMAC keys, processes 200k+ candidates per second
- **Token forging** — creates valid signed tokens with modified claims (role=admin etc.) once the secret is known
- **Algorithm confusion** — RS256 to HS256 attack using the server's public key (CVE-2016-10555)

Also has a live scanner that finds JWTs in cookies, headers, and JSON responses automatically.
Written using only Python's standard library — no PyJWT, no external packages.

→ [View Repository](https://github.com/sharatkvs/jwt_breaker)

---


## Certifications

- CEH v13 — Certified Ethical Hacker (EC-Council)
- Penetration Testing, Web Security Testing & Bug Bounty Hunting (ZSecurity)
- IT Security: Defense Against the Digital Dark Arts (Google)
- Postman API Fundamentals Student Expert

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sharatkvs&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="160"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sharatkvs&layout=compact&theme=github_dark&hide_border=true" height="160"/>
</p>

---

<p align="center">
  <i>Open to collaborating on security research, CTF challenges, and bug bounty. Feel free to reach out.</i>
</p>

