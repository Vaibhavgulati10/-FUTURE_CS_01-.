# FUTURE_CS_01 – Web Application Security Testing 🔐

This repository contains Task 1 for my Cyber Security Internship with [Future Interns](https://futureinterns.com).  
The objective of this task is to identify and report common web application vulnerabilities.

## 🔍 Task Objective
Perform security testing on a vulnerable web application to identify:
- SQL Injection
- Cross Site Scripting (XSS)
- Authentication Flaws

## 🛠 Tools Used
- Manual testing via web browser
- Burp-Suite Community Edition 
- Target: [OWASP Juice Shop](https://demo.owasp-juice.shop)

## ✅ Vulnerabilities Tested

### 1. SQL Injection(Admin login)
- **Payload Used:** `' OR 1=1--`
- **Result:** Login bypass successful

### 2. Classic Stored XSS
- **Payload Used:** `<<script>sscript>alert("XSS")</script>`
- **Result:** Attempted via Admin Page

### 3. Broken Access Control (Admin Section)
- **Tested With:** Inspect tools 
- **Result:** Successfully accessing adminsrtation page 

## 📄 Report
See [`Future_CS_O1.pdf`](./Future_CS_O1.pdf)  for full details. 

---

## 🌐 Connect with Me
- 🔗 [LinkedIn](https://www.linkedin.com/in/vaibhav-gulati-9a2b15354/)
- 📫 gulativaibhav10@gmail.com
