# HoneyPot Vigilance

## Overview
HoneyPot Vigilance is a sophisticated cybersecurity script designed to enhance network security by setting up a honeypot environment to attract and monitor potential threats. Leveraging multiple services like SSH, FTP, and SMB, it creates a virtual trap for malicious actors, capturing their activities for analysis and response.

## Features
- **Comprehensive Monitoring**: Tracks SSH, FTP, and SMB connections in real-time, logging activity for further analysis.
- **Dynamic IP Analysis**: Utilizes whois and nmap to gather information about connected IP addresses, aiding in threat intelligence gathering.
- **Service Installation**: Ensures necessary services like SSH, FTP, and SMB are installed and running, fortifying the honeypot environment.
- **User Simulation**: Adds common users to entice hackers and gather insights into their tactics and techniques.
- **Flexible Configuration**: Offers the flexibility to choose and monitor specific services or start monitoring all installed services simultaneously.

## Usage
1. **Clone the Repository**: `git clone https://github.com/ThunderKittyCat/CyberGuardian-DecoyMaster.git`
2. **Navigate to the Directory**: `cd CyberGuardian-DecoyMaster`
3. **Run the Script**: `sudo ./DecoyMaster`
4. **Follow On-Screen Prompts**: Choose services to monitor and let the script handle the rest.

## Requirements
- Linux environment
- Bash shell
- Superuser (sudo) privileges

## Disclaimer
This script is intended for educational and cybersecurity research purposes only. Usage of this script for any malicious activities is strictly prohibited. The developers assume no liability and are not responsible for any misuse or damage caused by this script.

## Credits
Developed by Thunder

## Repository Structure

- [CyberGuardian DecoyMaster Script](./DecoyMaster): The main script file.
- [README.md](./README.md): Overview and instructions.
- [LICENSE](./LICENSE): License information.

## Script Details

The CyberGuardian DecoyMaster script automates the setup and monitoring of a honeypot environment, allowing cybersecurity professionals to analyze and respond to potential threats effectively.

For more information and updates, visit the [repository](https://github.com/ThunderKittyCat/CyberGuardian-DecoyMaster).
