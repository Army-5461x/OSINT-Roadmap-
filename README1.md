# Ultimate OSINT Roadmap (Beginner → Advanced)

> A complete roadmap to learn Open Source Intelligence (OSINT) for cybersecurity, investigations, threat intelligence, bug bounty reconnaissance, journalism, and digital forensics.

***

## What is OSINT?

OSINT (Open Source Intelligence) is the process of collecting, analyzing, and correlating publicly available information from:

- Websites
- Social media
- Search engines
- Metadata
- Public records
- Maps and satellite imagery
- Domain information
- Leaked datasets
- Archived websites
- Forums and communities

***

## Skills You Will Learn

- Digital investigations
- Cyber reconnaissance
- Threat intelligence
- Geolocation
- Metadata analysis
- Social media intelligence
- Domain intelligence
- Username and email tracing
- Automation with Python
- Intelligence reporting

***

## PHASE 1 — Internet & Investigation Fundamentals

### Goals

Learn how information exists and leaks on the internet.

### Topics to Learn

#### Search Engine Intelligence
- Google Dorking
- Advanced search operators
- Cached pages
- Site indexing

#### Metadata
- EXIF data
- File metadata
- PDF metadata
- Hidden information in images and documents

#### Username Intelligence
- Username correlation
- Social media footprinting
- Alias tracking

#### Email Intelligence
- Breach checking
- Email pattern discovery
- Email enumeration

#### Domain Intelligence
- WHOIS
- DNS
- Subdomains
- SSL certificates

#### Web Archives
- Historical websites
- Deleted pages
- Cached content

### Beginner Resources

#### Websites

##### [OSINT Framework](https://osintframework.com)
Massive categorized collection of OSINT tools.

##### [IntelTechniques](https://inteltechniques.com)
Excellent investigative resources by Michael Bazzell.

##### [Awesome OSINT](https://github.com/jivoi/awesome-osint)
Huge GitHub collection of tools and resources.

### Beginner YouTube Channels

##### [The Cyber Mentor](https://www.youtube.com/@TCMSecurityAcademy)
Best beginner-friendly cybersecurity and OSINT tutorials.

##### [John Hammond](https://www.youtube.com/@_JohnHammond)
Excellent practical investigations and CTF walkthroughs.

##### [NetworkChuck](https://www.youtube.com/@NetworkChuck)
Good for motivation and beginner exposure.

##### [Seytonic](https://www.youtube.com/@Seytonic)
Great cybersecurity investigations and case studies.

### Beginner Practice Platforms

##### [TryHackMe](https://tryhackme.com)
Recommended Rooms:
- OhSINT
- Sakura Room
- Searchlight
- Google Dorking
- OSINT challenges

##### [PicoCTF](https://picoctf.org)
Good beginner cybersecurity and investigation exercises.

***

## PHASE 2 — Core OSINT Tools

### Username Investigation Tools

#### [Sherlock](https://github.com/sherlock-project/sherlock)
Search usernames across hundreds of platforms.

##### Install

```bash
git clone https://github.com/sherlock-project/sherlock.git
cd sherlock
pip install -r requirements.txt
python sherlock username
```

#### [Maigret](https://github.com/soxoj/maigret)
Advanced username enumeration.

#### [WhatsMyName](https://whatsmyname.app)
Web-based username investigation.

### Email Intelligence Tools

#### [Hunter.io](https://hunter.io)
Find company email patterns.

#### [Have I Been Pwned](https://haveibeenpwned.com)
Check if emails were found in breaches.

### Metadata Tools

#### [ExifTool](https://exiftool.org)
Best metadata extraction tool.

##### Example

```bash
exiftool image.jpg
```

#### [FOCA](https://github.com/ElevenPaths/FOCA)
Metadata analysis for documents.

### Domain Intelligence Tools

#### [theHarvester](https://github.com/laramies/theHarvester)
Collect emails, domains, and subdomains.

##### Example

```bash
theHarvester -d example.com -b all
```

#### [Amass](https://owasp.org/www-project-amass/)
Powerful subdomain enumeration.

#### [Shodan](https://www.shodan.io)
Search internet-connected devices and exposed services.

#### [SecurityTrails](https://securitytrails.com)
DNS and domain intelligence.

### Web Archive Tools

#### [Wayback Machine](https://archive.org/web/)
Historical website snapshots.

#### [Archive.today](https://archive.ph)
Archive web pages permanently.

***

## PHASE 3 — Social Media & Geolocation Intelligence

### Topics
- Social media footprinting
- Geolocation
- Reverse image search
- Facial recognition awareness
- Timeline analysis
- Video analysis

### Reverse Image Search Tools

#### [Google Lens](https://lens.google.com)

