# Web Application Testing (DVWA)

## 🔹 Objective

To identify vulnerabilities in a web application using both manual and automated testing techniques.

---

## 🛠 Tools Used

* Burp Suite
* sqlmap
* OWASP ZAP

---

## 📊 Test Log

| Test ID | Vulnerability | Severity | Target URL                 |
| ------- | ------------- | -------- | -------------------------- |
| 001     | SQL Injection | Critical | http://192.168.1.200/login |
| 002     | Reflected XSS | Medium   | http://192.168.1.200/form  |

---

## 🔍 Testing Performed

### Manual Testing

* Intercepted requests using Burp Suite
* Modified parameters
* Observed server responses

### Automated Testing

* Used sqlmap to confirm SQL Injection
* Scanned endpoints using OWASP ZAP

---

## ✅ Checklist

* SQL Injection tested
* XSS payloads tested
* Authentication mechanism reviewed

---

## 📌 Result

Multiple OWASP Top 10 vulnerabilities were successfully identified.

---

## 📝 Summary (50 words)

The DVWA application was tested using manual and automated techniques. Critical vulnerabilities such as SQL Injection and Cross-Site Scripting were discovered. These issues can lead to unauthorized data access and session hijacking. Proper input validation and secure coding practices must be implemented to mitigate these risks.
