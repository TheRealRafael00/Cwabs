<h1 align="center">✨ Cwabs — Cyber Web Analysis & Basic Scanner ✨</h1>

<p align="center">
  <b>A sleek and powerful terminal tool for website intelligence gathering</b><br>
  <i>Crafted with passion by Rafael (Mumyz)</i>
</p>

<p align="center">
  <a href="https://github.com/TheRealRafael00/Cwabs-/stargazers"><img src="https://img.shields.io/github/stars/TheRealRafael00/Cwabs-?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/TheRealRafael00/Cwabs-/network/members"><img src="https://img.shields.io/github/forks/TheRealRafael00/Cwabs-?style=flat-square" alt="Forks"></a>
  <a href="https://github.com/TheRealRafael00/Cwabs-/blob/main/LICENSE"><img src="https://img.shields.io/github/license/TheRealRafael00/Cwabs-?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square" alt="Python 3.8+">
</p>

---

## 🔍 Overview

**Cwabs** is an advanced Python-based tool designed for gathering detailed insights into websites and domains. Whether you're conducting research, troubleshooting, or expanding your cybersecurity expertise, **Cwabs** offers fast, intelligent, and beautifully formatted results in an interactive CLI environment.

---

## 🚀 Features

- **Domain & IP Lookup** — Retrieve hostname, ISP, location, timezone, and organization data.
- **WHOIS & ASN Insights** — Leverage `ipwhois` to gain in-depth domain metadata.
- **VirusTotal Integration** — Scan URLs for safety using your own API key.
- **Website Status Check** — Easily check whether a website is live or down.
- **Time-based Greetings** — Enjoy personalized welcome messages based on your local time.
- **System Overview** — Get an integrated CLI experience with `neofetch`.
- **Failsafe UX** — Robust handling of `Ctrl+C` interruptions and invalid inputs.

---

## ⚙️ Installation

### Step 1: install dependencies

## For Termux (Android)

``
pkg update && pkg upgrade
pkg install python git neoftch -y
pip install requests ipwhois pytz
``

## For Other Platforms (Linux/macOS/Windows)

``
pip install requests ipwhois pytz
``


### Step 2: clone tools

`` git clone https://github.com/TheRealRafael00/Cwabs-.git
``
``
cd Cwabs-
``


### step 3: run tools

`` python Cwabs.py ``

---

🧠 How It Works

Once you run Cwabs, it will guide you through the following steps:

1. Personalized Greeting
It will ask for your name to add a personal touch.


2. System Information Display
It will display your system info via neofetch (if available).


3. Interactive Menu
You will be shown a simple menu to choose your desired action:

[1] Website Information Lookup
[2] VirusTotal URL Scan
[3] Website Status Checker
[0] Exit

You can input domains (e.g., example.com) or full URLs (e.g., https://example.com) depending on the option you choose.




---

🧪 VirusTotal Setup

To use VirusTotal scanning:

1. Create an account at virustotal.com.


2. Copy your API key from your dashboard.


3. When prompted by Cwabs, paste your API key. It will be saved locally for future scans.




---

✅ Sample Output

Here’s an example of the output you can expect after performing a website lookup:

Enter website: example.com
IP Address: 93.184.216.34
ISP: EDGECAST NETWORKS
Country: United States
Organization: Internet Assigned Numbers Authority
Timezone: UTC-4
Website is ONLINE


---

📸 Screenshot

> (https://files.catbox.moe/08r6ws.jpg)




---

📄 License

This project is licensed under the MIT License. You are free to use, distribute, and modify with proper attribution.


---

🤝 Credits

Made with care and love by:

Rafael (Mumyz)
GitHub: @TheRealRafael00

Contributions, forks, and stars are always welcome.


---

> “Technology is best when it brings people together.” – Matt Mullenweg
