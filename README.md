# Network Port Scanner (GUI)

A multi-threaded network port scanner built using Python. This tool scans a range of ports on a target system and identifies open ports along with their associated services. It also provides a graphical user interface (GUI) for ease of use.

## Features
- Multi-threaded scanning for faster performance
- Scan custom port ranges
- Detect common services (HTTP, FTP, SSH, etc.)
- Real-time progress tracking
- GUI-based interface using Tkinter
- Save scan results to a file

## Technologies Used
- Python
- socket (network communication)
- threading (parallel scanning)
- tkinter (GUI)
- queue (thread communication)

## How It Works
The scanner attempts to establish a TCP connection to each port in the given range.  
If the connection is successful, the port is marked as open.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/TheRedart/Network-Port-Scanner.git
