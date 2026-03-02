# Asset Atrium Compliance Framework

Enterprise HTML documentation for the investment compliance capabilities of SunBridge Asset Atrium Manager (FGS) — covering pre-trade compliance, post-trade monitoring, investment mandate management, exposure limits, regulatory reporting, breach management, and audit governance.

## Overview

This site provides internal reference documentation for the Asset Atrium Manager compliance engine. Content covers the full compliance lifecycle: from investment mandate modeling and pre-trade order checking through post-trade monitoring, breach management, and regulatory reporting for UCITS, AIFMD, MiFID II, SEC, and other frameworks.

Static HTML site hosted via GitHub Pages. No build tools or backend required.

## Pages

| Page | Topic |
|------|-------|
| `index.html` | Overview & Compliance Framework — architecture, supported regulations, module summary |
| `pre-trade.html` | Pre-Trade Compliance — real-time order checks, hard/soft breaches, override workflows |
| `post-trade.html` | Post-Trade Monitoring — scheduled compliance runs, passive breach detection, remediation timelines |
| `mandates.html` | Investment Mandates — IPS modeling, rule library, inheritance hierarchy, exception handling |
| `exposure.html` | Exposure & Concentration — sector, country, currency, issuer limits, UCITS 5/10/40, lookthrough, stress testing |
| `regulatory.html` | Regulatory Reporting — UCITS, AIFMD Annex IV, Form PF, MiFID II RTS 25, Solvency II, EMIR |
| `breach.html` | Breach Management — breach lifecycle, classification, escalation matrix, remediation tracking |
| `audit.html` | Audit Trail & Logging — compliance decision logging, Oracle audit schema, retention policies, exam readiness |

## Structure

```
compliance-regulatory-hub/
├── index.html
├── pre-trade.html
├── post-trade.html
├── mandates.html
├── exposure.html
├── regulatory.html
├── breach.html
├── audit.html
├── README.md
└── assets/
    └── style.css
```

## Technology

- HTML (~ 94%)
- CSS (~ 6%)
- No JavaScript, no frameworks, no build pipeline

## Platform Context

Asset Atrium Manager is an enterprise investment management platform originally developed by SunBridge (now FGS). The compliance engine documented here operates within the Asset Atrium ecosystem:

- **Runtime**: J2EE on Oracle WebLogic 14c
- **Database**: Oracle 19c RAC
- **Messaging**: IBM MQ Series
- **Caching**: Oracle Coherence
- **Market Data**: Bloomberg B-PIPE / BVAL
- **Trading**: FIX 4.2/4.4 Gateway
- **Settlement**: SWIFT Alliance Lite2

## Usage

Open `index.html` in any browser, or deploy to GitHub Pages for hosted access.

---

*Asset Atrium Compliance Framework — SunBridge / FGS — Internal Use Only*
