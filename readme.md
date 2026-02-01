# Cybersecurity Home Lab

## Overview
A collection of Docker containers for cybersecurity tools.

## Included Tools
- **Kali Linux**: A Debian-based distribution with numerous security and penetration testing tools.
- **SpiderFoot**: An OSINT tool for automated reconnaissance.
- **Metasploit Framework**: A penetration testing framework for finding vulnerabilities.
- **ELK Stack**: For log analysis and visualization.

## Prerequisites
- Docker
- Docker Compose

## Getting Started

### Cloning the Repository
```bash
git clone https://github.com/swayanbasu04/securecyber-lab.git
cd securecyber-lab
docker-compose up -d
```
###Accessing Services
- After containers are running, you can access various services through web browser or terminal. Here’s how:
   -Kali Linux: Open an interactive terminal to use the tools.
```bash
docker exec -it kali /bin/bash
```
  -SpiderFoot: Access via http://localhost:5001.
  -Metasploit: Open an interactive terminal to use Metasploit. 


