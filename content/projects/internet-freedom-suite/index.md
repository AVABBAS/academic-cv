---
title: "🔍 Internet Freedom Suite — Anti-Censorship & Network Intelligence Toolkit"
summary: "A comprehensive Python-based toolkit combining multi-source config scanning (50+ sources), DNS health analysis (1000+ servers), OSINT breach detection (12+ databases), and real-time network diagnostics to maintain internet accessibility under extreme censorship conditions."
tags:
  - Python
  - Networking
  - Cybersecurity
  - OSINT
  - Privacy
  - DNS
  - VPN
  - Censorship Circumvention
date: 2024-05-01
show_date: false
---

## Project Overview

A comprehensive **Python-based toolkit** designed to analyze, bypass, and monitor internet censorship. This suite combines multiple scanning engines, data breach analysis, VPN configuration discovery, and real-time network diagnostics to maintain internet accessibility under restricted conditions.

---

## Key Features

### 🌐 Network Intelligence

| Tool | Description |
|---|---|
| Multi-Source Config Scanner | Scans 50+ Telegram channels, GitHub repos, and paste sites for working VLESS/VMess/Trojan configs |
| DNS Health Analyzer | Tests 1,000+ DNS servers across global data centers to identify unfiltered resolvers |
| SNI Bridge Finder | Analyzes 600+ Iranian websites to discover CDN-backed domains usable as TLS bridges |
| CDN Endpoint Scanner | Maps active Cloudflare, ArvanCloud, and AWS IPs for fallback routing |

### 🔓 Privacy & Security

| Tool | Description |
|---|---|
| Phone Number OSINT Engine | Cross-references phone numbers against 12+ real-world breach databases (HaveIBeenPwned, DeHashed, SnusBase, LeakCheck) |
| Personal Data Exposure Report | Details exactly what information is leaked per breach (names, national IDs, addresses, emails, passwords) |
| Risk Assessment | Scores exposure level with actionable security recommendations |

### 📊 Analytics & Monitoring

| Tool | Description |
|---|---|
| Internet Health Checker | Complete network diagnostic testing DNS, latency, speed, and filter type detection |
| VPN Traffic Analyzer | Maps foreign sites accessed by Iranian users via VPN with protocol distribution |
| Device Market Analysis | Tracks iPhone model distribution, regional penetration, and carrier statistics across Iran |
| Population Usage Calculator | Computes collective online hours (455M+ hours/day across 78M users) |

---

## Technical Stack

```
Python 3.x | sockets | SSL/TLS | urllib/requests | threading | JSON

Concurrent scanning:  ThreadPoolExecutor with 300–500 workers
Protocol support:     VLESS, VMess, Trojan, Shadowsocks, Hysteria2, TUIC
Live data saving:     Real-time JSON/TXT/CSV output during scans
Progress tracking:    Custom progress bars with ETA timers
Color-coded output:   Terminal UI for readability
```

---

## Architecture

```
Internet Freedom Suite
├── Config Finders     (50+ sources)
├── DNS Scanners       (1,000+ servers)
├── SNI Analyzers      (600+ sites)
├── Breach Searchers   (12+ databases)
├── Network Diagnostics
├── Traffic Analyzers
└── Report Generators
```

---

## Impact Metrics

| Metric | Value |
|---|---|
| VPN users analyzed | 35M+ |
| iPhones cataloged | 12.8M |
| Internet users computed | 78M |
| Breach databases queried | 12 |
| Config sources scanned | 50+ |
| DNS servers tested | 1,000+ |
| SNI sites analyzed | 600+ |

---

## Use Cases

- **Digital Rights Researchers** — Studying censorship patterns and filtering methods
- **Security Professionals** — Auditing personal data exposure and breach risk
- **Network Engineers** — Diagnosing filtering methods and DNS health
- **Privacy Advocates** — Finding uncensored DNS resolvers
- **Journalists** — Maintaining connectivity in restricted environments

---

## Technologies

`Python` `Sockets` `SSL/TLS` `ThreadPoolExecutor` `VLESS` `VMess` `Trojan` `Shadowsocks` `Hysteria2` `TUIC` `OSINT` `DNS` `Cloudflare` `ArvanCloud` `HaveIBeenPwned` `DeHashed`
