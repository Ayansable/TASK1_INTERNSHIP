# TASK1_INTERNSHIP
A  network security project that uses Nmap to perform a TCP SYN scan on a local network to identify active hosts and open ports. The project includes traffic analysis using Wireshark, covers basic reconnaissance techniques, and highlights how to interpret scan results to identify potential vulnerabilities.
#  Port Scanning with Nmap

This is a simple project to scan a local network using *Nmap* and  analyze traffic using *Wireshark*.
# Tools
- Nmap: https://nmap.org
- Wireshark: https://wireshark.org

# How to Run
1. Install Nmap.
2. Find your IP range (e.g., 192.168.0.0/24).
3. Run:

#   What This Project Contains:
Nmap Scan Scripts/Commands: Example commands to perform TCP SYN scans (-sS) across local IP ranges.
Scan Results: Sample output files showing discovered IPs, open ports, and running services.

# Guides: Step-by-step instructions on how to:
Find your local IP range.
Perform a network scan with Nmap.
Interpret scan results.
capture network traffic using Wireshark.

# how to use command 
1- nmap -sS ip ranges yours (find which port is open closed )
2- nmap  -A aggresive which detect the vulnerability 
3- nmap -sn ping command 
4-nmap -p port 22 scanning
examples there are many that we can use and analyze.
