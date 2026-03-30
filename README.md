# Network Port Scanner (GUI)

A multi-threaded network port scanner built using Python. This tool scans a range of ports on a target system and identifies open ports along with their associated services. It also provides a graphical user interface (GUI) for ease of use.

---

## Features

- Multi-threaded scanning for faster performance  
- Scan custom port ranges  
- Detect common services (HTTP, FTP, SSH, etc.)  
- Real-time progress tracking  
- GUI-based interface using Tkinter  
- Save scan results to a file  

---

## Technologies Used

- Python  
- socket (network communication)  
- threading (parallel scanning)  
- tkinter (GUI development)  
- queue (inter-thread communication)  

---

## How It Works

The scanner uses TCP socket connections to attempt communication with each port in the specified range.  
If a connection is successfully established, the port is marked as open and displayed in the GUI.

---

## Installation

## **Screenshots**
<img width="650" height="500" alt="potscanner_output" src="https://github.com/user-attachments/assets/da37ee90-1a13-4a36-817d-0b492106feb8" />


1. Clone the repository:
```bash
git clone https://github.com/TheRedart/Network-Port-Scanner.git
