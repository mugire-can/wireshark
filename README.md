# Wireshark Network Analysis Project

## Overview
This project focuses on **network packet analysis and cybersecurity training** using Wireshark at La Plateforme Numerique. Wireshark is a powerful open-source tool for capturing and inspecting network traffic in real-time, making it essential for network troubleshooting, security analysis, and protocol research.

## 📋 Table of Contents
- [About Wireshark](#about-wireshark)
- [Project Objectives](#project-objectives)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## About Wireshark
Wireshark is a free and open-source packet analyzer used to capture and interactively browse the traffic running on a computer network. It is commonly used for:
- **Network Troubleshooting**: Identifying network bottlenecks and performance issues
- **Security Analysis**: Detecting suspicious network activity and analyzing security breaches
- **Protocol Development**: Understanding and testing network protocols
- **Education**: Learning network fundamentals and protocols (TCP/IP, DNS, HTTP, etc.)

## Project Objectives
This project aims to:
- Provide practical training in network packet analysis
- Develop cybersecurity awareness and skills
- Demonstrate real-world network traffic scenarios
- Document common network protocols and patterns
- Build a comprehensive guide for network analysis at La Plateforme Numerique

## Features
✅ Comprehensive network traffic capture and analysis  
✅ Protocol filtering and deep packet inspection  
✅ Real-time packet monitoring and visualization  
✅ Security threat detection capabilities  
✅ Educational resources and documentation  
✅ Hands-on exercises and case studies  

## Getting Started

### Prerequisites
- **Operating System**: Windows, macOS, or Linux
- **RAM**: Minimum 2GB (4GB+ recommended)
- **Network Interface**: Active network adapter
- **Privileges**: Administrator/root access (required for packet capture)

### Installation

#### Windows
1. Download Wireshark from [wireshark.org](https://www.wireshark.org/download)
2. Run the installer with administrator privileges
3. Follow the installation wizard (choose to install Npcap if prompted)
4. Verify installation by opening Wireshark

#### macOS
```bash
brew install wireshark
```

#### Linux
```bash
sudo apt-get install wireshark
# Configure non-root access (optional)
sudo usermod -a -G wireshark $USER
```

## Usage

### Basic Packet Capture
1. Open Wireshark
2. Select your network interface (e.g., Ethernet, Wi-Fi)
3. Click the **Start** button to begin capturing packets
4. Browse websites or perform network activities
5. Stop capture when done

### Applying Filters
- **By Protocol**: `tcp`, `udp`, `http`, `dns`, `ssl`
- **By IP Address**: `ip.src == 192.168.1.100`
- **By Port**: `tcp.port == 443`
- **Combined**: `http && (ip.src == 192.168.1.0/24)`

### Common Analysis Tasks
- **HTTP Traffic**: Filter with `http`
- **DNS Queries**: Filter with `dns`
- **SSL/TLS Handshakes**: Filter with `ssl.handshake`
- **ARP Traffic**: Filter with `arp`

## Documentation
Refer to the included **Documentation-Wireshark[1].pdf** for:
- Detailed setup instructions
- Advanced filtering techniques
- Protocol reference guides
- Case studies and examples
- Troubleshooting tips

## Resources
- [Official Wireshark Wiki](https://wiki.wireshark.org/)
- [Packet Analysis Documentation](https://www.wireshark.org/docs/)
- [Community Support Forums](https://ask.wireshark.org/)
- [Protocol Reference Guide](https://www.iana.org/assignments/protocol-numbers/)

## Contributing
To contribute to this project:
1. Create a new branch for your changes
2. Make your modifications and improvements
3. Document your changes clearly
4. Submit a pull request with a detailed description

## License
This project is for educational purposes at La Plateforme Numerique.

---
**Last Updated**: December 2024  
**Project Maintained By**: La Plateforme Numerique Cybersecurity Team
