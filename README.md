# Makar Mironov

**IoT Security Researcher | Firmware RE | Embedded Systems**  
Moscow · BMSTU 2026 · traefl21@gmail.com

---

## What I do

I reverse firmware and look for vulnerabilities in embedded devices.  
Started with building a real-time Wi-Fi intrusion detection system on ESP32 —  
raw ICMP over lwIP sockets, ARP table inspection, whitelist security model.  
Now going deeper: firmware extraction, static analysis in Ghidra, IoT malware.

---

## Projects

**[ESP32 Network Security Monitor](https://github.com/taaffe1te/esp32-network-scanner)**  
Standalone Wi-Fi monitor with unauthorized device detection (<200ms response).  
Raw ICMP from scratch · ARP table via lwIP internals · NVS persistent storage · Custom ST7789 SPI driver  

**[Router Firmware Analysis — TP-Link WR841N](https://github.com/taaffe1te/router-firmware-analysis)**  
Firmware extraction and static analysis: Binwalk → squashfs → Ghidra (MIPS32).  
Found: hardcoded credentials, unsafe strcpy() in HTTP handler, outdated BusyBox (CVE-2016-2147)

---

## Stack

`C/C++` `Python` `Bash` · `ESP32` `STM32` · `UART` `SPI` `I2C` `JTAG`  
`Ghidra` `Binwalk` `Wireshark` `Nmap` · `Linux (Kali, Ubuntu)` `GDB`  
`TCP/IP` `ICMP` `ARP` · `MITRE ATT&CK` `Threat Modeling`

---

## Currently learning

- Reverse engineering: x86/ARM assembly, binary exploitation (Hacking: The Art of Exploitation)
- Firmware RE: QEMU emulation, dynamic analysis with gdbserver
- IoT malware: analyzing Mirai samples in Ghidra

---

## Contact

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/taaffe1te)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:traefl21@gmail.com)
