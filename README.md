<p align="center">
  <h1 align="center">Tinder Auto Bot</h1>
  <h3 align="center">Experimental Python + Selenium automation & scraping tool for Tinder.com</h3>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Selenium-4+-orange?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium"/>
  <img src="https://img.shields.io/badge/undetected--chromedriver-Enabled-red?style=for-the-badge" alt="Undetected Chromedriver"/>
  <img src="https://img.shields.io/badge/Status-Experimental-yellow?style=for-the-badge" alt="Status"/>
  &nbsp;
  <img src="https://img.shields.io/github/license/shiny1005/tinder-auto-bot?style=for-the-badge" alt="License"/>
</p>

<br/>

## ⚠️ Important Disclaimer
## ⚠️ Important Disclaimer

**This is an experimental, educational project only.**  
Tinder.com (Match Group) strictly prohibits automation, bots, scraping, and any form of non-human interaction per their [Terms of Service](https://policies.tinder.com/terms).  

Using this tool **can and likely will** result in:  
- Permanent account bans  
- IP blocks  
- CAPTCHA/Arkose/Cloudflare challenges  
- Legal notices (in extreme cases)

**Use at your own risk.** The author is not responsible for any consequences. This repo is for learning web automation with Selenium only — **do not use on real accounts for production swiping/messaging**.

<br/>

## ✨ Original Features (as built)

- Login via Google, Facebook, or phone number
- Bypass/custom set location (paid Passport feature attempt – **unreliable now**)
- Adjust age range, distance, gender preferences
- Auto-swipe (left/right) with human-like random delays
- Scrape detailed profile data: name, age, bio, photos (URLs), distance, interests/tags, etc.
- Send templated or semi-personalized opening messages to new matches
- Handle common pop-ups, notifications, and basic anti-bot obstacles

<br/>

<p align="center">
  <img src="https://techcrunch.com/wp-content/uploads/2026/03/Tinder-revamp2026.png?w=1024" alt="Modern Tinder UI 2026" width="70%"/>
  <br/><em>Current Tinder interface (2026) – edge-to-edge photos, Liquid Glass aesthetic, new modes like Astrology & Events</em>
</p>

<br/>


## Why Many Features Are Broken in 2026

Tinder has heavily invested in anti-automation since 2024:

- Complete UI redesign (edge-to-edge, dynamic cards, new "For You", Modes like Astrology/Music/Double Date)
- Stronger client-side detection (behavior fingerprinting, mouse/keyboard patterns)
- Arkose Labs / Cloudflare Turnstile challenges
- API endpoint changes & obfuscation
- AI-driven bot detection (unusual swipe speeds, session patterns)

**undetected-chromedriver** helps evade basic checks, but advanced detection still catches most bots quickly.

<br/>

## 🛠️ Built With

- **Python 3.8+**
- **Selenium** (webdriver automation)
- **undetected-chromedriver** (stealth mode to reduce fingerprinting)
- Optional: requests (for photo downloads), beautifulsoup4 (fallback parsing), fake-useragent

<br/>

## 🚀 Quick Setup (For Educational Use Only)

1. Clone the repo
   ```bash
   git clone https://github.com/shiny1005/tinder-bot.git
   cd tinder-bot
