# CYBERTRACE // Autonomous Cyber Threat Intelligence Platform (2026)
### منصة الاستخبارات والتحليل الجنائي للتهديدات السيبرانية (CyberTrace CTI)

[![Deployment Status](https://img.shields.io/badge/Deployment-GitHub%20Pages%20Ready-00f0ff?style=flat-square&logo=github)](https://pages.github.com/)
[![Threats Monitored](https://img.shields.io/badge/Catalog-50%20Threat%20Families-ef4444?style=flat-square)](https://github.com/)
[![Flagship Dossiers](https://img.shields.io/badge/Whitepapers-50%20In--Depth%20Reports-10b981?style=flat-square)](https://github.com/)
[![Bilingual UI](https://img.shields.io/badge/Language-Arabic%20%7C%20English-blue?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-Defensive%20CTI%20Only-gray?style=flat-square)](#)

---

## 🌍 Overview // نظرة عامة

**CyberTrace** is an enterprise-grade Cyber Threat Intelligence (CTI) and forensic research platform designed to mirror the research caliber of top security intelligence firms (such as **Palo Alto Networks Unit 42**, **Check Point Research**, **Microsoft Threat Intelligence**, **Malwarebytes Labs**, **Outpost24 KrakenLabs**, and **CISA**).

**منصة CyberTrace** هي منصة استخبارات وتحقيق جنائي سيبراني رفيعة المستوى، صُممت لتضاهي تقارير وتحقيقات كبرى مراكز أبحاث التهديدات العالمية، وتتضمن كتالوجاً شاملاً يضم **50 عائلة برمجية خبيثة نشطة في عام 2026**، مع **50 ورقة تحقيق جنائي مفصلة (Whitepapers)** مدعومة بلقطات شاشات أصلية من بيئات المشغلين وأدوات البناء ومسارات العدوى.

---

## 💎 Core Architecture & Design System // المواصفات التقنية والتصميم

* **Static Zero-Dependency Runtime:** 100% pure HTML5, CSS3, and ES6 JavaScript. No Node.js, npm, or Python required for execution or deployment.
* **Instant GitHub Pages Compatibility:** Ready for 1-click deployment with zero build steps.
* **Bilingual Switcher (🇸🇦 Arabic / 🇬🇧 English):** Full bidirectional support with instant dynamic switching (`dir="rtl"` / `dir="ltr"`).
* **Obsidian Anti-Slop Theme:** Built using high-density dark mode (`#07080a`), mechanical 1px borders, and monospace typography (`JetBrains Mono`).
* **Interactive Slide-Over Inspector Drawer:** 7 synchronized tabs per threat (`Overview`, `Infection Chain`, `Technical Specs & C2`, `Defense & Containment`, `YARA & Sigma Detection`, `Forensic Media Gallery`, `Intelligence Sources`).
* **Forensic Media Lightbox:** Click-to-zoom interactive modal for inspecting tool screenshots and builder GUIs.
* **Real-time Search & Filter Matrix:** `Ctrl + K` instant keyboard shortcuts, live filter pills (RAT, Stealer, C2, Loader, Ransomware, Botnet), and instant telemetry counters.

---

## 📂 Project Structure // بنية المشروع

```text
CyberTrace-Platform/
├── index.html                   # Main Command Center HUD & Threat Grid
├── README.md                    # Platform documentation & setup guide
├── css/
│   └── styles.css               # Obsidian theme, HUD layout & whitepaper typography
├── js/
│   ├── app.js                   # Reactive controller, i18n, drawer, and lightbox logic
│   └── threats-data.js          # Complete dataset of 50 threats (#001 - #050)
└── threats/                     # Standalone deep-dive whitepaper dossiers
    ├── asyncrat.html            # TF-001: AsyncRAT Forensic Dossier
    ├── dolphinx.html            # TF-002: Dolphin X (AI Core) Whitepaper
    ├── lumma-whitepaper.html    # TF-003: Lumma Stealer C2 Analysis
    ├── redline-whitepaper.html  # TF-004: RedLine Stealer WCF Investigation
    ├── xworm-whitepaper.html    # TF-008: XWorm RAT & Clipper Whitepaper
    ├── darkgate-whitepaper.html # TF-009: DarkGate Loader In-Memory Injection
    ├── rhadamanthys-whitepaper.html # TF-010: Rhadamanthys VM & VFS Stealer
    ├── havoc-whitepaper.html    # TF-012: Havoc C2 Demon Agent & Ekko Sleep
    ├── sliver-whitepaper.html   # TF-013: Sliver C2 mTLS & WireGuard Analysis
    ├── lockbit-whitepaper.html  # TF-021: LockBit 3.0 Black Hybrid Encryption
    ├── blackcat-whitepaper.html # TF-022: BlackCat (ALPHV) Rust Ransomware
    ├── cobaltstrike-whitepaper.html # TF-031: Cobalt Strike Malleable C2
    ├── njrat-whitepaper.html    # TF-034: NjRAT (Bladabindi) Pipe Protocol
    └── atomic-stealer-whitepaper.html # TF-048: Atomic Stealer (AMOS) macOS
```

---

## 🚀 Instant Deployment to GitHub Pages // خطوات الرفع على استضافة GitHub Pages

### الخطوة 1: تهيئة المستودع (Initialize Git)
افتح الطرفية (PowerShell أو Terminal) داخل المجلد الرئيسي:
```bash
cd "C:\Users\bad\Desktop\مجلد جديد\CyberTrace-Platform"
git init
git add .
git commit -m "feat: initial commit of CyberTrace autonomous CTI platform"
```

### الخطوة 2: ربط المستودع بـ GitHub (Link Remote Repository)
أنشئ مستودعاً جديداً (Public Repository) على حسابك في GitHub باسم `CyberTrace-Platform`:
```bash
git branch -M main
git remote add origin https://github.com/<YOUR-USERNAME>/CyberTrace-Platform.git
git push -u origin main
```

### الخطوة 3: تفعيل GitHub Pages (Enable Pages)
1. ادخل إلى إعدادات المستودع على GitHub: **Settings** -> **Pages**.
2. تحت قسم **Build and deployment** / **Source**، اختر: **Deploy from a branch**.
3. اختر الفرع: **Branch: main** والمجلد: **/ (root)**.
4. اضغط على **Save**.
5. خلال ثوانٍ، سيكون موقعك متاحاً عالمياً على الرابط:
   `https://<YOUR-USERNAME>.github.io/CyberTrace-Platform/`

---

## 🛡️ Defensive & Ethical Rules // السياسة الأخلاقية والدفاعية الصارمة

1. **Strictly Defensive & Educational:**
   This repository is exclusively for defenders, security analysts (SOC / IR), and threat hunters.
2. **Zero Malware Payloads:**
   No malicious binaries, executables, cracked software, or weaponized stagers are distributed or hosted here.
3. **No Commercial Promotion:**
   No vendor contacts, underground marketplace links, or purchase mechanisms are facilitated.

---

## 📊 Complete Directory of All 50 Threat Whitepapers (100% Coverage)

Every single threat in the 2026 catalog features an authoritative, standalone technical dossier in `threats/`:

| ID | Threat Family | Classification | Ecosystem / Architecture | Whitepaper Dossier |
|---|---|---|---|---|
| **TF-001** | **AsyncRAT** | Remote Access Trojan | C# (.NET) / Cloudflare TLS Tunnels | [`threats/asyncrat.html`](threats/asyncrat.html) |
| **TF-002** | **Dolphin X** | AI-Assisted Stealer | C++ & Python AI Core / Telegram C2 | [`threats/dolphinx.html`](threats/dolphinx.html) |
| **TF-003** | **Lumma Stealer** | InfoStealer | Native C / Fast-Flux Crypto Grabber | [`threats/lumma-whitepaper.html`](threats/lumma-whitepaper.html) |
| **TF-004** | **RedLine Stealer** | InfoStealer | .NET / WCF SOAP Credential Harvester | [`threats/redline-whitepaper.html`](threats/redline-whitepaper.html) |
| **TF-005** | **Vidar Stealer** | InfoStealer | C++ / Dead-Drop Resolver Infrastructure | [`threats/vidar-whitepaper.html`](threats/vidar-whitepaper.html) |
| **TF-006** | **Agent Tesla** | Advanced Spyware | .NET / SMTP, FTP & Telegram Wiretapper | [`threats/agenttesla-whitepaper.html`](threats/agenttesla-whitepaper.html) |
| **TF-007** | **Remcos RAT** | Remote Access Trojan | C++ / RC4 Dynamic DNS Surveillance | [`threats/remcos-whitepaper.html`](threats/remcos-whitepaper.html) |
| **TF-008** | **XWorm** | Hybrid RAT & Worm | C# / AES-128 Clipper & USB Spreader | [`threats/xworm-whitepaper.html`](threats/xworm-whitepaper.html) |
| **TF-009** | **DarkGate** | Advanced Loader | AutoHotKey & Delphi / Cloudflare Lures | [`threats/darkgate-whitepaper.html`](threats/darkgate-whitepaper.html) |
| **TF-010** | **Rhadamanthys** | Advanced Stealer | C++ / Embedded VM & Virtual Filesystem | [`threats/rhadamanthys-whitepaper.html`](threats/rhadamanthys-whitepaper.html) |
| **TF-011** | **Stealc** | InfoStealer | Modular C / Web Admin API Exfiltration | [`threats/stealc-whitepaper.html`](threats/stealc-whitepaper.html) |
| **TF-012** | **Havoc C2** | C2 Framework | C (Demon) & Go / Ekko Sleep Obfuscation | [`threats/havoc-whitepaper.html`](threats/havoc-whitepaper.html) |
| **TF-013** | **Sliver C2** | C2 Framework | Go / mTLS & WireGuard Tunneling | [`threats/sliver-whitepaper.html`](threats/sliver-whitepaper.html) |
| **TF-014** | **Mythic C2** | C2 Framework | Python3 & Docker / Multi-Agent C2 | [`threats/mythic-whitepaper.html`](threats/mythic-whitepaper.html) |
| **TF-015** | **QuasarRAT** | Remote Access Trojan | C# (.NET) / TLS Authenticated Sockets | [`threats/quasarrat-whitepaper.html`](threats/quasarrat-whitepaper.html) |
| **TF-016** | **Warzone RAT** | Remote Access Trojan | Native C++ / UAC Bypass & Cam Spying | [`threats/warzone-whitepaper.html`](threats/warzone-whitepaper.html) |
| **TF-017** | **GuLoader** | Shellcode Loader | Encrypted Shellcode & Anti-VM Introspection | [`threats/guloader-whitepaper.html`](threats/guloader-whitepaper.html) |
| **TF-018** | **Pikabot** | Modular Loader | C++ / Advanced EDR API Unhooking | [`threats/pikabot-whitepaper.html`](threats/pikabot-whitepaper.html) |
| **TF-019** | **Qakbot (QBot)** | Banking Trojan & Loader | C++ / Thread Hijacking & SMB Pivoting | [`threats/qakbot-whitepaper.html`](threats/qakbot-whitepaper.html) |
| **TF-020** | **Emotet** | Modular Botnet | C++ / High-Volume Spambot Infrastructure | [`threats/emotet-whitepaper.html`](threats/emotet-whitepaper.html) |
| **TF-021** | **LockBit 3.0** | Ransomware (RaaS) | C & Assembly / High-Speed Hybrid Encryption | [`threats/lockbit-whitepaper.html`](threats/lockbit-whitepaper.html) |
| **TF-022** | **BlackCat (ALPHV)**| Ransomware (RaaS) | Rust / Multithreaded ESXi Destruction | [`threats/blackcat-whitepaper.html`](threats/blackcat-whitepaper.html) |
| **TF-023** | **Akira** | Enterprise Ransomware | C++ & Rust / Cisco VPN Edge Ingress | [`threats/akira-whitepaper.html`](threats/akira-whitepaper.html) |
| **TF-024** | **Medusa** | Big-Game Ransomware | C++ / High-Speed SMB Extortion Hub | [`threats/medusa-whitepaper.html`](threats/medusa-whitepaper.html) |
| **TF-025** | **Phobos (8Base)** | Ransomware Syndicate | C++ / Brute-Forced RDP Perimeter Drops | [`threats/phobos-whitepaper.html`](threats/phobos-whitepaper.html) |
| **TF-026** | **Formbook** | Form Grabber & Stealer | C & Assembly / Hooking ntdll Functions | [`threats/formbook-whitepaper.html`](threats/formbook-whitepaper.html) |
| **TF-027** | **Bumblebee** | Post-Exploitation Loader| C++ / Cobalt Strike & Sliver Staging | [`threats/bumblebee-whitepaper.html`](threats/bumblebee-whitepaper.html) |
| **TF-028** | **IcedID (BokBot)** | Banking Trojan & Loader | Modular C / Steganographic PNG Payloads | [`threats/icedid-whitepaper.html`](threats/icedid-whitepaper.html) |
| **TF-029** | **DanaBot** | Banking Trojan & Stealer| Delphi / Custom TCP Exfiltration Streams | [`threats/danabot-whitepaper.html`](threats/danabot-whitepaper.html) |
| **TF-030** | **SmokeLoader** | Classic Modular Loader | C / Underground Russian Loader Backbone | [`threats/smokeloader-whitepaper.html`](threats/smokeloader-whitepaper.html) |
| **TF-031** | **Cobalt Strike** | Adversary C2 | Java & C / Malleable C2 & SMB Pipes | [`threats/cobaltstrike-whitepaper.html`](threats/cobaltstrike-whitepaper.html) |
| **TF-032** | **Brute Ratel C4** | Next-Gen C2 Framework | C & Assembly / Direct Syscalls & Badger | [`threats/bruteratel-whitepaper.html`](threats/bruteratel-whitepaper.html) |
| **TF-033** | **NetSupport RAT** | Living-off-the-Land RAT | C++ / Trojanned IT Administration Client | [`threats/netsupport-whitepaper.html`](threats/netsupport-whitepaper.html) |
| **TF-034** | **NjRAT** | Commodity RAT | VB.NET / Pipe-Delimited Cleartext Sockets | [`threats/njrat-whitepaper.html`](threats/njrat-whitepaper.html) |
| **TF-035** | **DCRat** | Commercial RAT | .NET / Custom Plugin Ecosystem & Keylogger | [`threats/dcrat-whitepaper.html`](threats/dcrat-whitepaper.html) |
| **TF-036** | **PureCrypter** | Commercial Crypter | .NET / Multi-Stage In-Memory Injector | [`threats/purecrypter-whitepaper.html`](threats/purecrypter-whitepaper.html) |
| **TF-037** | **PrivateLoader** | PPI Loader Network | C++ / Pay-Per-Install Distribution Chain | [`threats/privateloader-whitepaper.html`](threats/privateloader-whitepaper.html) |
| **TF-038** | **SystemBC** | SOCKS5 Proxy Botnet | C / Encrypted Tor Traffic Proxy Gateway | [`threats/systembc-whitepaper.html`](threats/systembc-whitepaper.html) |
| **TF-039** | **Mirai** | IoT Botnet | C / Telnet Brute-Forcing & DDoS Engine | [`threats/mirai-whitepaper.html`](threats/mirai-whitepaper.html) |
| **TF-040** | **Mozi** | P2P IoT Botnet | C / DHT Network Peer-to-Peer Resiliency | [`threats/mozi-whitepaper.html`](threats/mozi-whitepaper.html) |
| **TF-041** | **Meduza Stealer** | Specialized Stealer | C++ / Comprehensive Browser & App Scraping | [`threats/meduza-whitepaper.html`](threats/meduza-whitepaper.html) |
| **TF-042** | **RisePro** | InfoStealer | C++ / Pay-Per-Install Underground Drops | [`threats/risepro-whitepaper.html`](threats/risepro-whitepaper.html) |
| **TF-043** | **BunnyLoader** | Second-Stage Loader | C / Modular Stealer & Spreader Pipeline | [`threats/bunnyloader-whitepaper.html`](threats/bunnyloader-whitepaper.html) |
| **TF-044** | **Latrodectus** | Modern Stealth Loader | C++ / IcedID Successor Delivery Engine | [`threats/latrodectus-whitepaper.html`](threats/latrodectus-whitepaper.html) |
| **TF-045** | **StrelaStealer** | Email Stealer | Python & DLL / Thunderbird & Outlook Grab | [`threats/strelastealer-whitepaper.html`](threats/strelastealer-whitepaper.html) |
| **TF-046** | **HijackLoader** | Polyglot Loader | Modular C / Process Hollowers & Sleep Hooks | [`threats/hijackloader-whitepaper.html`](threats/hijackloader-whitepaper.html) |
| **TF-047** | **RustBucket** | macOS Malware | Rust / Cross-Platform Target Infiltration | [`threats/rustbucket-whitepaper.html`](threats/rustbucket-whitepaper.html) |
| **TF-048** | **Atomic Stealer** | macOS InfoStealer | Go & AppleScript / Keychain & Crypto Grab | [`threats/atomic-stealer-whitepaper.html`](threats/atomic-stealer-whitepaper.html) |
| **TF-049** | **ShadowPad** | Modular C2 | C++ / State-Sponsored Shared Backdoor | [`threats/shadowpad-whitepaper.html`](threats/shadowpad-whitepaper.html) |
| **TF-050** | **PlugX (Korplug)** | Modular RAT | C++ / DLL Side-Loading & Stealth P2P | [`threats/plugx-whitepaper.html`](threats/plugx-whitepaper.html) |

---

© 2026 CyberTrace Threat Intelligence Platform. All rights reserved for defensive & informational operations.
