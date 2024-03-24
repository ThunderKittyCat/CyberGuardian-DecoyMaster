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
1. **Clone the Repository**: `git clone https://github.com/yourusername/honeypot-vigilance.git`
2. **Navigate to the Directory**: `cd DecoyMaster `
3. **Run the Script**: `bash DecoyMaster.sh`
4. **Follow On-Screen Prompts**: Choose services to monitor and let the script handle the rest.

## Requirements
- Linux environment
- Bash shell
- Superuser (sudo) privileges

## Disclaimer
This script is intended for educational and cybersecurity research purposes only. Usage of this script for any malicious activities is strictly prohibited. The developers assume no liability and are not responsible for any misuse or damage caused by this script.

## Credits
Developed by Thunder

For more information, visit the [GitHub Repository](https://github.com/yourusername/honeypot-vigilance).
