# Task-5-Wireshark.
Capture and analyze live network traffic
Tools Used
- **Kali Linux (VirtualBox)**
- **Wireshark 4.4.6**
- **Active Interface:** eth0
  
Capture Overview
- Total Packets Captured: 240
- Duration: ~20 seconds
- Traffic generated by browsing and DNS queries
  Protocols Identified

| Protocol | Description                  | Source IP        | Destination IP     | Port(s) Used   |
|----------|------------------------------|------------------|--------------------|----------------|
| ARP      | Address resolution            | 10.0.2.15        | 10.0.2.3           | -              |
| DNS      | Domain name lookup            | 10.0.2.15        | 10.0.2.3           | UDP 53         |
| TCP      | Connection-oriented traffic   | 10.0.2.15        | 31.13.79.53, etc.  | 443 (HTTPS)    |
| UDP      | Connectionless traffic        | 10.0.2.15        | 142.250.67.170     | 443            |
| TLSv1.2/1.3 | Encrypted web traffic      | Multiple         | Multiple           | TCP 443        |

