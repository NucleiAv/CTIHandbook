# Port Scanning

**Definition and Importance**

* **Port Scanning**: Technique used to identify open ports and services on a network, often to assess potential vulnerabilities.
* **Port**: A docking point for data exchange in computer networks.
  * **Well-known Ports (0-1,023)**: Administered by IANA - Internet Assigned Numbers Authority  (e.g., Port 20 - FTP, Port 22 - SSH, Port 80 - HTTP).
  * Port 20, which is UDP, holds the File Transfer Protocol that we use for data transfer. \
    Port 22 of a TCP holds the SSH, Secure Shell Protocol for secure logins, ftp, and port forwarding. \
    Port 50 of a UDP is the Domain Name System, DNS, which translates names to IP addresses. \
    Port 80 of a TCP, which is the world wide HTTP.
  * **Registered Ports (1,024-49,151)**: Registered by software corporations.
  * **Dynamic/Private Ports (49,152-65,536)**: Available for use by anyone.

**Responses to Port Scanning**

* **Open**: Port is listening and ready to accept data.
* **Closed**: Port is in use, but no services are available.
* **Filtered/Blocked**: No response, usually due to a firewall.

**Types of Port Scanning Techniques**

1. **Ping Scan**:
   * Basic method using ICMP echo request to detect active hosts.
2. **TCP/Half-Open (SYN) Scan**:
   * Popular for being stealthy; sends SYN packet but doesn't complete the connection, making it harder to detect.
3. **TCP Connect Scan**:
   * Completes the TCP handshake, making it more detectable but detailed.
4. **UDP Scan**:
   * Sends empty packets, only receiving a response if the port is closed.
5. **Stealth Scan**:
   * Quieter TCP scan designed to evade detection by firewalls and IDS.

**Tools for Port Scanning**

* **NMAP (Network Mapper)**:
  * Open-source tool for network exploration and security auditing.
  * Scans large networks and individual hosts.
  * Identifies available hosts, services, OS versions, and firewall settings.
  * NMAP uses raw IP packets in novel ways to determine what hosts are available on the network, what services, application name and version those hosts are offering, and what operating system and version of they are running, and what type of packet filters or firewalls are in use, and dozens of other characteristics.
  * The default scan in nmap is SYN scan.
* **ZenMap**:
  * GUI version of NMAP, making it more user-friendly and visually informative.
