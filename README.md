<h1>Full Project</h1><br />
<br />
<h2>Nmap and Wireshark</h2>


<h3>Description</h3>
This project focuses on identifying and addressing network security vulnerabilities using Nmap and Wireshark. By analyzing network topology, vulnerabilities, and anomalies, we'll propose solutions to enhance network security. The project will involve running Nmap and Wireshark on a virtual network environment, saving the results, and providing recommendations based on findings.<br />
<br />
Please note: I have removed screenshots of my project, IP addresses, hostnames, and MAC addresses to protect sensitive information.<br />
<br />
<br />




<p align="center">
<h3>Summary of Vulnerabilities and Implications</h3>
<p>
  
<p align="left">
<h4>FTP Vulnerability: An unencrypted FTP server was identified, exposing data to potential sniffing attacks.<br />
<br />
SSH Vulnerability: SSH was running on the default port, making it susceptible to brute force attacks. Multiple devices were affected.<br />
<br />
HTTP Vulnerability: An HTTP server was found, which is less secure than HTTPS. Data transmitted over HTTP is not encrypted.</h4><br />
<br />

<p align="center">
  <h3>Wireshark Anomalies</h3>
</p>
<p align="left">
<h4>Unauthorized FTP Login: An unknown user attempted to log in to an FTP server.<br />
<br />
HTTP Exploitation Attempt: A device was attempting to exploit systems using HTTP instead of HTTPS.<br />
<br />
SMB Exploitation Attempt: A device was attempting to exploit SMB services.</h4><br />
<br />

<p align="center">
  <h3>Implications of Anomalies</h3>
</p>
<p align="left">
<h4>Data Exposure: Unencrypted FTP could have led to the exposure of sensitive data.<br />
<br />
Security Risks: HTTP and SMB vulnerabilities could have allowed attackers to gain unauthorized access or launch attacks.</h4><br />
<br />

<p align="center">
  <h3>Recommended Solutions</h3>
</p>
<p align="left">
<h4>- Network Scanning: Regularly scan the network using tools like Zenmap to identify vulnerabilities.<br />
<br />
- FTP Security: Implement network data loss prevention to secure FTP traffic and encrypt data.<br />
<br />
- HTTPS Migration: Ensure all systems are using HTTPS instead of HTTP to protect data in transit.<br />
<br />
- SMB Security: Update SMB software, enforce strong security practices, and disable unnecessary features.<br />
<br />
- User Education: Train users on cybersecurity best practices to prevent unauthorized access.<br />
<br />
<br />
  By addressing these vulnerabilities and anomalies, you can significantly enhance the security of your network.
</h4><br />
<br />

</p>
