## PortSwigger

### Completed Labs

#### SQL Injection
- SQL injection vulnerability in WHERE clause allowing retrieval of hidden data  
- SQL injection vulnerability allowing login bypass  
- SQL injection attack, querying the database type and version on Oracle  

#### Cross-Site Scripting (XSS)
- Reflected XSS into HTML context with nothing encoded  
- Stored XSS into HTML context with nothing encoded  
- Reflected XSS into attribute with angle brackets HTML-encoded  
- DOM XSS in document.write sink using source `location.search`  
- DOM XSS in innerHTML sink using source `location.search`  
- DOM XSS in jQuery anchor `href` attribute sink using `location.search` source  
- DOM XSS in jQuery selector sink using a `hashchange` event  

#### Server-Side Request Forgery (SSRF)
- Basic SSRF against the local server  

#### OS Command Injection
- OS command injection, simple case  
- Blind OS command injection with time delays  

#### Access Control Vulnerabilities
- Unprotected admin functionality  
- Unprotected admin functionality with unpredictable URL  


### Screenshot 

<img width="864" height="573" alt="image" src="https://github.com/user-attachments/assets/c61cf6e5-691b-4753-8515-9c8c548a3d7d" />

## Reflection (PortSwigger)

Working through the PortSwigger labs helped me understand how real-world web vulnerabilities work in practice. I learned how SQL injection, XSS, SSRF, OS command injection, and access control issues occur due to poor input validation and insecure design. These labs improved my ability to analyze HTTP requests, understand application behavior, and think like an attacker while acting responsibly. Overall, the exercises strengthened my technical skills and increased my awareness of secure web application development.

---

## The Booking System Project

### Phase 1 – Environment Setup and Application Understanding

**What I did:**  
I set up the booking system using Docker and explored the application by running the containers and reviewing how the components interact.

**What worked:**  
The Docker environment started correctly, and the application was accessible through the browser.

**What didn’t work:**  
Initially, I faced issues understanding container ports and service communication.

**What took the most time:**  
Understanding the application architecture and how the backend and frontend interact.

**What I learned:**  
How containerized applications are deployed and how to approach them from a security testing perspective.

---

### Phase 2 – Vulnerability Scanning and Reporting

**What I did:**  
I used OWASP ZAP to perform automated vulnerability scans and documented the results.

**What worked:**  
Automated scanning and report generation worked well.

**What didn’t work:**  
Some findings were false positives and required manual verification.

**What took the most time:**  
Analyzing scan results and writing a clear, structured report.

**What I learned:**  
How to identify real security issues and report them professionally.

---

### Phase 3 – Authentication and Authorization Testing

**What I did:**  
I tested authentication and authorization for different user roles and manually verified access to restricted endpoints.

**What worked:**  
Manual testing of roles and access controls.

**What didn’t work:**  
Some endpoints were difficult to enumerate.

**What took the most time:**  
Manual authorization testing.

**What I learned:**  
The importance of enforcing strict access control and proper role validation.

---

### Phase 4 – GDPR and Security Improvements

**What I did:**  
I updated the GDPR checklist and reviewed privacy-related documentation such as privacy policy and terms of service.

**What worked:**  
Documentation updates and compliance checks.

**What didn’t work:**  
Understanding legal terminology required extra effort.

**What took the most time:**  
Interpreting GDPR requirements and applying them correctly.

**What I learned:**  
How legal compliance and cybersecurity are closely connected.

---

## Reflection (Booking System Project)

The booking system project helped me apply theoretical cybersecurity knowledge to a practical application. I learned how to use tools like Docker and OWASP ZAP to identify and analyze vulnerabilities. Testing authentication, authorization, and GDPR compliance showed how security and privacy must be integrated into application design. Writing reports and documenting findings also improved my technical communication skills, which are essential in cybersecurity work.

# Logbook

## Git Repository
GitHub repository link:  https://github.com/hiraacharya02/Cybersecurity-and-data-privacy-.git


### Total Hours
#### Total hours spent: 88 hours ####  
#### Hours per topic: https://github.com/hiraacharya02/Cybersecurity-and-data-privacy-/blob/main/Logbook.md
---



