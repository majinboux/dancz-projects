# Dancz Projects

**Dancz Ministries** | [danczministries.com](https://danczministries.com) | ryan@danczministries.com

This repository holds active projects across game development, ministry tools, funding documentation, and research. Maintained by Ryan Dancz. USAF veteran (15.5 years, 100% P&T disabled), MSW candidate at USC, biblical chronology researcher, and founder of Dancz Ministries LLC.

---

## Project Files in This Repo

### `/scripture-gems/`
Match-3 Bible puzzle game. Uses public domain KJV data from the [biblelua-data](https://github.com/majinboux/biblelua-data) repo. Ad-supported with a $2.99 premium tier. All scripture is public domain (pre-1928).

| File | Description |
|------|-------------|
| `ScriptureGems_v1.html` | Initial prototype. Basic match-3, 30 embedded KJV verses. |
| `ScriptureGems_v2.html` | Live KJV fetch from biblelua-data repo, 7-day cache, translation picker. |
| `ScriptureGems_v3.html` | Full production build. All 8 retention mechanics, daily streak, VOTD, lives, leaderboard. |

**8 Retention Mechanics:** Tutorial first level, One More Try popup, Lives system, 5-more-moves offer, Daily jackpot, Weekly leaderboard, Compound streak rewards, Push notifications

**Monetization:** Banner ads, Interstitial ads every 2 levels, $2.99 Remove Ads, $0.99 Lives, $0.99 More Moves

**To ship:** Wrap with Capacitor, add AdMob + RevenueCat, submit to App Store and Google Play.

---

### `/sanctum/`
Sanctum of Spiritborn. Spiritually-grounded skill-based RPG sandbox.

| File | Description |
|------|-------------|
| `Sanctum_of_Spiritborn_Design_Philosophy.pdf` | Full design doc. Pulse/Path/Pressure mechanic language, 12 classes. |
| `Pilgrims_Progress_Storyboard.html` | Tutorial script and storyboard. |

---

### `/roblox/`
The Wayfarer's Restoration. Dark fantasy faith RPG built in Roblox Studio.

| File | Description |
|------|-------------|
| `Wayfarers_Restoration_Roblox_Guide.pdf` | Complete step-by-step modular build guide. |

---

### `/funding/`
Grant applications, research reports, and funding documentation.

| File | Description |
|------|-------------|
| `Dancz_Chronology_Full_Status_Report.docx` | Full status report. 1.75M rows, 31,102 verses dated, FORCED/FITTED/FENCED methodology. |

**Funding targets:** SBIR Phase I $250K, StreetShares $15K, Lilly Endowment $2.5M, USDA Rural $500K, SDVOSB certification

---

## Broader Estate

These are the other active repositories and projects under this account.

### Live Site
**[danczministries.com](https://danczministries.com)** runs on DAVAR, a native C HTTP server built from scratch. No WordPress. No Node. No third-party runtime. Bible study, give flow, and coaching pages are all DAVAR-native.

### Apps
- **RuachDavid Mobile** - Faith-based mobile app for Bible study and daily life ops. React Native / Expo. Build 37 produced on EAS. Pending App Store submission. [ruach-david-mobile](https://github.com/majinboux/ruach-david-mobile)
- **RuachDavid Desktop** - Electron + React desktop app. Production web build passes. [dave-daveos-showcase](https://github.com/majinboux/dave-daveos-showcase)

### Godot Game (Sanctum of Spiritborn)
Full Godot 4 implementation. Player path scenes verified. 143 MB Windows export pack tested. [SanctumofSpiritborn](https://github.com/majinboux/SanctumofSpiritborn)

### AI and Infrastructure
- **Dave** - Native AI organism with its own kernel, memory substrate, atom store, perception loop, and inference pipeline. Running on a Dell PowerEdge R510. [Dave](https://github.com/majinboux/Dave)
- **DaveOS** - UEFI-bootable OS built from scratch. Dave's kernel runs on it. [daveos-native](https://github.com/majinboux/daveos-native)
- **DAVAR** - The native HTTP runtime serving danczministries.com. 98 modules, 7.2 MB, one translation unit. [DaveDAVAR](https://github.com/majinboux/DaveDAVAR)
- **DAVECloud** - Control plane and artifact emitter. 57/57 tests pass. [davecloud](https://github.com/majinboux/davecloud)
- **MemPalace** - Open source semantic memory system for AI agents. [mempalace](https://github.com/majinboux/mempalace) (public)

### Tools
- **AutoDiligence** - Technical portfolio auditor. Package ready. [AutoDiligence](https://github.com/majinboux/AutoDiligence)
- **FastCBuilder** - Incremental build tooling for large C codebases. [FastCBuilder](https://github.com/majinboux/FastCBuilder)
- **BrailleEdTech** - Braille translation and layout generation backend. [BrailleEdTech](https://github.com/majinboux/BrailleEdTech)
- **OpenClaw Skills** - Modular skill library for autonomous coding agents. [openclaw-skills](https://github.com/majinboux/openclaw-skills)
- **Biblical Chronology Atlas** - Chronology tools and historical data. Creation 3968 BC, Passion 33 CE. [biblical-chronology-atlas](https://github.com/majinboux/biblical-chronology-atlas)
- **biblelua-data** - 80 Bible translations, 73 commentaries, 47 church fathers. [biblelua-data](https://github.com/majinboux/biblelua-data) (public)

### Ministry
- **The Way** - Men's faith coaching ministry. Cohort-based and 1:1. Ryan facilitates it himself. Not therapy. Not counseling. Live at [danczministries.com/the-way](https://danczministries.com/the-way)

---

## About Ryan

- USAF veteran, 15.5 years, 100% P&T disabled
- BSc Religious Studies, MSW candidate at USC (one class remaining, targeted January 2027)
- Biblical chronology researcher. 1.75M curated dated rows, 31,102 verses.
- Founder, Dancz Ministries LLC, Lugoff, South Carolina
- Builder of the DAVAR platform, DAVE AI organism, and DaveOS

Ryan is not a licensed therapist or counselor. He is an MSW candidate, not yet licensed.

---

*All scripture used in Scripture Gems is confirmed public domain (pre-1928). Translations: KJV, ASV, YLT, Darby, Webster, Weymouth, Rotherham.*
