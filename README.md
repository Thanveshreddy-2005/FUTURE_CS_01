# 🔐 Vulnerability Assessment Report – Live Website

## 📌 Project Overview
This project demonstrates a **Vulnerability Assessment (VA)** performed on a **publicly available test website** to identify common security weaknesses.  
The assessment was conducted using **safe, ethical, and non-intrusive techniques**, focusing on detection, risk classification, and remediation recommendations.

---

## 🎯 Objective
- Identify common web security vulnerabilities
- Classify risks (Low / Medium)
- Perform passive and manual security analysis
- Document findings in a professional security report

---

## 🌐 Target Information
- **Target Website:** http://testphp.vulnweb.com  
- **Website Type:** Public test application (Acunetix demo site)  
- **Authorization:** The website is intentionally vulnerable and publicly provided for security testing and educational purposes.

---

## 🛠 Tools Used
- **Nmap** – Port scanning and service detection  
- **OWASP ZAP (Passive Scan)** – Web vulnerability identification  
- **Browser Developer Tools** – Manual header analysis  
- **Canva** – Professional report design  

---

## 🔍 Methodology
1. Target selection and authorization verification  
2. Port scanning using Nmap  
3. Passive vulnerability scanning using OWASP ZAP  
4. Manual inspection of HTTP response headers  
5. Risk classification based on impact  
6. Documentation and reporting  

---

## 🚨 Key Findings
| Vulnerability | Risk Level |
|--------------|-----------|
| HTTP Only Site (No HTTPS) | Medium |
| Missing Security Headers (CSP, X-Frame-Options) | Low |
| Server Version Disclosure | Low |
| X-Powered-By Header Disclosure | Low |
| Potential XSS (User-controllable HTML attribute) | Medium |

---

## 🛡 Recommendations
- Implement HTTPS using SSL/TLS certificates  
- Add HTTP security headers (CSP, X-Frame-Options, HSTS)  
- Hide server and framework version details  
- Validate and sanitize user input  
- Perform regular security assessments  

---
