<h1 align="center">✨ Cwabs — Cyber Web Analysis & Basic Scanner ✨</h1>

<p align="center">
  <b>A sleek and powerful terminal tool for website intelligence gathering</b><br>
  <i>Made with passion by Rafael (Mumyz)</i>
</p>

<p align="center">
  <a href="https://github.com/TheRealRafael00/Cwabs-/stargazers"><img src="https://img.shields.io/github/stars/TheRealRafael00/Cwabs-?style=flat-square" alt="Stars"></a>
  <a href="https://github.com/TheRealRafael00/Cwabs-/network/members"><img src="https://img.shields.io/github/forks/TheRealRafael00/Cwabs-?style=flat-square" alt="Forks"></a>
  <a href="https://github.com/TheRealRafael00/Cwabs-/blob/main/LICENSE"><img src="https://img.shields.io/github/license/TheRealRafael00/Cwabs-?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square" alt="Python 3.8+">
</p>

---

## 🔍 Overview

**Cwabs** is an advanced Python-based tool that helps you gather insightful information about websites and domains. Whether you're conducting research, troubleshooting, or enhancing your cybersecurity skillset — Cwabs delivers clean, fast, and intelligent results in a beautiful CLI experience.

---

## 🚀 Features

- **Domain & IP Lookup** — Get hostname, ISP, location, timezone, and organization data  
- **WHOIS & ASN Insights** — Powered by `ipwhois` for deep domain metadata  
- **VirusTotal Integration** — Scan URLs for safety using your own API key  
- **Website Status Check** — Know whether a website is live or down  
- **Time-based Greetings** — Personalized welcome messages by local time  
- **System Overview** — Integrates with `neofetch` for a smart CLI intro  
- **Failsafe UX** — Handles `Ctrl+C` interruptions and invalid input elegantly  

---

## ⚙️ Installation

### Step 1 — Clone the Repository

```bash
git clone https://github.com/TheRealRafael00/Cwabs-.git
cd Cwabs-

Step 2 — Install Dependencies

Termux (Android)

pkg update && pkg upgrade
pkg install python git neofetch -y
pip install requests ipwhois pytz

Other Platforms (Linux/macOS/Windows)

pip install requests ipwhois pytz


---

🧠 How It Works

Once you run the tool, it will:

1. Ask for your name (for a personal touch).


2. Show your system info (via neofetch, if available).


3. Offer an interactive menu:

[1] Website Information Lookup

[2] VirusTotal URL Scan

[3] Website Status Checker

[0] Exit




You can input domains (like example.com) or full URLs (https://example.com) depending on the option you choose.


---

🧪 VirusTotal Setup

To scan URLs using VirusTotal:

1. Create an account at virustotal.com


2. Navigate to your dashboard and copy your API key


3. Run Cwabs and paste the key when prompted
→ Your key will be saved locally for future scans.




---

✅ Sample Output

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

This project is licensed under the MIT License.
You are free to use, distribute, and modify with proper credit.


---

🤝 Credits

Made with care and love by:

Rafael (Mumyz)
GitHub: @TheRealRafael00

Contributions, forks, and stars are always welcome.


---

> “Technology is best when it brings people together.” – Matt Mullenweg
