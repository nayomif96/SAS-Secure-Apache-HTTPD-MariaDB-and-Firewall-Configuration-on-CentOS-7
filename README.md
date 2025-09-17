# SAS-Secure-Apache-HTTPD-MariaDB-and-Firewall-Configuration-on-CentOS-7
# System Administration & Security: Apache HTTPD, MariaDB, and Firewall Hardening on CentOS 7

This project demonstrates hands-on experience in **system administration and security**, showcasing the deployment, configuration, and hardening of Linux servers to industry-standard security practices.

---

## Project Overview

This project focuses on **securing and managing critical Linux services**, including:

- **Apache HTTPD** – Deploying a secure web server with SSL/TLS encryption, HTTP security headers, and access control.  
- **MariaDB Database** – Installing, configuring, and securing the database with controlled user privileges and proper logging.  
- **Firewall Configuration** – Managing traffic and network security using `firewalld` and `iptables`.  

The emphasis is on identifying vulnerabilities, implementing mitigations, and ensuring reliable, secure system operations.

---

## Key Highlights

- **Apache Hardening**  
  - Enabled SSL/TLS and redirected HTTP traffic to HTTPS to protect sensitive data.  
  - Configured HTTP security headers (CSP, X-XSS-Protection, X-Frame-Options, X-Content-Type-Options).  
  - Concealed server version and module information to reduce the attack surface.  
  - Secured web content files using SELinux contexts and restrictive permissions.  

- **MariaDB Security**  
  - Configured secure root access and least-privilege users.  
  - Created databases and tables with controlled access to protect data integrity.  
  - Implemented logging and auditing for security monitoring.  

- **Firewall & Network Security**  
  - Allowed only essential services (HTTP/HTTPS/SSH) while blocking unnecessary ports.  
  - Applied rate-limiting to protect against brute-force attacks and DDoS attempts.  
  - Monitored logs for anomalies and enforced security policies.  

- **Risk & Vulnerability Management**  
  - Addressed issues such as unencrypted traffic, weak firewall rules, information disclosure, missing security headers, and exposed files.  
  - Applied mitigation strategies aligned with **CIS, NIST, ISO 27001, and GDPR standards**.  

---

## Tools & Technologies

- **Operating System:** CentOS 7  
- **Web Server:** Apache HTTPD 2.4  
- **Database:** MariaDB  
- **Firewall:** `firewalld` & `iptables`  
- **Security Tools:** SELinux, mod_ssl, Certbot, curl, Lynx  
- **Monitoring & Logs:** Access logs, error logs, audit logs  

---

## Outcome

The project delivers a **secure, hardened server environment** with:

- Encrypted web traffic and protected web content.  
- Controlled database access with minimal privileges.  
- Strong network protection via robust firewall rules.  
- Reduced attack surface and compliance with security best practices.  

This project highlights expertise in **system administration, Linux server hardening, network security, and risk management**, demonstrating practical, real-world skills in securing enterprise-grade systems.




