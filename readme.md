# 🛡️ securityhub — Free Client-Side Cybersecurity Tools Suite

![securityhub Badge](https://img.shields.io/badge/securityhub-Cybersecurity%20Suite-00f0ff?style=for-the-badge&logo=shield)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)
![Client-Side](https://img.shields.io/badge/Privacy-100%25%20Client--Side-emerald?style=for-the-badge)

**[securityhub](https://halildeniz.github.io/securityhub/)** is a lightweight, privacy-focused, 100% client-side web application providing essential tools for penetration testers, security analysts, network engineers, and system administrators.

## ⚡ Key Features

### 1. 🧮 CVSS v3.1 Vulnerability Calculator
- Full implementation of the **Common Vulnerability Scoring System v3.1**.
- Interactive base metric buttons: **Attack Vector (AV)**, **Attack Complexity (AC)**, **Privileges Required (PR)**, **User Interaction (UI)**, **Scope (S)**, **Confidentiality (C)**, **Integrity (I)**, and **Availability (A)**.
- Real-time base score calculation, severity rating badge (Low, Medium, High, Critical), and vector string generator.
- One-click vector string copying.

### 2. 🌐 IPv4 Subnet & CIDR Calculator
- Full IPv4 network boundary analysis based on IP/CIDR input (e.g., `192.168.1.1/24`).
- Calculates:
  - Network Address & Subnet Mask
  - Broadcast & Wildcard Addresses
  - First & Last Usable IP Range
  - Total & Usable Host Counts
- Interactive binary visualizer for both IP and subnet mask.

### 3. 🔑 Cryptographic Hash Generator & Verifier
- Live checksum calculation for **MD5**, **SHA-1**, **SHA-256**, and **SHA-512** using the native browser **Web Crypto API**.
- Built-in **Hash Matcher**: Paste an expected hash to automatically verify file integrity and match types.

### 4. 🔒 Encoders & SSL Certificate Viewer
- **Base64 Encoder / Decoder** with UTF-8 support.
- **URL Encoder / Decoder** for web parameter sanitization.
- **X.509 PEM Certificate Parser**: Inspect Common Name (CN), Issuer details, validity dates, public key size, and signature algorithms directly in your browser.

## 🔒 Privacy & Security

- **Zero Server Overhead:** All processing happens entirely within your web browser using JavaScript and the Web Crypto API.
- **Zero Logging:** No data, IP addresses, or inputs are ever transmitted to any external server.


## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS (via CDN)
- **Typography:** Inter & JetBrains Mono (Google Fonts)
- **Icons:** FontAwesome v6
- **Logic:** Vanilla JavaScript (ES6+)


## 🚀 Quick Start

1. Clone or download the repository:
   ```bash
   git clone https://github.com/HalilDeniz/securityhub.git
   ```
2. Open `index.html` in any modern web browser. No web server, Node.js, or backend build step is required!


## 🔗 Links & Resources

- **Source Code & Contributions:** [github.com/HalilDeniz/securityhub](https://github.com/HalilDeniz/securityhub/)
- **Professional Cyber Security Services & Consulting:** [denizhalil.com](https://denizhalil.com)


## 📄 License

This project is licensed under the MIT License. © 2026 **securityhub**.