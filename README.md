# AT-Task2
# 🛡️ Task 2 - Web Application Vulnerability Scanning

**🎓 Internship:** Alfido Tech Cybersecurity Internship  
**👩‍💻 Intern:** Virendra Kumar  
**🔧 Tool Used:** OWASP ZAP  
**💻 Platform:** Linux  
**🌐 Target Website:** [http://zero.webappsecurity.com](http://zero.webappsecurity.com)

---

## 📌 Task Overview

The objective of this task was to perform **automated vulnerability scanning** on a deliberately vulnerable web application using **OWASP ZAP**, and identify common web security flaws such as:

- Cross-Site Scripting (XSS)  
- SQL Injection (SQLi)  
- Insecure HTTP Headers  
- Session and Cookie Weaknesses  

This task helped build hands-on experience with **automated tools** used by security analysts and bug bounty hunters.

---

## 🛠️ Tools Used

| Tool        | Purpose                                   |
|-------------|-------------------------------------------|
| **OWASP ZAP** | Automated scanning for web vulnerabilities |
| **Linux OS**  | Host environment for running the tool      |

---

## 🚀 Scan Process (Step-by-Step)

### 1️⃣ Launch OWASP ZAP
Start ZAP from terminal:
```bash
zap.sh
```
### 2️⃣ Set Target URL
Entered the target in ZAP:
```http://zero.webappsecurity.com```
### 3️⃣ Start Active Scan
- Used Spider (Crawl) to discover URLs and forms
- Performed Active Scan to detect vulnerabilities

### 📷 Screenshots

### 🖼️ 1. Target Website Loaded in ZAP
<img width="1920" height="954" alt="Screenshot (403)" src="https://github.com/user-attachments/assets/79e9ee45-8efd-4341-99e1-ddae90f41280" />


### ⚠️ 2. ZAP Alert Summary
Shows a list of vulnerabilities detected after scanning:
<img width="1920" height="1017" alt="Screenshot (404)" src="https://github.com/user-attachments/assets/ede6c769-3764-409b-8846-c24b1034a298" />


### ✅ Result Summary
#### ✔️ Successfully scanned the test web application using OWASP ZAP
#### ✔️ Identified multiple vulnerabilities including:

#### 🔸 Reflected XSS
#### 🔸 Potential SQL Injection
#### 🔸 Insecure HTTP Headers
#### 🔸 Missing HttpOnly and Secure flags on cookies

This task provided real-world insight into automated web application scanning and how ZAP can be used to uncover common OWASP Top 10 issues.

### 💼 Internship Info
#### Program: Alfido Tech – Cybersecurity Internship
#### Task: Web Application Vulnerability Scanning using ZAP
#### Intern: Virendra Kumar



