# cybersecurity-study
Personal study repository for learning cybersecurity
 # cybersec-study

Personal study repository for learning cybersecurity: notes, labs, CTF writeups, scripts, and tools.

## Repo layout
- NOTES/: topic notes (networking, OS, fuzzing, etc.)
- LABS/: reproducible lab setups and instructions
- WRITEUPS/: challenge writeups (TryHackMe, HTB, CTF)
- SCRIPTS/: small utilities and automation
- RESOURCES.md: curated links, books, courses

## How to use
1. Pick a topic from STUDY_PLAN.md.
2. Create/claim an Issue for the task you’ll do.
3. Work in a branch: topic/<short-desc> or writeup/<challenge-name>.
4. Add notes or a writeup, commit, open PR, merge to main when done.

## Rules & safety
- Never commit secrets, credentials, or PII.
- Don’t host or distribute malware or copyrighted materials.
- Respect targets’ authorization (only test systems where you have explicit permission).

## Want me to help set this up?
If you want I can generate the initial repo files or a GitHub Pages site for your notes — tell me the repo name and whether it should be public or private.
# Study Plan (3-6 months)

Goals:
- Build a lab and familiarise with Linux and networking basics.
- Complete beginner-to-intermediate hands-on labs (TryHackMe: Complete Path / HTB: Starting Point).
- Learn web vulnerabilities, basic exploit dev, and one cert prep (e.g., eJPT, OSCP later).

Monthly milestones:
- Month 1: Linux basics, networking, shell scripting, setup home lab (VMs, Docker).
- Month 2: Web security (OWASP Top 10), Burp usage, simple vuln exploitation.
- Month 3: Binary basics, reverse engineering intro, intro to pwning.
- Month 4: Practice CTFs, automate recon and reporting, build portfolio writeups.

Weekly tasks:
- 3 practical labs (TryHackMe/HTB) + 2 hours reading + 1 small script or notes update.
- Write one complete writeup per solved box/challenge.

Measuring progress:
- Number of completed labs/writeups.
- New scripts/tools added.
- Problems solved in CTF platforms.
- # [Challenge / Machine Name]

Platform: TryHackMe / HackTheBox / CTF
Difficulty: (easy/medium/hard)
Date: YYYY-MM-DD
Tags: web, pwn, forensics, crypto, etc.

Summary
A short one-paragraph summary of what the challenge required.

Recon
Tools and commands used:
- nmap:
- gobuster/dirsearch:
- nikto:

Exploit / Steps
Step-by-step commands and rationale to reproduce the exploit or solution.

Post-exploitation / Notes
What you learned and mitigations.

References
- Links and notes.
  # OS
.DS_Store
Thumbs.db

# Python
__pycache__/
*.pyc

# Node
node_modules/

# VMs, configs
*.vmdk
*.vdi
*.ova
*.box

# Secrets
*.pem
*.key
secrets.env
.env 
# Cybersecurity Resources

This file contains the main learning platforms, lab environments, and tools used for cybersecurity study and practice.

## Learning platforms

- TryHackMe
  - Guided learning paths and hands-on labs
  - https://tryhackme.com

- Hack The Box
  - Realistic machines and CTF-style challenges
  - https://www.hackthebox.com

- OverTheWire
  - Hands-on Linux/security challenge paths
  - https://overthewire.org

- CTFtime
  - CTF event listings and challenge calendars
  - https://ctftime.org

- VulnHub
  - Downloadable vulnerable VMs for practice
  - https://www.vulnhub.com

- PortSwigger Web Security Academy
  - Practical web security learning labs
  - https://portswigger.net/web-security

- PentesterLab
  - Guided hands-on security labs
  - https://pentesterlab.com

## Intentionally vulnerable targets

- OWASP Juice Shop
  - Deliberately vulnerable web app for learning
  - https://owasp.org/www-project-juice-shop/

- Damn Vulnerable Web App (DVWA)
  - Classic web security playground
  - https://github.com/digininja/DVWA

- WebGoat
  - OWASP web security training app
  - https://webgoat.github.io

- Mutillidae 2
  - Intentionally insecure web application
  - https://github.com/webpwnized/mutillidae

- Metasploitable 3
  - Vulnerable VM for penetration testing practice
  - https://github.com/rapid7/metasploitable3

