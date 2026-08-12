# 🎣 PhishScan — Client-Side Phishing URL Analyzer

A lightweight, fully client-side tool that scans any URL for common phishing red flags — IP-based hosts, `@` redirect tricks, punycode/homograph attacks, brand-name mimicry, suspicious TLDs, and more. No backend, no data collection — everything runs in the browser.

🔗 **Live demo:** _(add your GitHub Pages link here once deployed)_

## Why I built this
As part of my cyber security coursework and web application security assessments, I kept manually checking suspicious URLs against the same checklist of red flags. PhishScan automates that first-pass triage into a simple, instant tool — the kind of quick heuristic check a SOC analyst or end user could run before clicking a link.

## Features
- 10 heuristic checks (IP hostnames, `@` tricks, excessive subdomains, suspicious TLDs, known shorteners, URL length, hyphen density, punycode detection, brand mimicry, HTTPS presence)
- Weighted risk score (Low / Caution / High Risk)
- 100% client-side — no URL data ever leaves the browser or touches a server
- Zero dependencies — pure HTML/CSS/JavaScript

## Tech Stack
`HTML5` `CSS3` `JavaScript (ES6)`

## How to run locally
```bash
git clone https://github.com/<your-username>/phishscan.git
cd phishscan
open index.html   # or just double-click the file
```

## Disclaimer
This is a heuristic educational tool for security awareness, not a substitute for a full threat-intelligence lookup (e.g. VirusTotal, PhishTank). False positives/negatives are possible.

---
Built by **Nihara Dewindini** — Cyber Security Undergraduate, SLIIT
