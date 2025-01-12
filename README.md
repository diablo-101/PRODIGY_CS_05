# PRODIGY_CS_05

## Network Packet Analyzer

`PRODIGY_CS_05` is a network packet analyzer tool written in Python. It captures and analyzes network packets to display relevant information such as:

- Source and destination MAC addresses
- Source and destination IP addresses
- Protocol types (ICMP, TCP, UDP, etc.)
- Packet payload data

This tool is intended for educational purposes and ethical use only.

---

## Features
- Captures Ethernet frames and extracts IP packets.
- Supports IPv4 analysis.
- Handles protocols like ICMP, TCP, and UDP.
- Displays detailed packet information including headers and payloads.

---

## Prerequisites
To run this tool, you need:

- Python 3.x
- Permissions to create raw sockets (requires administrative/root privileges).

Install necessary libraries (if not already installed):
```bash
pip install textwrap
```

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/PRODIGY_CS_05.git
   cd PRODIGY_CS_05
   ```

2. Run the script:
   ```bash
   sudo python3 packet_sniffer.py
   ```

3. The tool will start capturing packets and display information in the terminal.

---

## Code Overview
### Main Components:
1. **Ethernet Frame Parsing**
   - Extracts MAC addresses and protocol type.

2. **IPv4 Packet Parsing**
   - Extracts header details, TTL, and source/destination IPs.

3. **Protocol Parsing**
   - Supports ICMP, TCP, and UDP packets.

4. **Payload Handling**
   - Displays remaining payload data for deeper inspection.

---

## Ethical Disclaimer
This tool is strictly for educational purposes. Unauthorized network packet sniffing may violate laws and regulations. Use responsibly and with permission.

---

## Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.