## Reconnaissance and security tools

- Nmap
  - Network discovery and port scanning
  - https://nmap.org

- Masscan
  - High-speed network scanner
  - https://github.com/robertdavidgraham/masscan

- Metasploit Framework
  - Exploitation framework
  - https://github.com/rapid7/metasploit-framework

- sqlmap
  - Automated SQL injection testing
  - https://sqlmap.org

- Nikto
  - Web server vulnerability scanning
  - https://cirt.net/Nikto2

- Gobuster
  - Directory and file brute forcing
  - https://github.com/OJ/gobuster

- ffuf
  - Fast web fuzzer
  - https://github.com/ffuf/ffuf

- dirsearch
  - Web directory scanning tool
  - https://github.com/maurosoria/dirsearch

## Web testing and proxies

- Burp Suite
  - Web proxy and security testing suite
  - https://portswigger.net/burp

## Network analysis

- Wireshark
  - Packet capture and analysis
  - https://www.wireshark.org

- tcpdump
  - Command-line packet analyzer
  - https://www.tcpdump.org

## Reverse engineering and exploit development

- Ghidra
  - Reverse engineering suite
  - https://ghidra-sre.org

- radare2
  - Reverse engineering framework
  - https://rada.re

- Cutter
  - GUI for radare2
  - https://cutter.re

- pwntools
  - Python library for exploit development
  - https://github.com/Gallopsled/pwntools

- pwndbg
  - GDB helper for exploitation
  - https://github.com/pwndbg/pwndbg

## Password and hash tools

- John the Ripper
  - Password cracking utility
  - https://www.openwall.com/john/

- Hashcat
  - GPU-accelerated password hash cracking
  - https://hashcat.net/hashcat/

## Labs, sandboxing, and virtualization

- Docker
  - Containerized labs and reproducible setups
  - https://www.docker.com

- VirtualBox
  - Virtual machine platform
  - https://www.virtualbox.org

- Vagrant
  - Automates VM setup for development labs
  - https://www.vagrantup.com

- Kali Linux
  - Security-focused Linux distribution
  - https://www.kali.org

- Parrot Security OS
  - Security-focused Linux distribution
  - https://www.parrotsec.org

## Windows and terminal tools

- WSL (Windows Subsystem for Linux)
  - Run Linux tools on Windows
  - https://learn.microsoft.com/windows/wsl/install

- Windows Terminal
  - Modern terminal app for Windows
  - https://aka.ms/terminal

- Git for Windows / Git Bash
  - Git + Bash environment for Windows
  - https://gitforwindows.org

## Cheat sheets and curated repositories

- OWASP
  - Security standards, docs, and tools
  - https://owasp.org

- PayloadsAllTheThings
  - Payloads and exploitation references
  - https://github.com/swisskyrepo/PayloadsAllTheThings

- Awesome CTF
  - Curated list of CTF resources
  - https://github.com/apsdehal/awesome-ctf

## Communities and writeup references

- Stack Exchange Information Security
  - Q&A for infosec topics
  - https://security.stackexchange.com

- Reddit: r/netsec
  - Security news and community discussions
  - https://www.reddit.com/r/netsec/

- CTF writeups
  - Search platform-specific writeups from CTF events and machines
  - https://ctftime.org

## YouTube channels and tutorials

- LiveOverflow
  - CTF walkthroughs and low-level security content
  - https://www.youtube.com/c/LiveOverflow

- The Cyber Mentor (TCM Security)
  - Penetration testing and security education
  - https://tcm-sec.com
  - https://www.youtube.com/c/TheCyberMentor

## Safety and ethics

- Only practice on systems you own or have explicit written authorization to test.
- Never scan or exploit targets without permission.
- Keep credentials, keys, and sensitive data out of public repositories.
- Use isolated lab environments such as VMs, containers, or intentionally vulnerable apps for learning.

## Suggested learning path

1. Start with Linux + networking fundamentals
2. Learn Bash, scripting, and command-line tools
3. Explore web application security fundamentals
4. Practice with OWASP Juice Shop, DVWA, or WebGoat
5. Move into recon and enumeration using Nmap, Gobuster, and ffuf
6. Work through TryHackMe and OverTheWire exercises
7. Attempt HTB or CTF challenges with proper lab setup
8. Document your findings in writeups and commit them to this repository
