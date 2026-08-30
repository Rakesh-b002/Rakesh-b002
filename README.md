# Hi, I'm Rakesh B

**Cybersecurity Student · Building AI-Driven Defensive Security Tools**

Second-year B.Tech student specializing in Cybersecurity at Dayananda Sagar University, Bengaluru. I work at the intersection of **network security, threat detection, and applied ML**, focusing on making defensive tools more adaptive and easier to understand — not just "it flagged an attack," but *why*.

📫 **rakesh.122605@gmail.com** · 🔗 [github.com/Rakesh-b002](https://github.com/Rakesh-b002)

---

## What I'm Working On

### 🍯 Adaptive IoT Honeypot with ML-Based Anomaly Detection
A Cowrie-based SSH/Telnet honeypot (inspired by the AIIPot paper) that logs attacker sessions to MongoDB and analyzes behavior with two Isolation Forest models — one behavioral, one semantic (sentence-transformer embeddings + PCA) — plus DBSCAN clustering to group attacker sessions by tactic.
- Behavioral feature extraction: 9 features including Shannon entropy, unique-command ratio, and download/execute detection
- Phase 1 (honeypot + logging) and Phase 2 (feature extraction) complete, with a full unit test suite passing
- **Stack:** Python, Cowrie, MongoDB, scikit-learn, Sentence-Transformers

### ⚡ SNN-Based Intrusion Detection System
Exploring Spiking Neural Networks as a lower-power alternative to conventional deep learning for network intrusion detection, trained on the TON_IoT and CIC-IDS2018 datasets.
- **Focus:** energy-efficient inference, IDS, network security

### 🛰️ Azure SOC & SIEM Lab
A hands-on security monitoring environment built in Azure to practice log collection, detection engineering, and incident investigation the way a SOC analyst would.
- **Focus:** Microsoft Sentinel, log analysis, detection tuning

### 🏗️ NirmanAI — Hack2Skill BRICS Innovation Hackathon
An explainable AI decision-support platform for public infrastructure prioritization, built for the hackathon's Digital Public Good challenge. Citizen-reported issues (initially potholes, extensible to broader civic infrastructure) are fused with population density, road-safety data, and public investment plans into an **Infrastructure Priority Score** that gives policymakers a transparent, ranked view of where to act first — rather than another unranked reporting app.

---

## Tech Stack

<table>
<tr>
<td><b>Security</b></td>
<td>
<img src="https://img.shields.io/badge/SOC-1F2937?style=for-the-badge" />
<img src="https://img.shields.io/badge/SIEM-374151?style=for-the-badge" />
<img src="https://img.shields.io/badge/IDS%2FIPS-4B5563?style=for-the-badge" />
<img src="https://img.shields.io/badge/Honeypots-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Threat_Detection-0A0A0A?style=for-the-badge&logo=hackthebox&logoColor=white" />
</td>
</tr>
<tr>
<td><b>AI / ML</b></td>
<td>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
<img src="https://img.shields.io/badge/Sentence--Transformers-8E44AD?style=for-the-badge" />
<img src="https://img.shields.io/badge/Spiking_Neural_Networks-6C5CE7?style=for-the-badge" />
<img src="https://img.shields.io/badge/Isolation_Forest_%2F_DBSCAN-FF6F00?style=for-the-badge" />
</td>
</tr>
<tr>
<td><b>Cloud & Infra</b></td>
<td>
<img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Also Familiar With</b></td>
<td>
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
</td>
</tr>
</table>

---

## GitHub Stats

<p align="center">
  <img src="profile/stats.svg" height="170"/>
  <img src="profile/top-langs.svg" height="170"/>
</p>

*(Auto-generated daily by a GitHub Action — see setup below. Until the workflow runs once, these will show as broken images.)*

---

## Open to Collaborate

Interested in working with others on cybersecurity × AI/ML projects with real research or real-world potential — reach out if you're building something in that space.
