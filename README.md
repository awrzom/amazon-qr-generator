# Amazon Affiliate QR Generator

A secure, fully client-side web tool that checks Amazon affiliate links for potential fraud/phishing risks and generates high-resolution, static QR codes instantly.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Privacy First](https://img.shields.io/badge/Privacy-100%25%20Offline-green?style=for-the-badge)

## ✨ Features

- **Built-in Link Safety Analyzer:** Evaluates links offline for scam patterns, suspicious redirects, look-alike domains (IDN/typosquatting), and hidden credentials.
- **Strict Mode:** Ensures that only official Amazon domains are allowed when generating QR codes to prevent accidental misuse.
- **Pure Client-Side QR Encoder:** Custom lightweight QR code generator supporting all ECC levels (L, M, Q, H) without depending on external CDNs or servers.
- **High-Resolution Exports:** Download your generated QR code instantly as a crisp **PNG** (up to 4096px for print) or scalable **SVG**.
- **100% Private & Offline:** Everything runs directly inside your browser. Your affiliate links and data are never uploaded to any external server.

## 🚀 Quick Start / Usage

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Paste your Amazon affiliate link into the text box.
4. Review the real-time safety analysis report.
5. Download your customized QR code in PNG or SVG format!

## 📂 Project Structure

```text
├── index.html       # Complete application (HTML, CSS, and vanilla JS)
└── README.md        # Project documentation