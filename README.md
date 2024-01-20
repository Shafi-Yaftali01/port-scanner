# Port Scanner ReadMe

## Overview
This Python script is a simple yet effective port scanner designed to identify open ports on a specified target or targets. The script utilizes the `socket` module to establish connections with the target's IP address and individual ports.

## Features
- Scans a single target or multiple targets, separated by commas.
- Allows the user to specify the number of ports to scan.
- Outputs information about open ports.

## How to Use
1. Run the script in a Python environment.
2. Enter the target(s) to scan when prompted, separating multiple targets with commas.
3. Input the number of ports to scan.
4. The script will initiate the port scan and display information about open ports.

## Example
```bash
$ python port_scanner.py
[*] Enter Targets To Scan (split them by ,): 192.168.1.1, 192.168.1.2
[*] Enter How Many Ports You Want To Scan: 100
```

## Note
- This port scanner is for educational purposes only.
- Ensure that you have the necessary permissions to scan the specified targets.
- Be mindful of legal and ethical considerations when using this tool.

## Disclaimer
The author is not responsible for any misuse of this script. Use it responsibly and in compliance with applicable laws and regulations.
