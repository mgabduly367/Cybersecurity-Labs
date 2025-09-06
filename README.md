# Cybersecurity-Labs
🔍 Nmap Vulnerability Scan & Report  

📌 Project Overview  
This project demonstrates how to use **Nmap**, a popular open-source network scanning tool, to identify open ports and potential vulnerabilities on a target system (for learning purposes only).  

The goal is to:  
a. Practice network reconnaissance techniques.  
b. Understand common open ports and services.  
c. Document risks and possible mitigations.  



🛠️ Tools & Environment  
a. **Nmap** (Network Mapper)  
b. Test environment: Virtual Machine (Ubuntu/Metasploitable2)  
c. Operating System: Kali Linux  



🚀 Steps Performed  
1. Installed and updated Nmap on Kali Linux.  
2. Identified the IP address of the target machine.  
3. Ran different types of Nmap scans:  
   a. Basic ping scan  
   b. Service/version detection (`-sV`)  
   c. Aggressive scan (`-A`)  
   d. Vulnerability script scan (`--script vuln`)  
4. Collected scan results and analyzed open ports.  
5. Documented findings and suggested mitigations.  


📊 Sample Results (Example Output)  
a. **Open Port 22 (SSH)** – Running OpenSSH 4.7p1 (outdated, potential vulnerabilities).  
b. **Open Port 80 (HTTP)** – Apache httpd 2.2.8 (exploitable if unpatched).  
c. **Open Port 3306 (MySQL)** – Accessible remotely, risk of SQL injection or brute force.  



🛡️ Security Recommendations  
a. Disable or restrict access to unnecessary services.  
b. Keep all software and services updated.  
c. Use firewalls to limit inbound/outbound traffic.  
d. Enforce strong authentication for SSH and databases.  



📂 Repository Contents  
a. `scan-results.txt` → Nmap raw output.  
b. `report.pdf` → Full vulnerability report with screenshots.  
c. `README.md` → Project documentation.  



📖 Learning Outcomes  
a. Gained hands-on experience with Nmap scanning.  
b. Learned how to interpret open ports and services.  
c. Improved understanding of network vulnerabilities and mitigations.  



⚠️ **Disclaimer:** This project was done in a controlled lab environment on test machines only. Never scan networks without explicit permission.  
