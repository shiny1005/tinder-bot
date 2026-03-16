# TinderBotz 🔥 Tinder Flame Icon

<p align="center">
  <img src="https://logos-world.net/wp-content/uploads/2020/09/Tinder-Symbol.png" alt="Tinder Flame Logo" width="180">
  <br><br>
  <img src="https://logos-world.net/wp-content/uploads/2020/09/Tinder-Logo.png" alt="Tinder Logo" width="300">
</p>

**Automated Tinder web bot & scraper using Selenium (mostly historical / educational now)**

**⚠️ Important – March 2026 status ⚠️**  
This project has seen **very limited maintenance since ~2023–2024**.  
Tinder has made **major frontend changes**, strengthened bot/fraud detection (more Cloudflare/Arkose challenges, device fingerprinting, behaviour analysis), and rolled out many AI-powered features + safety tools in 2025–2026.  
→ **Most functions (especially auto-swiping & mass messaging) are currently broken or result in very quick bans.**  
Use **only for learning purposes** on throwaway/test accounts. Expect to spend significant time fixing selectors & bypassing detection.

<a id="project"></a>
## Project 🧩

<p align="center">
  <h3 align="center">TINDERBOT AND PROFILE SCRAPER (Web version) 🔥</h3>

  <p align="center">
    Tinder web automation & data scraper (Python + Selenium).<br>
    Originally created for educational exploration of browser automation.
    <br /><br />
    <a href="https://github.com/frederikme/TinderBotz/blob/master/DOCUMENTATION.md"><strong>Explore the docs »</strong></a>
    ·
    <a href="https://github.com/frederikme/TinderBotz/issues">Report Issue / Ask for help</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents 🧭

- [About the Project](#about-the-project)
  - [Built With](#built-with)
- [🚨 Current Status – 2026](#current-status--2026)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Documentation](#documentation)
- [How to Avoid (or at Least Delay) Bans](#how-to-avoid-or-at-least-delay-bans)
- [Alternatives in 2026](#alternatives-in-2026)
- [Disclaimer & Legal Warning](#disclaimer--legal-warning)

<!-- ABOUT THE PROJECT -->
<a id="about-the-project"></a>
## About the Project ✨ 🔥

This project was created to experiment with **web automation** and **scraping** using Python + Selenium.

Originally it could:

- Log in to tinder.com (Google / Facebook / phone)
- Set custom location (paid feature bypass – **very unreliable now**)
- Change age range, distance, gender preferences
- Auto-swipe left/right (with random delays)
- Scrape profiles: name, age, bio, photos, distance, interests…
- Send templated / semi-personalized messages to matches
- Handle some pop-ups & notifications

Many of these features **no longer work reliably** due to:
- Major UI redesigns (2024–2026, including Liquid Glass aesthetic and edge-to-edge photos)
- Stronger anti-automation (Arkose/Cloudflare challenges)
- AI-based behaviour detection
- Removal/weakening of several old endpoints/selectors

<a id="built-with"></a>
### Built With

- Python 3.x
- Selenium
- undetected-chromedriver (helps a bit, but detection is much stronger in 2026)

<a id="current-status--2026"></a>
## 🚨 Current Status – 2026

- Last substantial code changes: ~2022–2023
- Minor patches/PRs: up to ~2024
- Many open issues about **"not working anymore"**, captchas, element not found (2025–2026)
- Recent Tinder updates (AI matching "Chemistry", Astrology mode, video speed dating, stronger content moderation & bot detection – announced early 2026) broke many selectors & login flows
- **Mass swiping / messaging almost always leads to shadowban or permanent ban within hours/days** — even with heavy randomization & proxies

→ This repo is now mainly **educational / historical**.  
Feel free to fork & try to revive parts of it — contributions welcome, but success rate is low.

<!-- GETTING STARTED -->
## Getting Started 🚀

### Prerequisites ✅

- Python 3.9–3.12 recommended
- Google / Facebook / Apple login capable Tinder account (**do NOT use your main account**)
- Recent Chrome browser

### Installation 📦

1. Clone the repo
   ```bash
   git clone https://github.com/frederikme/TinderBotz.git
   cd TinderBotz