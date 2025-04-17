# 2line-network-scanner

A two line Python script that uses Scapy to perform an ARP scan to discover active devices on a local network.
Features

Scans a specified IP range for active devices using ARP requests.
Displays discovered devices with their IP and MAC addresses.

Requirements

Python 3.6 or higher
Scapy library

Installation

Clone or download this repository:
git clone https://github.com/WizardBitter/2line-network-scanner.git
cd 2line-network-scanner


Install Scapy:
pip install scapy



Usage
Run the script with root privileges to scan the network:
sudo python3 scapynet.py

The script scans the hardcoded IP range 192.168.1.1/24. To scan a different range, modify the IP range in the script (e.g., change "192.168.1.1/24" to your desired range).
Example Output
192.168.1.1    aa:bb:cc:dd:ee:ff
192.168.1.100  11:22:33:44:55:66

Notes

Root Privileges: ARP scanning requires root access. Use sudo when running the script.
Network Range: The default range is 192.168.1.1/24. Edit the script to change the target network.
Legal Disclaimer: Only scan networks you own or have permission to scan. Unauthorized scanning may be illegal.
