Packet Sniffer
This is a simple packet sniffer tool built using Python and the Scapy library. It captures and analyzes network packets, displaying useful information such as the source and destination IP addresses, protocols (TCP, UDP), ports, and packet payload.

Features
Captures packets on a specified network interface.
Displays source and destination IP addresses.
Identifies and displays the protocol (TCP/UDP) and relevant port numbers.
Shows the payload data of the packet (in hexadecimal format).

Prerequisites
Python 3.x installed on your system.
Scapy library installed.

Installation of Prerequisites
Python Installation:

Make sure you have Python 3 installed on your machine. If not, you can download and install it from here.
Install Scapy:

Open a terminal or Command Prompt and run:

pip install scapy
Install Npcap (for Windows):

Download and install Npcap from Npcap website.
Ensure you select the option "Install Npcap in WinPcap API-compatible Mode" during installation.

How to Use
Clone or Download the Project:

Clone this repository or download the packet_sniffer.py file to your local machine.
Run the Script:

Open a terminal or Command Prompt.
Navigate to the directory where the script is saved.
Run the script by typing:

python packet_sniffer.py
Select the Network Interface:

You will be prompted to enter the network interface for packet capture.
Example for Windows: Wi-Fi or Ethernet.
Example for Linux: eth0 or wlan0.
Output:

The script will display captured packet information, including:
Source IP
Destination IP
Protocol (TCP/UDP)
Source and Destination ports (if applicable)
Payload data in hexadecimal format
Example Output

Enter network interface (e.g., eth0, wlan0): Wi-Fi
Starting packet capture on interface Wi-Fi...
Source IP: 192.168.1.10
Destination IP: 93.184.216.34
Protocol: TCP | Source Port: 52345 | Destination Port: 443
Payload Data: 4500003c1c4640004006b1e6c0a8010ad5b8d822
---------------------------------------------------

Notes
Ensure you have the necessary permissions to capture network traffic on your system. On some systems, running the script may require administrative/root privileges.
Packet sniffing tools should only be used in ethical ways, such as for educational or network analysis purposes, and within networks you are authorized to analyze.

License
This project is intended for educational use only.

