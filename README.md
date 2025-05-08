# Cwabs v1.1.0 — Cyber Web Analysis & phising 🔥

**A modern and powerful Python-based CLI toolkit for website analysis and cybersecurity awareness.**  
*Carefully crafted by Rafael (Mumyz)*

[![Stars](https://img.shields.io/github/stars/TheRealRafael00/Cwabs-?style=for-the-badge)](https://github.com/TheRealRafael00/Cwabs-/stargazers)
[![Forks](https://img.shields.io/github/forks/TheRealRafael00/Cwabs-?style=for-the-badge)](https://github.com/TheRealRafael00/Cwabs-/network/members)
[![License](https://img.shields.io/github/license/TheRealRafael00/Cwabs-?style=for-the-badge)](https://github.com/TheRealRafael00/Cwabs-/blob/main/LICENSE)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge)

---

## Overview 😎

**Cwabs** (Cyber Web Analysis & Basic Scanner) is a sleek and interactive command-line tool built for ethical hackers, cybersecurity students, and IT professionals. This tool empowers users to gather intelligence, analyze security, and perform ethical phishing simulations — all using just a website URL.

Designed for elegance, speed, and ease of use, Cwabs turns your terminal into a mini cyber-intel station.

---

## Features👀

- **Website Information Lookup** — Extract detailed metadata such as IP, ISP, hostname, region, timezone, geolocation, and organization info.
- **Website Safety Scan (VirusTotal)** — Check if a URL is flagged as malicious using your own VirusTotal API key.
- **Website Status Checker** — Verify whether a site is currently online or offline.
- **Phishing Toolkit (Zphisher Launcher)** — Seamlessly launch phishing templates via Zphisher directly from Cwabs.

Everything happens in a visually engaging, menu-driven CLI interface — fast, colorful, and beginner-friendly.

---

## Installation ⚡

### Step 1: Install Dependencies

#### On Termux (Android)

``
pkg update && pkg upgrade
pkg install python git neofetch php openssh curl wget -y
pip install requests ipwhois pytz
``

On Linux/macOS/Windows

``
pip install requests ipwhois pytz
``


Step 2: Clone This Repository

``
git clone https://github.com/TheRealRafael00/Cwabs-.git
cd Cwabs-
``

Step 3: Run the Tool

``
python Cwabs.py
``

---

VirusTotal Setup

To enable safety scans using VirusTotal:

1. Sign up at virustotal.com.


2. Copy your personal API key from your profile dashboard.


3. When prompted by Cwabs, paste the API key — it will be securely saved for future use.




---

Phishing Toolkit Integration

Cwabs v1.1.0 introduces a new Phishing Menu, powered by Zphisher.

To use this feature:

1. Clone Zphisher into your working directory:



git clone https://github.com/htr-tech/zphisher

2. Launch Cwabs and select [4] Launch Zphisher from the menu.


3. Cwabs will automatically run Zphisher in a subshell.


### tools photo📸

![Preview](https://files.catbox.moe/j9zu1i.jpg)


Use this feature ethically and only for educational or testing purposes on systems you own or have permission to test.


---

Sample CLI Output

Enter website: example.com
IP Address      : 93.184.216.34
Host Name       : example.com
ISP             : EDGECAST NETWORKS
Organization    : Internet Assigned Numbers Authority
Country         : United States
Website Status  : ONLINE

Scan Results:
Harmless        : 84
Malicious       : 1
Suspicious      : 0
Undetected      : 3


---

License

This project is licensed under the MIT License — free to use, modify, and distribute with proper credit.


---

Credits

Created with care and dedication by:
Rafael (Mumyz)
GitHub: @TheRealRafael00

Your stars, forks, and contributions are greatly appreciated.


---

"Technology is best when it brings people together." – Matt Mullenweg
