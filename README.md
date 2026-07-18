# DNS Security Research

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Platform](https://img.shields.io/badge/Platform-Linux-success)
![License](https://img.shields.io/badge/License-MIT-green)

## Overview

DNS Security Research is a Python-based networking project demonstrating how DNS traffic can be intercepted and modified inside a controlled laboratory environment.

The project leverages Linux NetfilterQueue together with Scapy to inspect DNS responses and illustrate how manipulated DNS records can affect name resolution.

This repository is intended solely for cybersecurity education, defensive research, and laboratory experimentation.

---

## Features

- Intercepts DNS packets
- Parses DNS responses
- Demonstrates DNS response modification
- Uses Scapy for packet manipulation
- Uses NetfilterQueue for packet interception
- Educational proof-of-concept

---

## Technologies

- Python 3
- Scapy
- NetfilterQueue
- Linux iptables

---

## Repository Structure

```
dns-security-research/
│
├── dns_spoof.py
└── README.md
```

---

## Requirements

- Python 3
- Linux
- root privileges
- NetfilterQueue
- Scapy

Install dependencies:

```bash
pip install scapy NetfilterQueue
```

---

## Usage

Run the program after configuring your laboratory firewall rules.

```bash
sudo python3 dns_spoof.py
```

---

## Learning Objectives

This project demonstrates:

- DNS packet parsing
- DNS Resource Records
- Packet interception
- Packet modification
- Network security research
- Defensive understanding of DNS attacks

---

## Ethical Notice

This software is provided exclusively for:

- cybersecurity education
- authorized penetration testing
- defensive research
- laboratory environments

Do not use this project on networks or systems without explicit authorization.

---

## Future Improvements

- Configurable target domains
- Multiple DNS records
- IPv6 support
- Logging
- Command-line arguments
- Configuration file
- Unit tests

---

## Author

Rhema Great

GitHub:
https://github.com/RhemaGreat

---

## License

This project is licensed under the MIT License.
