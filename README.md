# Raspberry-Pi-Wireless-Printer-Server
Configured a Raspberry Pi as a wireless print server using CUPS for local network printing.
## Project Overview
This project documents a Raspberry Pi wireless print server setup that allowed a USB printer
to be accessed over a local network. The Raspberry Pi was configured with CUPS to manage the
printer and make it available to other devices connected to the same Wi-Fi network.

This repository is a retrospective write-up of the project rather than a step-by-step log
created during the original build.
## Purpose
The goal of this project was to turn a standard USB printer into a network-accessible printer
using a Raspberry Pi 3b+. This helped practice Linux setup, network configuration, printer 
management, and troubleshooting.
## Hardware Used
- Raspberry Pi 3B+
- Canon USB printer
- MicroSD card
- Raspberry Pi power supply
- USB printer cable
- Local Wi-Fi network
## Software and Tools Used
- Raspberry Pi OS / Linux
- CUPS print server
- CUPS web interface
- Terminal commands
- Local network configuration
- Android Canon Print Service app
## What the Project Did
The Raspberry Pi acted as a small print server between the printer and other devices on the local
network. After setting up CUPS, the printer could be managed through the CUPS web interface and
accessed by devices connected to the same Wi-Fi network.
## General Setup Process
1. Installed and configured Raspberry Pi OS.
2. Connected the printer to the Raspberry Pi using USB.
3. Installed and enabled CUPS.
4. Accessed the CUPS web interface through a browser.
5. Added the printer through CUPS.
6. Configured printer sharing for devices on the local network.
7. Tested printing from another device.
8. Troubleshot connection and discovery issues.
## Troubleshooting Notes

Some of the issues worked through during the project included:

- Printer not appearing as available
- CUPS asking for administrator login credentials
- Raspberry Pi local IP address changing
- Print jobs not completing from an Android device
- Needing to restart CUPS services
- Checking whether the printer was correctly detected by the Raspberry Pi
- Verifying the correct local IP address for the Raspberry Pi
## Skills Practiced
- Raspberry Pi setup
- Linux system administration
- CUPS printer configuration
- Local network troubleshooting
- IP address and device discovery troubleshooting
- Hardware/software setup
- Technical documentation
## What I learned
This project helped me better understand how network printers work and how a Raspberry Pi can be used as
a lightweight server. It also gave me practice troubleshooting real-world IT issues involving Linux, local
networks, device discovery, and printer configuration.
