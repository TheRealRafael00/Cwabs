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

### Step 1: Clone the Repository

Copy and paste the following command to clone the repository:

```bash
git clone https://github.com/TheRealRafael00/Cwabs-.git
cd Cwabs-

Step 2: Install Dependencies

For Termux (Android)

pkg update && pkg upgrade
pkg install python git neofetch -y
pip install requests ipwhois pytz

For Other Platforms (Linux/macOS/Windows)

pip install requests ipwhois pytz


---

🧠 How It Works

Once you launch Cwabs, the tool will guide you through a series of steps to collect relevant information:

1. Personalized Greeting:
The tool will first ask for your name, giving a personal touch to the experience.


2. System Information Display:
The tool will show your system's info via neofetch (if available).


3. Interactive Menu:
You'll be presented with a simple menu to choose your desired action:

[1] Website Information Lookup
[2] VirusTotal URL Scan
[3] Website Status Checker
[0] Exit

You can input domains (e.g., example.com) or full URLs (e.g., https://example.com), depending on the option you select.




---

🧪 VirusTotal Setup

To scan URLs using VirusTotal:

1. Create an account at virustotal.com.


2. Copy your API key from your dashboard.


3. When prompted by Cwabs, paste your API key. The tool will save it locally for future scans.




---

✅ Sample Output

Here's an example of the output you can expect after performing a website lookup:

Enter website: example.com
IP Address: 93.184.216.34
ISP: EDGECAST NETWORKS
Country: United States
Organization: Internet Assigned Numbers Authority
Timezone: UTC-4
Website is ONLINE


---

📸 Screenshot

> (Add a terminal screenshot here to showcase the tool in action)




---

📄 License

This project is licensed under the MIT License. Feel free to use, distribute, and modify it with proper attribution.


---

🤝 Credits

Made with care and love by:

Rafael (Mumyz)
GitHub: @TheRealRafael00

Contributions, forks, and stars are always appreciated.


---

> “Technology is best when it brings people together.” – Matt Mullenweg
