# ⚠️ NEATLABS™ DATABROKER ATLAS
### Know Who Has Your Data. Take It Back.

> *Over 4,000 data brokers operate in the U.S., harvesting your name, address, phone, financials, relatives, and behavioral profiles — then selling them to anyone with a credit card.*

**DATABROKER ATLAS** is a free, standalone HTML tool that maps the most dangerous data brokers in the U.S., explains exactly what they know about you, and gives you direct opt-out links to take your data back. No backend. No login. No tracking. One file, open and go.

![NEATLABS ATLAS](https://img.shields.io/badge/NEATLABS™-DATABROKER%20ATLAS-ef4444?style=for-the-badge&labelColor=090a0e)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge&labelColor=090a0e)
![Brokers Mapped](https://img.shields.io/badge/Brokers%20Mapped-35%2B-f97316?style=for-the-badge&labelColor=090a0e)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-06b6d4?style=for-the-badge&labelColor=090a0e)
![SDVOSB](https://img.shields.io/badge/SDVOSB-Security%20360%2C%20LLC-a855f7?style=for-the-badge&labelColor=090a0e)

---

## 🔥 Why This Exists

Most people have no idea how many companies are buying and selling their personal information right now.

Your home address, phone number, relatives' names, financial history, insurance claims, employment records, behavioral profiles, and real-time location patterns are being collected, packaged, and sold — often for less than a dollar per record — to marketers, landlords, employers, law enforcement, stalkers, and scammers alike.

**The problem isn't just that it's happening. It's that finding and opting out of each broker individually requires knowing where to look, understanding the process for each one, and repeating the whole thing every few months when your data resurfaces.**

DATABROKER ATLAS solves the discovery and navigation problem. Every major broker, every opt-out link, every process detail — in one place.

> *The average American's data appears on 40+ data broker sites. Comprehensive manual opt-out takes 40–60 hours. We've done the research so you don't have to.*

---

## ✨ Features

- **35+ brokers mapped** across 5 categories with verified opt-out links
- **Priority system** — Critical / High / Medium / Low, so you know where to start
- **Risk level indicators** — 5-dot visual scale for each broker's threat level
- **Difficulty ratings** — Easy / Medium / Hard / Very Hard for each opt-out process
- **What they collect** — data chips showing exactly what each broker has on you
- **Who they sell to** — where your data actually ends up
- **Opt-out method & timing** — phone, email, online form, ID required, and how long removal takes
- **Data reappearance ratings** — how likely and how soon your data comes back
- **Pro tip notes** — insider details like the PeopleConnect hack that removes you from 15+ sites at once
- **✓ Progress tracker** — mark brokers as complete; progress saves automatically via localStorage
- **Export progress report** — download a timestamped `.txt` file with completed and remaining opt-outs sorted by priority
- **Filter by category** — People Search, Marketing Data, Financial & Credit, Background Check, Data Aggregators
- **Filter by difficulty** — tackle Easy opt-outs first for quick wins
- **Live search** — find any broker by name, data type, or category instantly
- **☀️ Light/Dark mode** — preference saved across sessions
- **"Start Here" priority guide** — pinned alert explaining the optimal order of operations
- **Zero dependencies** — pure HTML, CSS, and vanilla JavaScript
- **No server · No login · No tracking · No ads · Free forever**

---

## 🗂️ Categories Covered

### 👤 People Search (15 brokers)
The most publicly visible brokers. Anyone can search your name and get your home address, phone, relatives, and more — for free. These feed data to hundreds of smaller sites.

| Broker | Priority | Difficulty | Key Risk |
|---|---|---|---|
| Whitepages | 🔴 Critical | Hard | 200M+ records, phone verification required |
| Spokeo | 🔴 Critical | Easy | Social media photos, job history |
| BeenVerified | 🔴 Critical | Easy | Also covers PeopleLooker, PeopleSmart |
| MyLife | 🔴 Critical | Very Hard | "Reputation Scores," notorious for resistance |
| Radaris | 🔴 Critical | Medium | Real-time monitoring alerts |
| Intelius | 🔴 Critical | Medium | Use PeopleConnect — covers 15+ sites |
| FamilyTreeNow | 🟠 High | Easy | Lists children by name — prioritize if you have kids |
| PeopleFinders | 🟠 High | Medium | May require driver's license |
| FastPeopleSearch | 🟠 High | Easy | High Google ranking — very visible |
| TruePeopleSearch | 🟠 High | Easy | Free, no login — quick win |
| TruthFinder | 🟠 High | Medium | Covered by PeopleConnect Suppression Center |
| Instant Checkmate | 🟠 High | Medium | Covered by PeopleConnect Suppression Center |
| Nuwber | 🟡 Medium | Easy | Free public access |
| PeekYou | 🟡 Medium | Easy | Social media + web mention aggregator |
| ThatsThem | 🟡 Medium | Easy | IP geolocation + reverse lookup |

### 📣 Marketing Data (6 brokers)
Build behavioral and demographic profiles sold to advertisers, political campaigns, and corporations. Most consumers never know these records exist.

| Broker | Priority | Key Risk |
|---|---|---|
| Acxiom | 🔴 Critical | 10,000+ data points per person; feeds Fortune 500 companies |
| Epsilon | 🟠 High | Cross-channel consumer identity graphs |
| ZoomInfo | 🟠 High | Direct work numbers sold to B2B sales teams |
| Oracle Data Cloud | 🟠 High | Offline purchase history linked to online identity |
| LiveRamp | 🟠 High | Cross-device identity matching — broad downstream impact |
| Clearbit / HubSpot | 🟡 Medium | Auto-fills contact records without consent |

### 💳 Financial & Credit (7 brokers)
Feed insurance scoring, loan underwriting, and risk profiling. The hardest to opt out of — and the highest real-world impact on your life.

| Broker | Priority | Key Risk |
|---|---|---|
| OptOutPrescreen.com | 🟠 High | **Do this first** — 1 form covers all 4 credit bureaus |
| LexisNexis Risk | 🔴 Critical | Feeds law enforcement, insurers, government agencies |
| Equifax | 🔴 Critical | 147M records exposed in 2017 breach |
| Experian | 🔴 Critical | Multiple separate opt-outs required per channel |
| TransUnion | 🔴 Critical | Insurance risk data and consumer segmentation |
| CoreLogic | 🟠 High | 136M+ real estate transactions; impacts underwriting |
| The Work Number | 🟠 High | Employer payroll data sent automatically |

### 🔎 Background Check (3 brokers)
Used by employers and landlords to screen you. Inaccurate data here can cost you jobs and housing — and you may never know you were screened.

| Broker | Priority | Key Risk |
|---|---|---|
| Checkr | 🟠 High | Used by Uber, Lyft, DoorDash, thousands of employers |
| HireRight | 🟠 High | Global employer screening with FCRA rights to dispute |
| Sterling | 🟡 Medium | Corporate screening — request your file if denied a role |

### 🕸️ Data Aggregators (4 brokers)
The wholesale suppliers feeding hundreds of smaller sites. Opt-outs here have the highest downstream impact.

| Broker | Priority | Key Risk |
|---|---|---|
| **PeopleConnect Suppression Center** | 🔴 Critical | **⚡ 1 opt-out = 15+ sites simultaneously** |
| NAI Ad Networks | 🟡 Medium | Opt out of 100+ ad networks at once |
| DMAchoice | 🟡 Medium | Official direct mail opt-out registry |
| Innovis | 🟡 Medium | The "fourth credit bureau" — often overlooked |

---

## 🚀 Quick Start

**One file. Download and open.**

```bash
# Clone the repo
git clone https://github.com/yourusername/neatlabs-databroker-atlas.git

# Open the tool
open neatlabs-databroker-atlas/neatlabs-databroker-atlas.html
```

Or download `neatlabs-databroker-atlas.html` directly and double-click it. No installation, no npm, no build process. Works completely offline once loaded.

---

## ⚡ Recommended Opt-Out Order

Follow this sequence to maximize impact per hour spent:

### Phase 1 — Maximum Leverage (Do These First)
These removals cascade to hundreds of downstream sites:

1. **PeopleConnect Suppression Center** → `suppression.peopleconnect.us` — removes you from Intelius, TruthFinder, Instant Checkmate, US Search, ZabaSearch, Classmates, AnyWho, and 8 more sites in one submission
2. **OptOutPrescreen.com** → `optoutprescreen.com` — stops prescreened credit/insurance offers from all 4 major credit bureaus simultaneously
3. **NAI Opt-Out** → `optout.networkadvertising.org` — removes you from 100+ ad network member companies at once

### Phase 2 — High-Visibility People Search (Quick Wins)
Do these in order of ease — they're free, fast, and email-verified:

4. FastPeopleSearch → Easy, 24 hrs
5. TruePeopleSearch → Easy, 24 hrs
6. ThatsThem → Easy, 24–48 hrs
7. Nuwber → Easy, 24–48 hrs
8. BeenVerified → Easy, covers PeopleLooker + PeopleSmart
9. Spokeo → Easy, 48–72 hrs
10. FamilyTreeNow → Easy, 24 hrs — **prioritize if you have children**

### Phase 3 — Harder People Search
11. Radaris → Medium (persistence required)
12. PeopleFinders → Medium (may require ID)
13. Whitepages → Hard (phone call required)
14. MyLife → Very Hard (multiple attempts often needed)

### Phase 4 — Marketing Data Brokers
15. Acxiom → Medium, 30–45 days
16. ZoomInfo → Easy, 14 days
17. Epsilon → Medium, 30 days
18. LiveRamp → Medium, 30 days

### Phase 5 — Financial & Credit
19. LexisNexis → Hard (may require SSN/driver's license)
20. Equifax, Experian, TransUnion → Medium each
21. CoreLogic → Hard
22. The Work Number → Hard (limits access, doesn't stop data submission)

### Phase 6 — Background Check
23. Request your consumer file from Checkr, HireRight, Sterling
24. Dispute any inaccuracies within 30 days under FCRA

---

## 🔑 The Single Highest-Leverage Action

**If you do nothing else, do this:**

Go to **[suppression.peopleconnect.us](https://suppression.peopleconnect.us/login)**

One opt-out removes you from:
- Intelius
- TruthFinder
- Instant Checkmate
- US Search
- Classmates.com
- ZabaSearch
- AnyWho
- Addresses.com
- PublicRecords.com
- PeopleLookup
- DateCheck
- LookUpAnyone
- iSearch
- PeopleFinder
- AddressSearch.com

That's 15 sites from one form. It takes 5 minutes.

---

## ⏰ Important: Opt-Outs Are Not Permanent

| Timeline | What Happens |
|---|---|
| Day 1–30 | Initial opt-out processed |
| Month 1–3 | Data removed from public search |
| Month 3–6 | Data typically begins to reappear from new public records |
| Month 6+ | Most brokers have re-listed your information |

**Set a quarterly calendar reminder** to repeat your opt-outs. The tool's progress tracker and export feature are designed to support this ongoing process.

---

## 📁 File Structure

```
neatlabs-databroker-atlas/
├── neatlabs-databroker-atlas.html    # The entire tool — one file
└── README.md                         # This file
```

One HTML file. No dependencies. No build step. Everything runs locally in your browser.

---

## ⚠️ Disclaimer

NEATLABS™ DATABROKER ATLAS is provided by **Security 360, LLC** for informational and educational purposes only.

- Opt-out links are verified at time of publication but **may change as companies update their privacy processes**
- We cannot guarantee all links remain current or that opt-out requests will be honored
- Always verify the opt-out page URL before submitting personal information to any broker
- Opt-out effectiveness varies by broker and by your jurisdiction
- **This tool is not legal advice.** For complex situations (stalking, identity theft, domestic violence), consult a privacy attorney or contact the Electronic Frontier Foundation
- FCRA-covered entities (credit bureaus, background check companies) have specific legal obligations — consult the CFPB at `consumerfinance.gov` for your rights
- NEATLABS™ is not affiliated with any of the companies listed in this directory

---

## 🤝 Contributing

Know of a broker that should be added? Have an updated opt-out URL? Contributions welcome.

1. Fork the repo
2. Add or update your broker in the `BROKERS` array in `neatlabs-databroker-atlas.html`:

```javascript
{
  id: 'uniqueid',
  name: 'Broker Name',
  category: 'people',          // people | marketing | financial | background | aggregator
  avatar: 'BN',                // 2-3 character abbreviation
  risk: 4,                     // 1 (low) – 5 (critical)
  priority: 'high',            // critical | high | medium | low
  difficulty: 'Medium',        // Easy | Medium | Hard | Very Hard
  method: '✉️ Email Verify',   // brief description of the opt-out method
  removal: '48–72 hrs',        // time to removal
  desc: 'Description of what this broker does and why it matters.',
  collects: ['Data Type 1', 'Data Type 2', 'Data Type 3'],
  sellsTo: 'Who buys this data',
  optOutUrl: 'https://verified-opt-out-url.com/',
  notes: 'Important details, gotchas, or tips for this specific opt-out.',
  reappears: 'Moderate',       // Low | Moderate | High | Very High
}
```

3. **Verify the opt-out URL yourself before submitting.** Open it, confirm it's the correct page, and note the date.
4. Submit a pull request with a brief note on the broker and why it belongs in ATLAS

**Contribution guidelines:**
- Opt-out URL must be a direct link to the removal/suppression form — not a general privacy policy page
- Broker must have a meaningful U.S. consumer data presence
- All fields required — partial entries will not be merged
- No referral links, affiliate links, or links to paid removal services in the opt-out URL field

---

## 🌐 More from NEATLABS™

DATABROKER ATLAS is part of a growing suite of free privacy and cybersecurity tools built by NEATLABS™.

**→ [neatlabs.ai](https://neatlabs.ai)**

| Tool | Description |
|---|---|
| **DATABROKER ATLAS** | This tool — data broker directory and opt-out tracker |
| **VANTAGE** | Expert intelligence discovery — find the right people to follow on LinkedIn |
| **Blast Radius** | Comprehensive data broker exposure analysis tool |
| **ToS/Policy Analyzer** | AI-powered analysis of privacy policies and terms of service |
| **CMMC Compliance Suite** | CMMC Level 2 compliance platforms for defense contractors |
| **SSP Manager Professional** | System Security Plan documentation and management |

---

## 📄 License

MIT — free to use, fork, modify, and redistribute. Attribution appreciated but not required.

If this tool helped you reduce your data exposure, consider starring the repo. It helps more people find it.

---

## 🏢 About NEATLABS™ / Security 360, LLC

**NEATLABS™** is the innovation brand of **Security 360, LLC**, a Veteran-Owned Small Business (VOSB) specializing in:

- Privacy engineering and data broker exposure analysis
- CMMC Level 2 compliance consulting for defense contractors
- Cybersecurity architecture and zero-trust implementation
- AI-powered security tooling and research platforms
- Federal contracting cybersecurity for the defense industrial base

With 28+ years of federal cybersecurity experience, Security 360 brings practitioner-grade expertise to every engagement — and builds free tools like this one for the broader community.

**→ [neatlabs.ai](https://neatlabs.ai)** for tools, research, and professional services.

---

## 📚 Additional Resources

- **EFF's Surveillance Self-Defense** — `ssd.eff.org`
- **FTC Do Not Call Registry** — `donotcall.gov`
- **CFPB Consumer Credit Rights** — `consumerfinance.gov`
- **California Privacy Rights (CPRA)** — `cppa.ca.gov`
- **Big-Ass Data Broker Opt-Out List** (GitHub, Yael Grauer) — comprehensive community-maintained list
- **Michael Bazzell's IntelTechniques Data Removal Workbook** — `inteltechniques.com/workbook.html`
- **EasyOptOuts** — automated removal service (paid, ~$20/year) for those who want it done automatically

---

*Built by practitioners, for practitioners.*  
*No ads. No tracking. No upsell. Just signal.*

**[⭐ Star this repo if ATLAS helped you take your data back]**
