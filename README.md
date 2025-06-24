 Secure Portfolio Website Deployment
This project demonstrates how to securely deploy and manage a personal portfolio website on a virtual machine running Ubuntu. It was developed as part of my cybersecurity diploma to explore secure web hosting, Linux administration, and common attack simulations in a real-world environment.

📌 Project Overview
The project includes:

-Hosting a PHP-based portfolio website with login and blog functionality
-Configuring secure access with role-based access control (RBAC)
-Securing the server using iptables firewall rules
-Monitoring the server with Zabbix
-Simulating common web attacks (SQL Injection & Forced Browsing)
-Ensuring secure access across virtual machines

🧱 Technologies Used
-LAMP Stack: Apache, MySQL, PHP
-phpMyAdmin for DB management
-Zabbix for monitoring
-iptables for firewall configuration
-Ubuntu 22.04 server environment
-VirtualBox for VM testing

🔧 Features Implemented
✅ 1. Secure Web Server Setup
Installed Apache, MySQL, PHP, and phpMyAdmin
Proper file permissions and ownership
Website served from /var/www/html
✅ 2. Role-Based Access Control (RBAC)
PHP-based authentication with MySQL backend
Redirects based on user roles (admin/user)
✅ 3. Firewall Configuration (iptables)
Only allowed essential ports: HTTP (80), HTTPS (443), and SSH (22)
Restricted SSH access to a single trusted IP
✅ 4. Server Monitoring (Zabbix)
Zabbix agent installed on the web server
Monitoring for HTTP response, CPU, RAM, and disk usage
Email alerts configured for critical events
✅ 5. Security Testing
SQL Injection: Mitigated via prepared statements
Forced Browsing: Blocked using session-based access control
✅ 6. External Access Test
Website successfully accessed from another VM within the network

🛡️ Key Takeaways
Gained hands-on experience in secure website deployment
Applied Linux system administration and firewall best practices
Validated security through real-world attack simulations
Implemented effective monitoring and alerting for availability and resource usage

📬 Contact
Lovish Ramphul
Cybersecurity Student | SOC Analyst in Training
LinkedIn | GitHub
