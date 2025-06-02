# Automated_Port_Scanner
This project involves developing a simple automated port scanner using Python to perform active network reconnaissance. The tool scans a target IP address or domain to identify open ports and their associated services. This mimics the first phase of penetration testing — information gathering — which is essential in any offensive cybersecurity engagement.

### Abstract
This project involves developing a simple automated port scanner using Python 
to perform active network reconnaissance. The tool scans a target IP address or 
domain to identify open ports and their associated services. This mimics the first 
phase of penetration testing — information gathering — which is essential in any 
offensive cybersecurity engagement. 

***Port Scanner***
A port scanner is a cybersecurity tool used to identify open ports and services 
running on a target machine. In the context of offensive security, port scanning 
is a critical step during the reconnaissance phase of penetration testing, as it 
helps attackers or ethical hackers map the network and detect potential entry 
points. 
This project involves creating a Python-based automated port scanner that 
connects to specified ports on a target IP address or domain to check their status 
(open/closed). The scanner also attempts to retrieve service banners from open 
ports, providing further insight into the system’s exposed services. 
By automating this process using Python and multithreading, the tool allows fast 
and efficient scanning of port ranges, mimicking real-world penetration testing 
techniques. 

***Objectives*** 
1. Scan target IP for open ports 
2. Identify services from banners 
3. Log or display results clearly 
4. Understand ethical usage in penetration testing

***Tools Used*** 
> Python 3 
> Libraries: socket, argparse, concurrent.futures 

***Methodology***
1. Target IP is resolved. 
2. Ports scanned in parallel threads. 
3. Open ports are logged with banners. 
4. Results displayed in console.

***Sample Run***

![Screenshot 2025-06-03 031345](https://github.com/user-attachments/assets/e0873cb8-43e3-49d7-ac15-609e21b9771b)

***Conclusion*** 

The Python-based port scanner developed in this project demonstrates the core 
concepts of network reconnaissance in offensive cybersecurity. By scanning and 
identifying open ports and service banners on a target system, the tool aids in 
detecting potential vulnerabilities that could be exploited in further stages of 
penetration testing. 
This project not only reinforces the practical use of Python in cybersecurity but 
also emphasizes the importance of ethical hacking practices. The port scanner 
provides a solid foundation for understanding how attackers gather information 
and how defenders can proactively secure exposed services. 

