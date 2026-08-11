<!--
PORTFOLIO README — Arjun Krishna B
Design: monochrome · monospace · numbered sections · system-map aesthetic
All charts/diagrams are inline animated SVGs (SMIL + CSS keyframes).
-->

<div align="center">

<!-- ═══════════════════════════════════════════════ TOP META ═══════════════════════════════════════════════ -->
<table width="100%"><tr>
<td align="left"><sub>PORTFOLIO — INDEX N° 001</sub></td>
<td align="right"><sub>CHERTHALA, IN — 9.68° N · 76.34° E</sub></td>
</tr></table>

---

<!-- ═══════════════════════════════════════════════ HERO NAME — animated typing cursor ═══════════════════════════════════════════════ -->
# <span style="font-family: 'JetBrains Mono', monospace;">Arjun Krishna B<span style="border-right: 2px solid #000; animation: blink 1s steps(2) infinite; margin-left: 4px;">&nbsp;</span></span>
<sub><b>Cybersecurity & Full-Stack Developer — Cherthala, India.</b></sub>

<sub>focus ▸ network security · full-stack systems · threat detection · AI-integrated products</sub>
<sub>open to internships · entry-level · collaboration</sub>

---

<sub>PYTHON & JAVASCRIPT &nbsp;·&nbsp; FULL-STACK SYSTEMS &nbsp;·&nbsp; NETWORK SECURITY &nbsp;&nbsp;&nbsp; VIT — 2023 / 2026</sub>

<br/>

<sub>
<a href="https://arjunportfolio.super.site">PORTFOLIO</a> &nbsp;
<a href="https://github.com/arjunkrishn">GITHUB</a> &nbsp;
<a href="https://linkedin.com/in/arjunn100">LINKEDIN</a> &nbsp;
<a href="mailto:arjunkb45@gmail.com">EMAIL</a>
</sub>

