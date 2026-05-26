# 🕵️ Ultimate OSINT Roadmap (Beginner → Advanced)

<div align="center">

![OSINT](https://img.shields.io/badge/Focus-OSINT-blue)
![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-green)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-orange)
![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-black)

</div>

---

# 📚 Table of Contents

- [What is OSINT?](#-what-is-osint)
- [Skills You Will Learn](#-skills-you-will-learn)
- [Learning Path](#-learning-path)
- [Phase 1 — Fundamentals](#-phase-1--fundamentals)
- [Phase 2 — Core Tools](#-phase-2--core-tools)
- [Phase 3 — Social Media & Geolocation](#-phase-3--social-media--geolocation)
- [Phase 4 — Threat Intelligence](#-phase-4--threat-intelligence)
- [Phase 5 — Automation with Python](#-phase-5--automation-with-python)
- [Phase 6 — Real World Practice](#-phase-6--real-world-practice)
- [Best YouTube Channels](#-best-youtube-channels)
- [Best Websites & Resources](#-best-websites--resources)
- [Books](#-books)
- [Linux Setup](#-linux-setup)
- [Browser Extensions](#-browser-extensions)
- [Project Ideas](#-project-ideas)
- [Certifications](#-certifications)
- [Daily Practice Routine](#-daily-practice-routine)
- [Ethics](#-ethics)
- [6-Month Roadmap](#-6-month-roadmap)

---

# 🔍 What is OSINT?

OSINT (Open Source Intelligence) is the process of collecting and analyzing publicly available information from:

- Websites
- Social media
- Search engines
- Public records
- Metadata
- Maps & satellite imagery
- Leaked databases
- Domain intelligence
- Forums and communities
- Archived web pages

OSINT is widely used in:

- Cybersecurity
- Threat Intelligence
- Bug Bounty Recon
- Journalism
- Investigations
- Digital Forensics
- Corporate Security
- Law Enforcement

---

# 🚀 Skills You Will Learn

✅ Google Dorking  
✅ Metadata Analysis  
✅ Username Enumeration  
✅ Email Intelligence  
✅ Social Media Intelligence  
✅ Domain Reconnaissance  
✅ Geolocation  
✅ Threat Intelligence  
✅ Reverse Image Search  
✅ Automation with Python  
✅ Intelligence Reporting  

---

# 🛣 Learning Path

```text
Internet Basics
      ↓
Search Intelligence
      ↓
Metadata & Social Media OSINT
      ↓
Domain & Network Recon
      ↓
Geolocation & Investigations
      ↓
Threat Intelligence
      ↓
Automation & Scripting
      ↓
Real-World Investigations
```

---

# 📖 Phase 1 — Fundamentals

## 🎯 Goals

Understand how information exists and leaks on the internet.

---

## 📌 Topics to Learn

### 🔎 Search Engine Intelligence
- Google Dorking
- Search Operators
- Cached Pages
- Indexed Data

### 🖼 Metadata Analysis
- EXIF Data
- PDF Metadata
- Hidden File Information

### 👤 Username Intelligence
- Username Correlation
- Alias Tracking
- Social Media Enumeration

### 📧 Email Intelligence
- Email Enumeration
- Breach Checking
- Email Pattern Discovery

### 🌐 Domain Intelligence
- WHOIS
- DNS
- Subdomains
- SSL Certificates

### 🕰 Web Archives
- Cached Pages
- Historical Websites
- Deleted Content

---

# 🛠 Phase 2 — Core Tools

# 👤 Username Investigation Tools

## Sherlock
### 🔗 https://github.com/sherlock-project/sherlock

Search usernames across hundreds of websites.

### Installation

```bash
git clone https://github.com/sherlock-project/sherlock.git
cd sherlock
pip install -r requirements.txt
python sherlock username
```

---

## Maigret
### 🔗 https://github.com/soxoj/maigret

Advanced username OSINT tool.

---

## WhatsMyName
### 🔗 https://whatsmyname.app

Web-based username search platform.

---

# 📧 Email Intelligence Tools

## Hunter.io
### 🔗 https://hunter.io

Find company email patterns.

---

## Have I Been Pwned
### 🔗 https://haveibeenpwned.com

Check if emails were found in data breaches.

---

# 🖼 Metadata Tools

## ExifTool
### 🔗 https://exiftool.org

Best metadata extraction tool.

### Example

```bash
exiftool image.jpg
```

---

## FOCA
### 🔗 https://github.com/ElevenPaths/FOCA

Metadata analysis for documents.

---

# 🌐 Domain Intelligence Tools

## theHarvester
### 🔗 https://github.com/laramies/theHarvester

Collect emails, domains, and subdomains.

### Example

```bash
theHarvester -d example.com -b all
```

---

## Amass
### 🔗 https://owasp.org/www-project-amass/

Powerful subdomain enumeration tool.

---

## Shodan
### 🔗 https://www.shodan.io

Search exposed internet-connected devices.

---

## SecurityTrails
### 🔗 https://securitytrails.com

DNS and domain intelligence.

---

# 🕰 Web Archive Tools

## Wayback Machine
### 🔗 https://archive.org/web/

Historical snapshots of websites.

---

## Archive.today
### 🔗 https://archive.ph

Archive webpages permanently.

---

# 🌍 Phase 3 — Social Media & Geolocation

# 📌 Topics

- Social Media Footprinting
- Geolocation
- Timeline Analysis
- Reverse Image Search
- Video Analysis
- Facial Recognition Awareness

---

# 🖼 Reverse Image Search Tools

## Google Lens
### 🔗 https://lens.google.com

---

## Yandex Images
### 🔗 https://yandex.com/images/

Excellent for location and face similarity.

---

## TinEye
### 🔗 https://tineye.com

Track image origins.

---

# 📍 Geolocation Tools

## Google Earth
### 🔗 https://earth.google.com

---

## GeoGuessr
### 🔗 https://www.geoguessr.com

Improve visual geolocation skills.

---

## SunCalc
### 🔗 https://www.suncalc.org

Estimate location/time using shadows.

---

# 📱 Social Media Investigation Tools

## Social Searcher
### 🔗 https://www.social-searcher.com

---

## Twint
### 🔗 https://github.com/twintproject/twint

Twitter/X intelligence gathering.

---

# 🧠 Phase 4 — Threat Intelligence

# 📌 Learn

- Threat Intelligence
- IOC Analysis
- Malware Infrastructure Tracking
- Breach Analysis
- Passive Reconnaissance

---

# 🛠 Advanced Tools

## Maltego
### 🔗 https://www.maltego.com

Graph-based intelligence platform.

---

## SpiderFoot
### 🔗 https://www.spiderfoot.net

Automated OSINT collection.

---

## Recon-ng
### 🔗 https://github.com/lanmaster53/recon-ng

Reconnaissance framework.

---

## VirusTotal
### 🔗 https://www.virustotal.com

Analyze files, hashes, and domains.

---

## AlienVault OTX
### 🔗 https://otx.alienvault.com

Threat intelligence platform.

---

# 🐍 Phase 5 — Automation with Python

# 📌 Topics

- APIs
- Web Scraping
- Automation
- Regex
- JSON Parsing
- Reporting

---

# 📦 Python Libraries

## Requests

```bash
pip install requests
```

---

## BeautifulSoup

```bash
pip install beautifulsoup4
```

---

## Selenium

```bash
pip install selenium
```

---

## Pandas

```bash
pip install pandas
```

---

# 💡 Project Ideas

# 🟢 Beginner Projects
- Username Checker
- Metadata Extractor
- Email Breach Checker
- Domain Recon Tool

---

# 🟡 Intermediate Projects
- Automated Recon Dashboard
- Shodan Automation Tool
- Social Media Analyzer
- Threat Intel Collector

---

# 🔴 Advanced Projects
- AI-Powered Investigation Assistant
- Real-Time Monitoring System
- Threat Actor Tracker
- Full OSINT Framework

---

# 🧪 Phase 6 — Real-World Practice

# 🏆 Platforms

## TryHackMe
### 🔗 https://tryhackme.com

### Recommended Rooms
- OhSINT
- Sakura Room
- Searchlight
- Google Dorking

---

## Hack The Box
### 🔗 https://www.hackthebox.com

Advanced OSINT & DFIR labs.

---

## Trace Labs
### 🔗 https://www.tracelabs.org

Real missing-person investigations.

---

## CTFtime
### 🔗 https://ctftime.org

Find OSINT competitions and CTFs.

---

# 🎥 Best YouTube Channels

| Channel | Focus |
|---|---|
| The Cyber Mentor | Cybersecurity & OSINT |
| John Hammond | Investigations & CTFs |
| NetworkChuck | Beginner Cybersecurity |
| Seytonic | Cyber Investigations |
| LiveOverflow | Hacking Concepts |
| David Bombal | Networking & Security |
| InsiderPhD | Bug Bounty & Recon |

---

# 🌐 Best Websites & Resources

| Resource | Purpose |
|---|---|
| https://osintframework.com | OSINT Tool Collection |
| https://inteltechniques.com | OSINT Training |
| https://github.com/jivoi/awesome-osint | Huge OSINT Resource List |
| https://www.bellingcat.com | Investigation Journalism |
| https://portswigger.net | Web Security Learning |

---

# 📚 Books

## Open Source Intelligence Techniques
### Author: Michael Bazzell

Best practical OSINT book.

---

## OSINT Techniques
### Author: Michael Bazzell

Advanced investigation methods.

---

## Social Engineering
### Author: Christopher Hadnagy

Human intelligence gathering.

---

# 🐧 Linux Setup

# Recommended Operating Systems

## Kali Linux
### 🔗 https://www.kali.org

---

## Parrot OS
### 🔗 https://www.parrotsec.org

---

# 🌐 Browser Extensions

| Extension | Purpose |
|---|---|
| Wappalyzer | Technology Fingerprinting |
| Shodan Extension | Quick Website Intelligence |
| Wayback Machine | Archive Access |
| User-Agent Switcher | Browser Simulation |
| uBlock Origin | Cleaner Researching |

---

# 🏅 Certifications

| Certification | Platform |
|---|---|
| TCM Practical OSINT | TCM Security |
| eJPT | INE |
| PNPT | TCM Security |
| Security+ | CompTIA |
| HTB CPTS | Hack The Box |

---

# ⏰ Daily Practice Routine

## Daily (1–2 Hours)

### 📰 20 Minutes
Read cyber news & investigations.

### 🛠 30 Minutes
Practice one OSINT tool.

### 🧪 30 Minutes
Solve TryHackMe/HTB challenges.

### 📝 20 Minutes
Document findings and write reports.

---

# ⚖ Ethics

## ✅ Allowed
- Learning
- Labs
- CTFs
- Public Information
- Authorized Investigations

## ❌ Never Do
- Doxxing
- Harassment
- Stalking
- Accessing Private Systems
- Leaking Personal Data

---

# 📅 6-Month Roadmap

# 🟢 Month 1
- Search Operators
- Metadata
- Username OSINT
- TryHackMe Basics

---

# 🟢 Month 2
- DNS
- WHOIS
- Shodan
- Subdomains
- Web Archives

---

# 🟡 Month 3
- Social Media Investigations
- Geolocation
- Reverse Image Search

---

# 🟡 Month 4
- Threat Intelligence
- IOC Tracking
- Malware Infrastructure Basics

---

# 🔴 Month 5
- Python Automation
- APIs
- Scraping
- Dashboards

---

# 🔴 Month 6
- Real Investigations
- Trace Labs
- Advanced Recon
- Portfolio Projects

---

# 🎯 Final Advice

Do NOT focus only on tools.

The best OSINT analysts are experts at:

- Asking the right questions
- Verifying information
- Correlating data
- Building timelines
- Writing professional reports
- Automating repetitive work

Tools help.  
Methodology wins.

---

<div align="center">

# ⭐ Keep Learning • Stay Ethical • Build Real Skills

</div>
