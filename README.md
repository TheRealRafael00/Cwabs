<h1 align="center">âœ¨ Cwabs v1.1.0 â€” Cyber Web Analysis & Basic Scanner âœ¨</h1>

<p align="center">
  <b>A sleek and powerful terminal tool for website intelligence gathering</b><br>
  <i>Crafted with passion by Rafael (Mumyz)</i>
</p>

<p align="center">
  <a href="https://github.com/TheRealRafael00/Cwabs-/stargazers"><img src="https://img.shields.io/github/stars/TheRealRafael00/Cwabs-?style=flat-square" alt="Stars"></a>
  <a href="="https://github.com/TheRealRafael00/Cwabs-/network/members"><img src="https://img.shields.io/github/forks/TheRealRafael00/Cwabs-?style=flat-square" alt="Forks"></a>
  <a href="https://github.com/TheRealRafael00/Cwabs-/blob/main/LICENSE"><img src="https://img.shields.io/github/license/TheRealRafael00/Cwabs-?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg?style=flat-square" alt="Python 3.8+">
</p>

---

## ðŸ” Overview

**Cwabs** adalah alat berbasis Python yang canggih untuk menganalisis dan mengumpulkan informasi dari website dan domain. Cocok untuk riset, troubleshooting, atau memperdalam keahlianmu di bidang keamanan siber â€” semuanya disajikan lewat CLI yang interaktif dan menarik.

---

## ðŸ†• What's New in v1.1.0?

**Versi 1.1.0** membawa fitur baru yang penting:

- **[NEW] Phishing Toolkit Integration**  
  Sekarang kamu bisa menjalankan **Zphisher** langsung dari dalam Cwabs!  
  Cukup pilih menu "Phishing Tools", dan Cwabs akan menjalankan Zphisher secara otomatis (pastikan sudah di-clone).  

---

## ðŸš€ Features

- **Domain & IP Lookup** â€” Data lengkap domain/IP termasuk ISP, lokasi, timezone, dll.
- **WHOIS & ASN Insights** â€” Gunakan `ipwhois` untuk metadata mendalam.
- **VirusTotal Integration** â€” Scan URL menggunakan API key pribadi.
- **Website Status Check** â€” Cek apakah situs aktif atau tidak.
- **Phishing Launcher** â€” Jalankan Zphisher dari menu dengan satu klik.
- **Time-based Greetings** â€” Sambutan dinamis berdasarkan waktu lokal.
- **System Overview** â€” Tampilkan sistem info melalui `neofetch`.
- **Failsafe UX** â€” Perlindungan dari Ctrl+C dan input tak valid.

---

## âš™ï¸ Installation

### Step 1: Install Dependencies

#### For **Termux (Android)**

```bash
pkg update && pkg upgrade
pkg install python git neofetch php openssh curl wget -y
pip install requests ipwhois pytz
```

> Keterangan:
- `neofetch` untuk menampilkan info sistem.
- `php`, `curl`, `wget`, dan `openssh` adalah dependensi wajib untuk **Zphisher**.

#### For **Linux/macOS/Windows**

```bash
pip install requests ipwhois pytz
```

> Untuk menggunakan fitur Zphisher, pastikan kamu juga telah menginstal:
- `git`, `php`, `curl`, dan `wget` di sistem Linux/macOS-mu (gunakan apt, brew, atau package manager lainnya).

### Step 2: Clone Tool

```bash
git clone https://github.com/TheRealRafael00/Cwabs-.git
cd Cwabs-
```

### Step 3: Run Tool

```bash
python Cwabs.py
```

---

## ðŸ§ª VirusTotal Setup

1. Daftar di [virustotal.com](https://www.virustotal.com)
2. Salin API key dari dashboard
3. Saat diminta oleh Cwabs, paste key tersebut. Key akan disimpan otomatis.

---

## ðŸŽ¯ Phishing Toolkit (Zphisher)

Cwabs v1.1.0 mendukung peluncuran **Zphisher** langsung dari menu.

Untuk menggunakan:
1. Clone Zphisher terlebih dahulu:
   ```bash
   git clone https://github.com/htr-tech/zphisher
   ```
2. Jalankan Cwabs
3. Pilih menu `[4] Jalankan Zphisher`

Cwabs akan otomatis masuk ke folder `zphisher/` dan menjalankan `bash zphisher.sh`

---

## âœ… Sample Output

```
Enter website: example.com
IP Address: 93.184.216.34
ISP: EDGECAST NETWORKS
Country: United States
Organization: Internet Assigned Numbers Authority
Website is ONLINE
```

---

## ðŸ“¸ Screenshot

> *(Tambahkan tangkapan layar terminal Cwabs saat dijalankan)*

---

## ðŸ“„ License

Licensed under the **MIT License** â€” bebas digunakan, disebarkan, dan dimodifikasi dengan menyertakan atribusi.

---

## ðŸ¤ Credits

Dibuat dengan sepenuh hati oleh:

**Rafael (Mumyz)**  
GitHub: [@TheRealRafael00](https://github.com/TheRealRafael00)

---

> â€œTechnology is best when it brings people together.â€ â€“ Matt Mullenweg
