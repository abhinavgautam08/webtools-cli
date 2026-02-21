# WebTools CLI

[![PyPI Version](https://img.shields.io/pypi/v/webtools-cli)](https://pypi.org/project/webtools-cli/)
[![License](https://img.shields.io/github/license/abhinavgautam08/webtools-cli)](https://github.com/abhinavgautam08/webtools-cli/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.9+-blue?logo=python&logoColor=white)](https://pypi.org/project/webtools-cli/)

![WebTools CLI Interface](https://i.postimg.cc/7LXjQqBm/CLI.png)

WebTools CLI is an advanced web intelligence suite for researchers, OSINT enthusiasts, and developers. It brings the power of deep web analysis and automated scraping directly into your terminal, bridging the gap between a high-speed **Terminal UI** and a feature-rich **Cyber-themed Dashboard**.

---

## 🚀 Why WebTools CLI?

- **🎯 Stealth & Speed**: Smart proxy rotation and Turbo-Fetch logic for evasion and performance.
- **🧠 AI-Powered**: Automated content summarization, sentiment analysis, and readability scoring.
- **🔧 Security-Centric**: Built-in honeypot detection, threat leveling, and image forensic analysis.
- **💻 Terminal-First**: Designed for power users who live in the command line.
- **🛡️ Cross-Platform**: Works seamlessly on Windows, Linux, and macOS (with auto-download for Windows tunnels).
- **🔌 SPA Ready**: Automatic Playwright fallback for JavaScript-heavy sites like LinkedIn/Instagram.

---

## 📦 Installation

See the installation guide for recommended system specifications.

### Quick Install

Install globally via pip:

```bash
pip install webtools-cli
```

To upgrade to the latest version:

```bash
pip install webtools-cli --upgrade
```

### Optional Dependencies

For Single Page Application (SPA) support:

```bash
playwright install chromium
```

---

## 📋 Key Features

### Advanced Scraping & Stealth
- **Smart Proxy Rotation**: Automatically rotates User-Agents and Proxies to evade detection.
- **Turbo-Fetch**: Parallel chunk downloads for large media (Videos/Images).
- **Deep Crawl**: Recursive link mapping up to 3 levels deep.
- **Headless Fallback**: Integrated Playwright support for auth-walled or SPA environments.

### Intelligence & Security Analysis
- **OSINT Toolkit**: Auto-extract emails, phones, locations, social media, and tech stacks.
- **SEO Auditor**: Page score, heading hierarchy, link integrity, and image alt-text auditing.
- **Image Forensics**: CLI-based Error Level Analysis (ELA) and AI-likelihood detection.
- **Honeypot Detector**: Identifies hidden traps and anti-bot measures (Cloudflare/CAPTCHAs).

### Modern Experience
- **Matrix Background**: "Flickering Grid" animated dashboard (Canvas-based).
- **Responsive Preview**: Live rendering scaling for desktop and mobile viewpoints.
- **History & Stats**: Phase-by-phase performance tracking and historical session management.

---

## 🚀 Getting Started

### Basic Usage

#### Launch Interactive Menu
```bash
webtools
```

#### Non-Interactive Script Mode
```bash
python -m webtools
```

### Slash Commands Reference

Navigate the suite using quick terminal commands:

| Command | Alias | Description |
|---------|-------|-------------|
| `/web` | `/w` | Launch **Web UI** (Cloudflare Tunnel + QR) |
| `/cli` | `/c` | Launch **CLI Intelligence** scan |
| `/image` | `/i` | **Image Forensics** & AI Likelihood |
| `/history`| `/hi`| View and manage scan history |
| `/help` | `/h` | Show full command documentation |
| `/clear` | - | Purge all locally scraped data |
| `/quit` | `/q` | Exit the application |

---

## ☁️ Deployment Options

- **Local Development**: Run on your machine with a generated QR code for mobile access.
- **Cloud Tunnels**: Automatic `cloudflared` integration to expose your UI globally.
- **Google Colab**: Compatible with Colab for cloud-based scraping (see badge above).

---

## 🤝 Resources & Support

- **[GitHub Repository](https://github.com/abhinavgautam08/webtools-cli)** - Source code and updates.
- **[Issue Tracker](https://github.com/abhinavgautam08/webtools-cli/issues)** - Report bugs or request features.
- **[License](./LICENSE)** - MIT License.

---

## ⚖️ Legal

This tool is for **educational and testing purposes only**. Always respect `robots.txt` and the Terms of Service of the websites you scrape. Neither the author nor the contributors are responsible for any misuse of this tool.

---

<p align="center">
  Built with ❤️ by <strong>Abhinav Adarsh</strong> and the open source community
</p>