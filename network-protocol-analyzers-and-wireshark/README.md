# Network Protocol Analyzers and Wireshark

**Network Protocol Analyzer Overview**

* **Definition**: Also known as a sniffer, packet analyzer, network analyzer, or traffic analyzer.
* **Function**: Captures data in transit for analysis and review.
* **Operation**: Works at the data link layer of the OSI model, allowing it to capture all data on the network without restrictions.

<figure><img src="../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

**Wireshark**

* **Wireshark**: The most widely-used protocol analyzer.
  * **Purpose**: Converts binary traffic into a human-readable format.
  * **Uses**:
    * **Network Troubleshooting**: Identifying and solving network issues.
    * **Security Analysis**: Examining security-related problems.
    * **QA Testing**: Verifying network-related issues.
    * **Protocol Debugging**: Used by developers to debug protocols.
    * **Learning Tool**: Helps individuals understand network protocols.
  * **Features**:
    * Deep inspection of hundreds of protocols.
    * Live capture and offline analysis.
    * Three-pane packet browser.
    * Cross-platform compatibility (Windows, Linux, MacOS, etc.).
    * Graphical User Interface (GUI) and TTY-mode Tshark utility.
    * Powerful display filters and rich VoIP analysis.
    * Reads and writes various capture file formats.
    * Supports gzip compression/decompression on the fly.
    * Decryption support for various protocols (e.g., IPSec, SSL/TLS, WPA2).
    * Customizable coloring rules for quick analysis.
    * Export options to formats like XML, PostScript, CSV, plain text, etc.

**Packet Capture (PCAP)**

* **PCAP Overview**:
  * **PCAP**: A file format used to capture and record network traffic.
  * **Uses**:
    * Monitoring bandwidth usage.
    * Identifying rogue DHCP servers.
    * Detecting malware.
    * DNS resolution and incident response.
  * **Wireshark**: Utilizes PCAP files to store captured network data.

**PCAP File Formats**

1. **Libpcap**:
   * Used in Unix-based systems like Linux and MacOS.
   * Traditional format for packet capture.
2. **PCAP**:
   * Older format for Windows, not commonly used as a default anymore.
3. **Pcapng (PCAP Next Generation)**:
   * Default format for Wireshark.
   * Captures and stores data, considered the next generation of packet capture formats.
4. **Npcap**:
   * Specific to Nmap, a port scanning tool with packet capture capabilities.