#### [Yandex Images](https://yandex.com/images/)
Excellent for facial and location similarity.

#### [TinEye](https://tineye.com)
Image source tracking.

### Geolocation Tools

#### [Google Earth](https://earth.google.com)

#### [GeoGuessr](https://www.geoguessr.com)
Improves visual geolocation skills.

#### [SunCalc](https://www.suncalc.org)
Estimate time and location from shadows.

### Social Media Investigation Tools

#### [Social Searcher](https://www.social-searcher.com)

#### [Twint](https://github.com/twintproject/twint)
Twitter/X intelligence gathering.

***

## PHASE 4 — Threat Intelligence & Advanced Recon

### Learn
- Threat Intelligence
- IOC analysis
- Malware infrastructure tracking
- Breach analysis
- Dark web monitoring
- Passive reconnaissance

### Advanced Tools

#### [Maltego](https://www.maltego.com)
Graph-based intelligence platform.

#### [SpiderFoot](https://www.spiderfoot.net)
Automated OSINT collection.

#### [Recon-ng](https://github.com/lanmaster53/recon-ng)
Reconnaissance framework.

#### [VirusTotal](https://www.virustotal.com)
Analyze files, domains, and hashes.

#### [AlienVault OTX](https://otx.alienvault.com)
Threat intelligence platform.

***

## PHASE 5 — Automation & Scripting

### Learn Python for OSINT

### Topics
- APIs
- Web scraping
- Automation
- Data parsing
- JSON handling
- Regex
- Reporting

### Python Libraries

#### Requests

```bash
pip install requests
```

#### BeautifulSoup

```bash
pip install beautifulsoup4
```

#### Selenium

```bash
pip install selenium
```

#### Pandas

```bash
pip install pandas
```

### Build These Projects

#### Beginner Projects
- Username checker
- Metadata extractor
- Email breach checker
- Domain recon tool

#### Intermediate Projects
- Automated recon dashboard
- Social media analyzer
- Shodan automation
- Threat intel collector

#### Advanced Projects
- Full OSINT framework
- AI-powered investigation assistant
- Real-time monitoring system
- Threat actor tracker

***

## PHASE 6 — Real-World Practice

### Platforms

#### [Trace Labs](https://www.tracelabs.org)
Real missing-person investigations.

#### [Hack The Box Sherlocks](https://www.hackthebox.com)
Advanced investigations and DFIR challenges.

#### [CTFtime](https://ctftime.org)
Find OSINT competitions and CTFs.

### Best Books

#### Open Source Intelligence Techniques — Michael Bazzell
Best practical OSINT book.

#### OSINT Techniques — Michael Bazzell
Advanced investigation methodologies.

#### Social Engineering: The Science of Human Hacking — Christopher Hadnagy
Understand human intelligence gathering.

### Recommended Linux Setup

#### OSINT Operating Systems
- [Kali Linux](https://www.kali.org)
- [Parrot OS](https://www.parrotsec.org)

#### Browser Extensions for OSINT

##### [Wappalyzer](https://www.wappalyzer.com)
Technology fingerprinting.

##### [Shodan Extension](https://www.shodan.io)
Quick website intelligence.

##### [Wayback Machine Extension](https://archive.org/web/)
Access archived versions of websites quickly.

***

## Recommended Daily Practice Routine

### Daily (1–2 Hours)

- **20 min** — Read cyber news and investigations.
- **30 min** — Practice one OSINT tool.
- **30 min** — Solve TryHackMe or HTB OSINT challenges.
- **20 min** — Document findings and create reports.

***

## Learn Reporting

A professional OSINT investigator must know:

- Documentation
- Evidence preservation
- Timeline building
- Attribution confidence
- Reporting

***

## Important Ethics

### ONLY investigate:
- Yourself
- Labs
- Authorized targets
- Public information
- CTF challenges

### NEVER:
- Doxx
- Stalk
- Harass
- Access private systems
- Leak personal data

***

## Suggested 6-Month Plan

### Month 1
- Search operators
- Metadata
- Username OSINT
- TryHackMe basics

### Month 2
- DNS
- Domains
- Shodan
- Web archives

### Month 3
- Social media investigations
- Geolocation
- Reverse image search

### Month 4
- Threat intelligence
- Malware infrastructure basics
- IOC tracking

### Month 5
- Python automation
- APIs
- Scraping
- Dashboards

### Month 6
- Real investigations
- Trace Labs
- Advanced recon
- Portfolio projects

***

## Final Advice

Do NOT just collect tools.

Focus on:
- Investigation methodology
- Verification
- Correlation
- Documentation
- Automation
- Ethics

The best OSINT analysts are not the people with the most tools —
they are the people who ask the best questions.
