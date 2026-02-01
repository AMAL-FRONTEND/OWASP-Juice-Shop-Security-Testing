# OWASP Juice Shop Security Testing

## Project Overview

This project demonstrates **basic web application security testing** using **OWASP Juice Shop**, an intentionally vulnerable web application. The goal of this project is to identify common web vulnerabilities and understand their potential impact in a **safe, local lab environment**.

> ⚠️ All testing was performed locally for educational purposes only.

---

## Tools Used

* **Kali Linux**
* **OWASP Juice Shop (Docker)**
* **Web Browser**
* *(Optional)* Burp Suite

---

## Project Objectives

* Run OWASP Juice Shop locally
* Identify common web application vulnerabilities
* Understand security risks and impacts
* Document findings in a structured manner

---

## Vulnerabilities Identified

### 1️⃣ SQL Injection (Login Bypass)

**Description:**
A SQL injection payload was used in the login field, allowing authentication to be bypassed without valid credentials.

**Impact:**

* Unauthorized access
* Authentication bypass
* Risk to sensitive user data

---

### 2️⃣ Weak Password Policy

**Description:**
The application allows users to register accounts using very weak passwords without enforcing password strength rules.

**Impact:**

* Increased risk of account compromise
* Susceptible to brute-force attacks

---

## Methodology

1. OWASP Juice Shop was deployed locally using Docker.
2. The application was accessed through a web browser.
3. Authentication and registration functionalities were tested.
4. Vulnerabilities were identified through manual testing.
5. Screenshots and findings were documented.

---

## Project Artifacts

* video demonstrating vulnerabilities
* 📄 Detailed findings report (`report.txt`)
* 🎥 Project demo video (LinkedIn)

---

## Demo Video

* LinkedIn: https://www.linkedin.com/posts/amal-n-k-032255364_cybersecurity-owasp-websecurity-activity-7423754942429052928-s-84?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFpzDuYBobGpFzcFAwUt0hxKGZ3Bx7RDj08

---

## Learning Outcomes

* Understanding of common web application vulnerabilities
* Hands-on experience with OWASP Juice Shop
* Improved awareness of secure authentication practices

---

## Disclaimer

This project is intended **strictly for educational purposes**. No real-world systems or public networks were tested.

