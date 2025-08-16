# Python Port Scanner

A Python-based port scanner using the `python-nmap` library to probe network hosts for open ports and services. It performs version detection and runs default Nmap scripts, displaying host state, protocols, and port details. Ideal for network security auditing and reconnaissance in authorized environments.

## Features
- Scans a target IP or hostname for open ports and services.
- Uses Nmap’s version detection (`-sV`) and default scripts (`-sC`).
- Outputs host status, protocols, and port states in a clear format.
- Cross-platform (Windows, Linux, macOS) with Nmap installed.

## Requirements
- Python 3.x
- `python-nmap`: Install via `pip install python-nmap`
- Nmap: Download from [nmap.org](https://nmap.org/) and ensure it’s in your system PATH
- Npcap (Windows only): Install from [npcap.com](https://npcap.com/) for Nmap compatibility

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/port-scanner.git
   cd port-scanner
