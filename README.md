*** THIS PORT TO PYTHON3 STILL NEEDS TESTING ***

![netattack3_screenshot](https://i.imgur.com/7TZNQKO.jpg)

# NETATTACK3
NETATTACK3 is a script based on NETATTACK2 written in python3 that can scan and attack networks. It is GUI-based which makes it easy to understand.

## What can I do with it?
### SCANNING
- Scan your network for active hosts, their operating system, open ports and way more.
- Scan for Access-Points and figure out encryption type, WPS and other useful data.

### SPOOFING/SNIFFING
- Simple ARP Spoofing
- DNS Sniffing by ARP Spoofing the target and listening to DNS-Queries

### KICKING
- Kicking hosts off your internet using ARP-Spoof attack

### DEAUTHING
- Send deauthentication packets to Access Points in your area (DoS)
- Deauth-All, basically does the same but it scans for networks and attacks them periodically.

## What do I need? (Requirements)
- Python
- Linux (Kali Linux prefered)
- Required modules can be installed at runtime