<style>
@keyframes blink { 50% { border-color: transparent; } }
@keyframes drawIn { to { stroke-dashoffset: 0; } }
@keyframes growUp { from { transform: scaleY(0); } to { transform: scaleY(1); } }
@keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
@keyframes pulse { 0%, 100% { r: 4; opacity: 1; } 50% { r: 6; opacity: 0.5; } }
@keyframes slideIn { from { transform: translateY(8px); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
</style>

</div>

---

<!-- ═══════════════════════════════════════════════ 01 / WHOAMI ═══════════════════════════════════════════════ -->
<table width="100%"><tr>
<td align="left">

# 01 &nbsp; <sub><b>WHOAMI</b></sub>

</td>
<td align="right">

`~/01-whoami`

</td>
</tr></table>

```
$ whoami
```

graduating **BCA specialized in AIML** at Vellore Institute of Technology, Cherthala.  
building across the **full stack** — Python · JavaScript · SQL · Linux · CLI tooling.  
drawn to projects where **security meets data** — clean architecture and threat response in equal measure.  

---

| | |
|---|---|
| **FOCUS**  | network security · full-stack systems · threat detection · AI-integrated architectures |
| **STATUS** | open to internships · entry-level · collaboration |
| **CLUBS**  | VIT — iSpace Club (Web & App Development) |

---

<!-- ═══════════════════════════════════════════════ 02 / SYSTEM MAP — animated mind-map SVG ═══════════════════════════════════════════════ -->
<table width="100%"><tr>
<td align="left">

# 02 &nbsp; <sub><b>SYSTEM MAP</b></sub>

</td>
<td align="right">

`~/02-system-map`

</td>
</tr></table>

<table width="100%"><tr>
<td align="left"><sub>SYSTEM MAP — EVERYTHING FROM ONE PIPELINE</sub></td>
<td align="right"><sub>FIG. 01</sub></td>
</tr></table>

<br/>

<div align="center">

<!-- Animated mind map SVG: central ARJUN.SYS hub + 7 satellite project nodes + animated connection lines + pulsing nodes -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 720" font-family="ui-monospace, 'JetBrains Mono', 'Fira Code', Menlo, Consolas, monospace" font-size="13" fill="#000">
  <style>
    .lbl { font-size: 13px; font-weight: 600; }
    .sub { font-size: 10px; fill: #555; }
    .node-rect { fill: #fff; stroke: #000; stroke-width: 1.2; }
    .center-rect { fill: #000; stroke: #000; stroke-width: 2; }
    .center-text { fill: #fff; font-weight: 700; }
    .conn { stroke: #000; stroke-width: 1.2; fill: none; stroke-dasharray: 600; stroke-dashoffset: 600; animation: draw 1.4s ease-out forwards; }
    .pulse { animation: pulse 2.4s ease-in-out infinite; transform-origin: center; transform-box: fill-box; }
    .float-in { animation: floatin 0.8s ease-out backwards; }
    @keyframes draw { to { stroke-dashoffset: 0; } }
    @keyframes pulse { 0%, 100% { opacity: 1; } 50% { opacity: 0.35; } }
    @keyframes floatin { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: translateY(0); } }
  </style>

  <!-- background grid (very faint) -->
  <defs>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#eee" stroke-width="0.5"/>
    </pattern>
  </defs>
  <rect width="1200" height="720" fill="url(#grid)"/>

  <!-- category labels (top) -->
  <text x="600" y="22" text-anchor="middle" class="sub" letter-spacing="2">WEB &amp; DATA</text>
  <text x="200" y="22" class="sub" letter-spacing="2">SECURITY</text>
  <text x="1000" y="22" class="sub" letter-spacing="2">TOOLING</text>

  <!-- Category labels (bottom) -->
  <text x="600" y="710" text-anchor="middle" class="sub" letter-spacing="2">FULL-STACK · RESEARCH · INTERNSHIPS</text>

  <!-- ============== CONNECTION LINES (drawn in) ============== -->
  <!-- from center (600,360) outward -->
  <line class="conn" x1="600" y1="360" x2="320" y2="160" style="animation-delay: 0.0s"/>
  <line class="conn" x1="600" y1="360" x2="880" y2="160" style="animation-delay: 0.1s"/>
  <line class="conn" x1="600" y1="360" x2="200" y2="320" style="animation-delay: 0.2s"/>
  <line class="conn" x1="600" y1="360" x2="1000" y2="320" style="animation-delay: 0.3s"/>
  <line class="conn" x1="600" y1="360" x2="320" y2="540" style="animation-delay: 0.4s"/>
  <line class="conn" x1="600" y1="360" x2="880" y2="540" style="animation-delay: 0.5s"/>
  <line class="conn" x1="600" y1="360" x2="600" y2="600" style="animation-delay: 0.6s"/>

  <!-- ============== SATELLITE NODES ============== -->
  <!-- Top-left: job-shield -->
  <g class="float-in" style="animation-delay: 0.4s">
    <rect class="node-rect" x="200" y="100" width="240" height="120" rx="2"/>
    <text x="320" y="135" text-anchor="middle" class="lbl">job-shield</text>
    <line x1="220" y1="148" x2="420" y2="148" stroke="#000" stroke-width="0.6"/>
    <text x="320" y="170" text-anchor="middle" class="sub">fake job detector</text>
    <text x="320" y="188" text-anchor="middle" class="sub">NLP · scikit-learn</text>
    <text x="320" y="206" text-anchor="middle" class="sub">live</text>
    <circle class="pulse" cx="425" cy="110" r="3" fill="#000"/>
  </g>

  <!-- Top-right: ai-threat -->
  <g class="float-in" style="animation-delay: 0.5s">
    <rect class="node-rect" x="760" y="100" width="240" height="120" rx="2"/>
    <text x="880" y="135" text-anchor="middle" class="lbl">ai-threat</text>
    <line x1="780" y1="148" x2="980" y2="148" stroke="#000" stroke-width="0.6"/>
    <text x="880" y="170" text-anchor="middle" class="sub">AI threat detection</text>
    <text x="880" y="188" text-anchor="middle" class="sub">ml · streamlit</text>
    <text x="880" y="206" text-anchor="middle" class="sub">SRIP 2026</text>
    <circle class="pulse" cx="985" cy="110" r="3" fill="#000"/>
  </g>

  <!-- Mid-left: vulnsnip -->
  <g class="float-in" style="animation-delay: 0.6s">
    <rect class="node-rect" x="80" y="260" width="240" height="120" rx="2"/>
    <text x="200" y="295" text-anchor="middle" class="lbl">vulnsnip</text>
    <line x1="100" y1="308" x2="300" y2="308" stroke="#000" stroke-width="0.6"/>
    <text x="200" y="330" text-anchor="middle" class="sub">vulnerability scanner</text>
    <text x="200" y="348" text-anchor="middle" class="sub">nmap · python</text>
    <text x="200" y="366" text-anchor="middle" class="sub">live</text>
    <circle class="pulse" cx="305" cy="270" r="3" fill="#000"/>
  </g>

  <!-- Mid-right: net-watch -->
  <g class="float-in" style="animation-delay: 0.7s">
    <rect class="node-rect" x="880" y="260" width="240" height="120" rx="2"/>
    <text x="1000" y="295" text-anchor="middle" class="lbl">net-watch</text>
    <line x1="900" y1="308" x2="1100" y2="308" stroke="#000" stroke-width="0.6"/>
    <text x="1000" y="330" text-anchor="middle" class="sub">traffic analyzer</text>
    <text x="1000" y="348" text-anchor="middle" class="sub">scapy · tcp/ip</text>
    <text x="1000" y="366" text-anchor="middle" class="sub">live</text>
    <circle class="pulse" cx="1105" cy="270" r="3" fill="#000"/>
  </g>

  <!-- Bottom-left: fortigate-lab -->
  <g class="float-in" style="animation-delay: 0.8s">
    <rect class="node-rect" x="200" y="480" width="240" height="120" rx="2"/>
    <text x="320" y="515" text-anchor="middle" class="lbl">fortigate-lab</text>
    <line x1="220" y1="528" x2="420" y2="528" stroke="#000" stroke-width="0.6"/>
    <text x="320" y="550" text-anchor="middle" class="sub">firewall &amp; VPN</text>
    <text x="320" y="568" text-anchor="middle" class="sub">fortigate · vlan</text>
    <text x="320" y="586" text-anchor="middle" class="sub">internship · 2026</text>
    <circle class="pulse" cx="425" cy="490" r="3" fill="#000"/>
  </g>

  <!-- Bottom-right: ui-shelf -->
  <g class="float-in" style="animation-delay: 0.9s">
    <rect class="node-rect" x="760" y="480" width="240" height="120" rx="2"/>
    <text x="880" y="515" text-anchor="middle" class="lbl">ui-shelf</text>
    <line x1="780" y1="528" x2="980" y2="528" stroke="#000" stroke-width="0.6"/>
    <text x="880" y="550" text-anchor="middle" class="sub">responsive web ui</text>
    <text x="880" y="568" text-anchor="middle" class="sub">html · css · js</text>
    <text x="880" y="586" text-anchor="middle" class="sub">internship · 2025</text>
    <circle class="pulse" cx="985" cy="490" r="3" fill="#000"/>
  </g>

  <!-- Bottom-center: portfolio -->
  <g class="float-in" style="animation-delay: 1.0s">
    <rect class="node-rect" x="480" y="600" width="240" height="100" rx="2"/>
    <text x="600" y="635" text-anchor="middle" class="lbl">portfolio</text>
    <line x1="500" y1="648" x2="700" y2="648" stroke="#000" stroke-width="0.6"/>
    <text x="600" y="670" text-anchor="middle" class="sub">arjunportfolio.super.site</text>
    <text x="600" y="686" text-anchor="middle" class="sub">live</text>
    <circle class="pulse" cx="705" cy="610" r="3" fill="#000"/>
  </g>

  <!-- ============== CENTER HUB ============== -->
  <g class="float-in" style="animation-delay: 0.2s">
    <rect class="center-rect" x="500" y="320" width="200" height="80" rx="2"/>
    <text x="600" y="350" text-anchor="middle" class="center-text" style="font-size: 16px;">ARJUN.SYS</text>
    <line x1="520" y1="362" x2="680" y2="362" stroke="#fff" stroke-width="0.6"/>
    <text x="600" y="382" text-anchor="middle" style="fill: #ccc; font-size: 10px;">one-person build pipeline</text>
  </g>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════ 03 / PROJECTS ═══════════════════════════════════════════════ -->
<table width="100%"><tr>
<td align="left">

# 03 &nbsp; <sub><b>PROJECTS</b></sub>

</td>
<td align="right">

`~/03-projects`

</td>
</tr></table>

<br/>

## 01 / JOB-SHIELD — Fake Job Posting Detection
Intelligent fraud detection system classifying job postings as **genuine or fraudulent** using ML and NLP. Implements text preprocessing, TF-IDF & CountVectorizer feature extraction, and trains classification models. Evaluated via accuracy, precision, recall, F1-score.
<sub>PYTHON · SCIKIT-LEARN · PANDAS · NUMPY · NLTK · TF-IDF · NLP · MATPLOTLIB</sub>

---

## 02 / VULNSNIP — Vulnerability Scanner
Python-based vulnerability scanner identifying **security weaknesses and exposed services** on target systems. Implements automated host discovery, port scanning, service enumeration, and misconfiguration checks. Generates scan reports for risk identification.
<sub>PYTHON · NMAP · PYTHON-NMAP · SOCKET · TCP/IP · LINUX · THREADING</sub>

---

## 03 / NET-WATCH — Network Traffic Analyzer
Real-time Python-based network traffic analyzer monitoring communications. Implements **packet inspection and protocol analysis** to identify TCP, UDP, ICMP, DNS, and HTTP patterns. Generates traffic statistics and reports for anomaly detection.
<sub>PYTHON · SCAPY · PANDAS · MATPLOTLIB · SOCKET · TCP/IP · WIRESHARK</sub>

---

## 04 / AI-THREAT — AI Threat Detection System
Python-based system automating identification and classification of **cybersecurity threats** from network traffic. Uses data preprocessing, feature extraction, anomaly detection, and ML algorithms. Generates real-time alerts, risk assessments, and analytical reports.
<sub>PYTHON · SCIKIT-LEARN · PANDAS · NUMPY · STREAMLIT · ANOMALY DETECTION</sub>

---

## 05 / FORTIGATE-LAB — Firewall & Network Hardening
Internship project at Secure Solutions — installed, configured, and managed **FortiGate firewalls** to secure enterprise network infrastructure. Configured firewall policies, NAT, VLANs, and IPsec VPNs. Implemented IPS, Web Filtering, AV, Application Control.
<sub>FORTIGATE · FIREWALL · NAT · VLAN · IPSEC VPN · IPS · WIRESHARK</sub>

---

## 06 / UI-SHELF — Responsive Web Interfaces
Internship project at Techgentsia — assisted in developing and implementing **responsive web user interfaces**. Collaborated with development teams to support front-end design and testing activities.
<sub>HTML · CSS · JAVASCRIPT · RESPONSIVE DESIGN · UI/UX</sub>

---

<!-- ═══════════════════════════════════════════════ 04 / TELEMETRY — animated charts ═══════════════════════════════════════════════ -->
<table width="100%"><tr>
<td align="left">

# 04 &nbsp; <sub><b>TELEMETRY</b></sub>

</td>
<td align="right">

`~/04-telemetry`

</td>
</tr></table>

<table width="100%"><tr>
<td align="left"><sub>TELEMETRY — WHAT THE HANDS ARE DOING</sub></td>
<td align="right"><sub>FIG. 02</sub></td>
</tr></table>

<br/>

<!-- ─────────────── ANIMATED HORIZONTAL BAR CHART ─────────────── -->
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 360 280" font-family="ui-monospace, 'JetBrains Mono', Menlo, Consolas, monospace" font-size="12" fill="#000">
  <style>
    .bar { fill: #000; transform-origin: left center; transform-box: fill-box; animation: grow 1.2s cubic-bezier(.2,.7,.3,1) backwards; }
    .pct { font-size: 11px; fill: #000; opacity: 0; animation: fadein 0.5s ease-out forwards; }
    @keyframes grow { from { transform: scaleX(0); } to { transform: scaleX(1); } }
    @keyframes fadein { to { opacity: 1; } }
  </style>

  <text x="0" y="14" font-size="10" letter-spacing="2" fill="#555">LANGUAGE DISTRIBUTION · EST.</text>

  <!-- python 32% -->
  <text x="0" y="46">python</text>
  <rect class="bar" x="80" y="35" width="0" height="14" style="animation-delay: 0.1s">
    <animate attributeName="width" from="0" to="220" dur="1s" fill="freeze" begin="0.1s"/>
  </rect>
  <text x="305" y="46" class="pct" style="animation-delay: 1.0s">32%</text>

  <!-- javascript 22% -->
  <text x="0" y="78">javascript</text>
  <rect class="bar" x="80" y="67" width="0" height="14" style="animation-delay: 0.2s">
    <animate attributeName="width" from="0" to="151" dur="1s" fill="freeze" begin="0.2s"/>
  </rect>
  <text x="305" y="78" class="pct" style="animation-delay: 1.1s">22%</text>

  <!-- sql 18% -->
  <text x="0" y="110">sql</text>
  <rect class="bar" x="80" y="99" width="0" height="14" style="animation-delay: 0.3s">
    <animate attributeName="width" from="0" to="124" dur="1s" fill="freeze" begin="0.3s"/>
  </rect>
  <text x="305" y="110" class="pct" style="animation-delay: 1.2s">18%</text>

  <!-- bash 9% -->
  <text x="0" y="142">bash</text>
  <rect class="bar" x="80" y="131" width="0" height="14" style="animation-delay: 0.4s">
    <animate attributeName="width" from="0" to="62" dur="1s" fill="freeze" begin="0.4s"/>
  </rect>
  <text x="305" y="142" class="pct" style="animation-delay: 1.3s">9%</text>

  <!-- c/c++ 7% -->
  <text x="0" y="174">c/c++</text>
  <rect class="bar" x="80" y="163" width="0" height="14" style="animation-delay: 0.5s">
    <animate attributeName="width" from="0" to="48" dur="1s" fill="freeze" begin="0.5s"/>
  </rect>
  <text x="305" y="174" class="pct" style="animation-delay: 1.4s">7%</text>

  <!-- html/css 6% -->
  <text x="0" y="206">html/css</text>
  <rect class="bar" x="80" y="195" width="0" height="14" style="animation-delay: 0.6s">
    <animate attributeName="width" from="0" to="41" dur="1s" fill="freeze" begin="0.6s"/>
  </rect>
  <text x="305" y="206" class="pct" style="animation-delay: 1.5s">6%</text>

  <!-- other 6% -->
  <text x="0" y="238">other</text>
  <rect class="bar" x="80" y="227" width="0" height="14" style="animation-delay: 0.7s">
    <animate attributeName="width" from="0" to="41" dur="1s" fill="freeze" begin="0.7s"/>
  </rect>
  <text x="305" y="238" class="pct" style="animation-delay: 1.6s">6%</text>
</svg>

</div>

---

<!-- ─────────────── ANIMATED LINE CHART — Shipping Velocity ─────────────── -->
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 360 240" font-family="ui-monospace, 'JetBrains Mono', Menlo, Consolas, monospace" font-size="11" fill="#000">
  <style>
    .axis { stroke: #000; stroke-width: 1; }
    .grid { stroke: #eee; stroke-width: 0.5; }
    .label { font-size: 9px; fill: #555; letter-spacing: 1.5px; }
    .point { fill: #000; opacity: 0; animation: pop 0.3s ease-out forwards; }
    .point-halo { fill: none; stroke: #000; stroke-width: 1; opacity: 0; animation: halo 2.4s ease-out infinite; }
    @keyframes pop { to { opacity: 1; } }
    @keyframes halo { 0% { r: 4; opacity: 0.6; } 100% { r: 14; opacity: 0; } }
  </style>

  <text x="0" y="14" class="label">SHIPPING VELOCITY · 2023 → 2026</text>

  <!-- Y axis -->
  <line class="axis" x1="40" y1="40" x2="40" y2="200"/>
  <!-- X axis -->
  <line class="axis" x1="40" y1="200" x2="340" y2="200"/>

  <!-- Y grid labels -->
  <text x="34" y="44" text-anchor="end" font-size="9" fill="#666">60</text>
  <text x="34" y="84" text-anchor="end" font-size="9" fill="#666">40</text>
  <text x="34" y="124" text-anchor="end" font-size="9" fill="#666">20</text>
  <text x="34" y="200" text-anchor="end" font-size="9" fill="#666">0</text>

  <!-- Y grid lines -->
  <line class="grid" x1="40" y1="80" x2="340" y2="80"/>
  <line class="grid" x1="40" y1="120" x2="340" y2="120"/>
  <line class="grid" x1="40" y1="160" x2="340" y2="160"/>

  <!-- X labels -->
  <text x="60" y="218" text-anchor="middle" class="label">'23</text>
  <text x="130" y="218" text-anchor="middle" class="label">'24</text>
  <text x="200" y="218" text-anchor="middle" class="label">'25</text>
  <text x="270" y="218" text-anchor="middle" class="label">'26</text>
  <text x="320" y="218" text-anchor="middle" class="label">now</text>

  <!-- The animated line (path drawing) -->
  <polyline points="60,180 130,160 200,120 270,80 320,50"
            fill="none" stroke="#000" stroke-width="2"
            stroke-dasharray="500" stroke-dashoffset="500">
    <animate attributeName="stroke-dashoffset" from="500" to="0" dur="1.6s" fill="freeze" begin="0.4s"/>
  </polyline>

  <!-- Data points with halos -->
  <circle class="point-halo" cx="60" cy="180" r="4" style="animation-delay: 1.2s"/>
  <circle class="point" cx="60" cy="180" r="3" style="animation-delay: 0.4s"/>

  <circle class="point-halo" cx="130" cy="160" r="4" style="animation-delay: 1.4s"/>
  <circle class="point" cx="130" cy="160" r="3" style="animation-delay: 0.7s"/>

  <circle class="point-halo" cx="200" cy="120" r="4" style="animation-delay: 1.6s"/>
  <circle class="point" cx="200" cy="120" r="3" style="animation-delay: 1.0s"/>

  <circle class="point-halo" cx="270" cy="80" r="4" style="animation-delay: 1.8s"/>
  <circle class="point" cx="270" cy="80" r="3" style="animation-delay: 1.3s"/>

  <circle class="point-halo" cx="320" cy="50" r="4" style="animation-delay: 2.0s"/>
  <circle class="point" cx="320" cy="50" r="4" style="animation-delay: 1.6s"/>

  <!-- trend annotation -->
  <text x="170" y="225" text-anchor="middle" class="label" style="fill:#000;">trend — accelerating →</text>
</svg>

</div>

---

<!-- ─────────────── STATS GRID (big numbers) ─────────────── -->
<table width="100%">
<tr>
<td align="center" valign="top" width="25%">

# <span style="font-size: 56px; font-weight: 800;">18</span>
<sub>REPOSITORIES</sub>

</td>
<td align="center" valign="top" width="25%">

# <span style="font-size: 56px; font-weight: 800;">6</span>
<sub>PROJECTS DOCUMENTED</sub>

</td>
<td align="center" valign="top" width="25%">

# <span style="font-size: 56px; font-weight: 800;">4</span>
<sub>PLATFORMS — SEC / WEB / CLI / DATA</sub>

</td>
<td align="center" valign="top" width="25%">

# <span style="font-size: 56px; font-weight: 800;">∞</span>
<sub>TERMINAL TABS OPEN RIGHT NOW</sub>

</td>
</tr>
</table>

---

<!-- ─────────────── GITHUB STATS BOX + LANGUAGES BY REPO ─────────────── -->
<table width="100%">
<tr>
<td width="50%" valign="top">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 360 220" font-family="ui-monospace, 'JetBrains Mono', Menlo, Consolas, monospace" font-size="12" fill="#000">
  <style>
    .box { fill: #fff; stroke: #000; stroke-width: 1; }
    .ttl { font-size: 13px; font-weight: 700; letter-spacing: 2px; }
    .row { opacity: 0; animation: slideup 0.5s ease-out forwards; }
    @keyframes slideup { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: translateY(0); } }
  </style>

  <rect class="box" x="0" y="0" width="360" height="220"/>
  <text x="20" y="32" class="ttl">GITHUB STATS</text>
  <line x1="20" y1="44" x2="340" y2="44" stroke="#000" stroke-width="0.6"/>

  <g class="row" style="animation-delay: 0.2s">
    <text x="20" y="72">TOTAL STARS</text>
    <text x="340" y="72" text-anchor="end">4</text>
  </g>
  <g class="row" style="animation-delay: 0.4s">
    <text x="20" y="102">2026 COMMITS</text>
    <text x="340" y="102" text-anchor="end">345</text>
  </g>
  <g class="row" style="animation-delay: 0.6s">
    <text x="20" y="132">TOTAL PULL REQUESTS</text>
    <text x="340" y="132" text-anchor="end">2</text>
  </g>
  <g class="row" style="animation-delay: 0.8s">
    <text x="20" y="162">TOTAL ISSUES</text>
    <text x="340" y="162" text-anchor="end">0</text>
  </g>
  <g class="row" style="animation-delay: 1.0s">
    <text x="20" y="192">CONTRIBUTED TO</text>
    <text x="340" y="192" text-anchor="end">25</text>
  </g>
</svg>

</td>
<td width="50%" valign="top">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 360 220" font-family="ui-monospace, 'JetBrains Mono', Menlo, Consolas, monospace" font-size="12" fill="#000">
  <style>
    .box { fill: #fff; stroke: #000; stroke-width: 1; }
    .ttl { font-size: 13px; font-weight: 700; letter-spacing: 2px; }
    .bar { fill: #000; transform-origin: left center; transform-box: fill-box; }
  </style>

  <rect class="box" x="0" y="0" width="360" height="220"/>
  <text x="20" y="32" class="ttl">LANGUAGES BY REPOSITORY</text>
  <line x1="20" y1="44" x2="340" y2="44" stroke="#000" stroke-width="0.6"/>

  <!-- bar 1: javascript 24% -->
  <text x="20" y="68">JAVASCRIPT</text>
  <rect class="bar" x="140" y="58" width="0" height="12">
    <animate attributeName="width" from="0" to="192" dur="1s" fill="freeze" begin="0.2s"/>
  </rect>
  <rect x="332" y="58" width="8" height="12" fill="#fff" stroke="#000" stroke-width="0.6"/>

  <!-- bar 2: typescript -->
  <text x="20" y="98">TYPESCRIPT</text>
  <rect class="bar" x="140" y="88" width="0" height="12">
    <animate attributeName="width" from="0" to="144" dur="1s" fill="freeze" begin="0.3s"/>
  </rect>
  <rect x="284" y="88" width="56" height="12" fill="#fff" stroke="#000" stroke-width="0.6"/>

  <!-- bar 3: html 18% -->
  <text x="20" y="128">HTML</text>
  <rect class="bar" x="140" y="118" width="0" height="12">
    <animate attributeName="width" from="0" to="120" dur="1s" fill="freeze" begin="0.4s"/>
  </rect>
  <rect x="260" y="118" width="80" height="12" fill="#fff" stroke="#000" stroke-width="0.6"/>

  <!-- bar 4: swift -->
  <text x="20" y="158">SWIFT</text>
  <rect class="bar" x="140" y="148" width="0" height="12">
    <animate attributeName="width" from="0" to="80" dur="1s" fill="freeze" begin="0.5s"/>
  </rect>
  <rect x="220" y="148" width="120" height="12" fill="#fff" stroke="#000" stroke-width="0.6"/>

  <!-- bar 5: python -->
  <text x="20" y="188">PYTHON</text>
  <rect class="bar" x="140" y="178" width="0" height="12">
    <animate attributeName="width" from="0" to="56" dur="1s" fill="freeze" begin="0.6s"/>
  </rect>
  <rect x="196" y="178" width="144" height="12" fill="#fff" stroke="#000" stroke-width="0.6"/>
</svg>

</td>
</tr>
</table>

---

<!-- ─────────────── CONTRIBUTION GRAPH — animated heatmap ─────────────── -->
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 720 200" font-family="ui-monospace, 'JetBrains Mono', Menlo, Consolas, monospace" font-size="10" fill="#000">
  <style>
    .lbl { font-size: 10px; letter-spacing: 1.5px; fill: #555; }
    .cell { opacity: 0; animation: appear 0.4s ease-out forwards; }
    .line { stroke: #000; stroke-width: 1.5; fill: none; stroke-dasharray: 2000; stroke-dashoffset: 2000; animation: draw 2s ease-out forwards; }
    @keyframes appear { to { opacity: 1; } }
    @keyframes draw { to { stroke-dashoffset: 0; } }
  </style>

  <text x="0" y="14" class="lbl">CONTRIBUTION TELEMETRY</text>
  <text x="710" y="14" class="lbl" text-anchor="end">Y-axis: contributions</text>

  <!-- y labels -->
  <text x="0" y="50" font-size="9" fill="#666">25</text>
  <text x="0" y="80" font-size="9" fill="#666">15</text>
  <text x="0" y="110" font-size="9" fill="#666">10</text>
  <text x="0" y="140" font-size="9" fill="#666">5</text>
  <text x="0" y="170" font-size="9" fill="#666">0</text>

  <!-- horizontal grid lines -->
  <line x1="20" y1="46" x2="700" y2="46" stroke="#eee" stroke-width="0.5"/>
  <line x1="20" y1="76" x2="700" y2="76" stroke="#eee" stroke-width="0.5"/>
  <line x1="20" y1="106" x2="700" y2="106" stroke="#eee" stroke-width="0.5"/>
  <line x1="20" y1="136" x2="700" y2="136" stroke="#eee" stroke-width="0.5"/>

  <!-- baseline -->
  <line x1="20" y1="166" x2="700" y2="166" stroke="#000" stroke-width="0.8"/>

  <!-- x labels (days) -->
  <g font-size="9" fill="#666" text-anchor="middle">
    <text x="40" y="184">12</text>
    <text x="100" y="184">15</text>
    <text x="160" y="184">18</text>
    <text x="220" y="184">21</text>
    <text x="280" y="184">24</text>
    <text x="340" y="184">27</text>
    <text x="400" y="184">30</text>
    <text x="460" y="184">02</text>
    <text x="520" y="184">05</text>
    <text x="580" y="184">08</text>
    <text x="640" y="184">11</text>
  </g>
  <text x="360" y="196" class="lbl" text-anchor="middle">Days</text>

  <!-- the contribution line (animated draw) -->
  <polyline class="line"
            points="40,166 60,165 80,164 100,163 120,162 140,161 160,160 180,159 200,158 220,157 240,156 260,155 280,154 300,153 320,100 340,80 360,155 380,150 400,152 420,155 440,160 460,162 480,163 500,164 520,165 540,165 560,166 580,166 600,165 620,166 640,166 660,165 680,165 700,166"
            stroke-dasharray="2000" stroke-dashoffset="2000">
    <animate attributeName="stroke-dashoffset" from="2000" to="0" dur="2.2s" fill="freeze" begin="0.3s"/>
  </polyline>

  <!-- peak point -->
  <circle cx="340" cy="80" r="4" fill="#000" opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.4s" fill="freeze" begin="1.8s"/>
    <animate attributeName="r" values="4;7;4" dur="1.6s" repeatCount="indefinite" begin="2.2s"/>
  </circle>

  <!-- data dots -->
  <g fill="#000">
    <circle class="cell" cx="40" cy="166" r="2" style="animation-delay: 0.3s"/>
    <circle class="cell" cx="100" cy="163" r="2" style="animation-delay: 0.5s"/>
    <circle class="cell" cx="200" cy="158" r="2" style="animation-delay: 0.8s"/>
    <circle class="cell" cx="280" cy="154" r="2" style="animation-delay: 1.0s"/>
    <circle class="cell" cx="320" cy="100" r="2" style="animation-delay: 1.2s"/>
    <circle class="cell" cx="360" cy="155" r="2" style="animation-delay: 1.4s"/>
    <circle class="cell" cx="460" cy="162" r="2" style="animation-delay: 1.6s"/>
    <circle class="cell" cx="580" cy="166" r="2" style="animation-delay: 1.8s"/>
  </g>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════ 05 / THE ROUTE — animated timeline ═══════════════════════════════════════════════ -->
<table width="100%"><tr>
<td align="left">

# 05 &nbsp; <sub><b>THE ROUTE</b></sub>

</td>
<td align="right">

`~/05-journey`

</td>
</tr></table>

<table width="100%"><tr>
<td align="left"><sub>THE ROUTE SO FAR</sub></td>
<td align="right"><sub>FIG. 03</sub></td>
</tr></table>

<br/>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 220" font-family="ui-monospace, 'JetBrains Mono', Menlo, Consolas, monospace" font-size="12" fill="#000">
  <style>
    .year { font-size: 12px; font-weight: 700; letter-spacing: 2px; opacity: 0; animation: fadein 0.5s ease-out forwards; }
    .label { font-size: 11px; fill: #333; opacity: 0; animation: fadein 0.5s ease-out forwards; }
    .sub { font-size: 9px; fill: #666; opacity: 0; animation: fadein 0.5s ease-out forwards; }
    .track { stroke: #000; stroke-width: 1.2; stroke-dasharray: 1200; stroke-dashoffset: 1200; animation: draw 1.6s ease-out forwards; }
    .dot { fill: #000; opacity: 0; animation: pop 0.4s ease-out forwards; }
    .dot-pulse { fill: none; stroke: #000; stroke-width: 1.2; opacity: 0; animation: halo 2.4s ease-out infinite; }
    @keyframes draw { to { stroke-dashoffset: 0; } }
    @keyframes pop { to { opacity: 1; } }
    @keyframes fadein { to { opacity: 1; } }
    @keyframes halo { 0% { r: 5; opacity: 0.6; } 100% { r: 14; opacity: 0; } }
  </style>

  <!-- Main timeline track -->
  <line class="track" x1="50" y1="110" x2="1150" y2="110"/>

  <!-- Stop 1: 2023 — first commit / VIT -->
  <g>
    <circle class="dot-pulse" cx="150" cy="110" r="5" style="animation-delay: 0.5s"/>
    <circle class="dot" cx="150" cy="110" r="5" style="animation-delay: 0.5s"/>
    <text class="year" x="150" y="80" text-anchor="middle" style="animation-delay: 0.6s">2023</text>
    <text class="label" x="150" y="55" text-anchor="middle" style="animation-delay: 0.7s">first commit</text>
    <text class="sub" x="150" y="140" text-anchor="middle" style="animation-delay: 0.8s">VIT — BCA · AIML</text>
  </g>

  <!-- Stop 2: 2024 — iSpace club -->
  <g>
    <circle class="dot-pulse" cx="370" cy="110" r="5" style="animation-delay: 0.8s"/>
    <circle class="dot" cx="370" cy="110" r="5" style="animation-delay: 0.8s"/>
    <text class="year" x="370" y="80" text-anchor="middle" style="animation-delay: 0.9s">2024</text>
    <text class="label" x="370" y="55" text-anchor="middle" style="animation-delay: 1.0s">iSpace Club</text>
    <text class="sub" x="370" y="140" text-anchor="middle" style="animation-delay: 1.1s">Web &amp; App Dev</text>
  </g>

  <!-- Stop 3: 2025 — Techgentsia / Web UI -->
  <g>
    <circle class="dot-pulse" cx="590" cy="110" r="5" style="animation-delay: 1.1s"/>
    <circle class="dot" cx="590" cy="110" r="5" style="animation-delay: 1.1s"/>
    <text class="year" x="590" y="80" text-anchor="middle" style="animation-delay: 1.2s">2025</text>
    <text class="label" x="590" y="55" text-anchor="middle" style="animation-delay: 1.3s">Techgentsia</text>
    <text class="sub" x="590" y="140" text-anchor="middle" style="animation-delay: 1.4s">Web UI Intern</text>
  </g>

  <!-- Stop 4: 2026 — Ambian/Research -->
  <g>
    <circle class="dot-pulse" cx="810" cy="110" r="5" style="animation-delay: 1.4s"/>
    <circle class="dot" cx="810" cy="110" r="5" style="animation-delay: 1.4s"/>
    <text class="year" x="810" y="80" text-anchor="middle" style="animation-delay: 1.5s">2026</text>
    <text class="label" x="810" y="55" text-anchor="middle" style="animation-delay: 1.6s">SRIP · Secure Solutions</text>
    <text class="sub" x="810" y="140" text-anchor="middle" style="animation-delay: 1.7s">Research &amp; Network Security</text>
  </g>

  <!-- Stop 5: 2026+ — now / next -->
  <g>
    <circle class="dot-pulse" cx="1030" cy="110" r="5" style="animation-delay: 1.7s"/>
    <circle class="dot" cx="1030" cy="110" r="5" style="animation-delay: 1.7s"/>
    <text class="year" x="1030" y="80" text-anchor="middle" style="animation-delay: 1.8s">2026 →</text>
    <text class="label" x="1030" y="55" text-anchor="middle" style="animation-delay: 1.9s">the interesting part</text>
    <text class="sub" x="1030" y="140" text-anchor="middle" style="animation-delay: 2.0s">NOW · open to internships</text>
  </g>
</svg>

</div>

---

| year | role |
|------|------|
| **2026** | **Secure Solutions · Network Security Intern · Kochi** — installed, configured, and managed FortiGate firewalls · configured firewall policies, NAT, VLANs, IPsec VPNs · implemented IPS, Web Filtering, AV, Application Control · monitored firewall logs and security events |
| **2026** | **VIT · Summer Research Intern (SRIP 2026)** — research pipeline combining confidence scoring, named-entity routing, evidence retrieval and contradiction checks · applied to threat-detection workflows |
| **2025** | **Techgentsia Software Technologies · Web UI Development Intern · Infopark Pallipuram** — assisted in developing responsive web UIs · collaborated with dev teams on front-end design and testing |
| **2023 – 2026** | **Vellore Institute of Technology · BCA — Specialized in AIML** · CGPA 7.67/10 · coursework: AI, ML, Computer Networks, DBMS, Programming, Software Development |

---

<!-- ═══════════════════════════════════════════════ 06 / STACK ═══════════════════════════════════════════════ -->
<table width="100%"><tr>
<td align="left">

# 06 &nbsp; <sub><b>STACK</b></sub>

</td>
<td align="right">

`~/06-stack`

</td>
</tr></table>

<br/>

| | |
|---|---|
| **LANGUAGES** | Python · JavaScript · SQL · Bash · C/C++ · HTML/CSS |
| **SECURITY**  | FortiGate · Nmap · Wireshark · Linux · TCP/IP · VLAN · NAT · VPN · IPSec |
| **DATA / ML** | Pandas · NumPy · Scikit-learn · NLTK · TF-IDF · Matplotlib · Seaborn · Streamlit |
| **WEB**       | HTML · CSS · JavaScript · Responsive UI · React (basics) |
| **NETWORK**   | Scapy · Socket · Packet Analysis · Protocol Inspection · Nmap |
| **TERMINAL**  | TUI / CLI · Linux shell · keyboard-driven workflows |
| **TOOLING**   | Git · GitHub · Docker (basics) · Jupyter · VS Code · Figma · Postman |

---

<div align="center">

<sub>end of transmission — arjunkb45@gmail.com</sub>

<sub>↑ built from a one-person build pipeline · `&lt;3` open source</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=000000&height=80&section=footer&text=&fontSize=0" width="100%" alt=""/>

</div>
