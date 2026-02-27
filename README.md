<!-- ANIMATED PIXEL ART TERMINAL BANNER -->
<div align="center">

<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <pattern id="scanlines" x="0" y="0" width="800" height="4" patternUnits="userSpaceOnUse">
      <rect width="800" height="2" fill="rgba(0,0,0,0.15)"/>
    </pattern>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow-strong" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="pixel-grid" x="0" y="0" width="4" height="4" patternUnits="userSpaceOnUse">
      <rect width="4" height="4" fill="none" stroke="rgba(0,255,65,0.03)" stroke-width="0.5"/>
    </pattern>
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#000000"/>
      <stop offset="50%" style="stop-color:#030a03"/>
      <stop offset="100%" style="stop-color:#000000"/>
    </linearGradient>
    <linearGradient id="line-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="20%" style="stop-color:#00ff41"/>
      <stop offset="80%" style="stop-color:#00ff41"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
    <linearGradient id="text-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ff41"/>
      <stop offset="50%" style="stop-color:#ffffff"/>
      <stop offset="100%" style="stop-color:#00ff41"/>
    </linearGradient>
  </defs>

  <!-- Background -->
  <rect width="800" height="200" fill="url(#bg-grad)"/>
  <rect width="800" height="200" fill="url(#pixel-grid)"/>

  <!-- Border frame - pixel art style -->
  <rect x="0" y="0" width="800" height="3" fill="#00ff41" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="0" y="197" width="800" height="3" fill="#00ff41" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="0" y="0" width="3" height="200" fill="#00ff41" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="797" y="0" width="3" height="200" fill="#00ff41" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3s" repeatCount="indefinite"/>
  </rect>
  <!-- Pixel corners -->
  <rect x="0" y="0" width="12" height="12" fill="#00ff41"/>
  <rect x="788" y="0" width="12" height="12" fill="#00ff41"/>
  <rect x="0" y="188" width="12" height="12" fill="#00ff41"/>
  <rect x="788" y="188" width="12" height="12" fill="#00ff41"/>
  <rect x="3" y="3" width="6" height="6" fill="#000000"/>
  <rect x="791" y="3" width="6" height="6" fill="#000000"/>
  <rect x="3" y="191" width="6" height="6" fill="#000000"/>
  <rect x="791" y="191" width="6" height="6" fill="#000000"/>

  <!-- PIXEL ART AKIRA MOTORCYCLE - Left side -->
  <!-- Speed lines (behind bike) -->
  <line x1="8" y1="104" x2="48" y2="104" stroke="#00ff41" stroke-width="2" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0;0.7" dur="0.25s" repeatCount="indefinite"/>
  </line>
  <line x1="8" y1="112" x2="38" y2="112" stroke="#00ff41" stroke-width="1.5" opacity="0.5">
    <animate attributeName="opacity" values="0.5;0;0.5" dur="0.3s" repeatCount="indefinite"/>
  </line>
  <line x1="8" y1="119" x2="44" y2="119" stroke="#00ff41" stroke-width="1" opacity="0.4">
    <animate attributeName="opacity" values="0.4;0;0.4" dur="0.4s" repeatCount="indefinite"/>
  </line>
  <line x1="8" y1="97" x2="32" y2="97" stroke="#00ff41" stroke-width="1" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0;0.3" dur="0.35s" repeatCount="indefinite"/>
  </line>
  <line x1="8" y1="127" x2="28" y2="127" stroke="#00ff41" stroke-width="1" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0;0.3" dur="0.45s" repeatCount="indefinite"/>
  </line>

  <!-- Rear wheel -->
  <g>
    <circle cx="72" cy="126" r="30" fill="none" stroke="#00ff41" stroke-width="4" opacity="0.85"/>
    <circle cx="72" cy="126" r="20" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.5"/>
    <circle cx="72" cy="126" r="7" fill="#00ff41" opacity="0.9"/>
    <g transform-origin="72 126">
      <line x1="72" y1="96" x2="72" y2="156" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <line x1="42" y1="126" x2="102" y2="126" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <line x1="51" y1="105" x2="93" y2="147" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <line x1="93" y1="105" x2="51" y2="147" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <animateTransform attributeName="transform" type="rotate" from="0 72 126" to="360 72 126" dur="0.9s" repeatCount="indefinite"/>
    </g>
  </g>

  <!-- Front wheel -->
  <g>
    <circle cx="178" cy="126" r="30" fill="none" stroke="#00ff41" stroke-width="4" opacity="0.85"/>
    <circle cx="178" cy="126" r="20" fill="none" stroke="#00ff41" stroke-width="2" opacity="0.5"/>
    <circle cx="178" cy="126" r="7" fill="#00ff41" opacity="0.9"/>
    <g transform-origin="178 126">
      <line x1="178" y1="96" x2="178" y2="156" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <line x1="148" y1="126" x2="208" y2="126" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <line x1="157" y1="105" x2="199" y2="147" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <line x1="199" y1="105" x2="157" y2="147" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
      <animateTransform attributeName="transform" type="rotate" from="0 178 126" to="360 178 126" dur="0.9s" repeatCount="indefinite"/>
    </g>
  </g>

  <!-- Bike chassis - Akira style low long frame -->
  <polygon points="65,100 175,100 185,112 175,120 65,120 52,112" fill="#001400" stroke="#00ff41" stroke-width="2" opacity="0.9"/>
  <!-- Upper fairing -->
  <polygon points="90,88 170,88 185,100 65,100 72,92" fill="#002800" stroke="#00ff41" stroke-width="1.5" opacity="0.85"/>
  <!-- Front fairing (nose) -->
  <polygon points="175,88 205,110 185,100 178,96" fill="#001400" stroke="#00ff41" stroke-width="2" opacity="0.9"/>
  <!-- Windshield -->
  <polygon points="155,80 175,80 185,96 165,96" fill="#004400" stroke="#00ff41" stroke-width="1" opacity="0.7"/>
  <!-- Tail section -->
  <polygon points="52,100 72,100 72,120 52,120 42,112" fill="#001400" stroke="#00ff41" stroke-width="1.5" opacity="0.8"/>
  <!-- Exhaust -->
  <rect x="38" y="114" width="36" height="5" rx="2" fill="#00ff41" opacity="0.6"/>
  <rect x="36" y="115" width="6" height="3" fill="#00ff41" opacity="0.4"/>
  <!-- Handlebar -->
  <rect x="168" y="84" width="22" height="4" rx="2" fill="#00ff41" opacity="0.8"/>

  <!-- RIDER pixel art - leaning forward Akira pose -->
  <!-- Legs / lower body -->
  <rect x="105" y="92" width="40" height="12" rx="2" fill="#00ff41" opacity="0.75"/>
  <!-- Torso (leaning forward aggressively) -->
  <polygon points="120,60 148,72 148,94 108,94 108,76" fill="#00ff41" opacity="0.85"/>
  <!-- Helmet -->
  <rect x="118" y="46" width="26" height="20" rx="4" fill="#00ff41" opacity="0.95"/>
  <!-- Visor -->
  <rect x="120" y="50" width="22" height="8" rx="1" fill="#000000" opacity="1"/>
  <rect x="121" y="51" width="20" height="6" rx="1" fill="#001a00" opacity="0.9"/>
  <!-- Visor glow -->
  <rect x="121" y="51" width="20" height="6" rx="1" fill="#00ff41" opacity="0.1">
    <animate attributeName="opacity" values="0.1;0.3;0.1" dur="2s" repeatCount="indefinite"/>
  </rect>
  <!-- Arms stretched forward -->
  <rect x="144" y="70" width="30" height="7" rx="3" fill="#00ff41" opacity="0.8"/>
  <rect x="170" y="72" width="14" height="5" rx="2" fill="#00ff41" opacity="0.7"/>

  <!-- Scanlines -->
  <rect width="800" height="200" fill="url(#scanlines)" opacity="0.35"/>

  <!-- MAIN TITLE -->
  <g filter="url(#glow-strong)">
    <text x="410" y="82"
          font-family="'Courier New', Courier, monospace"
          font-size="50"
          font-weight="bold"
          fill="url(#text-grad)"
          text-anchor="middle"
          letter-spacing="14">MANTEIGHA
      <animate attributeName="opacity" values="1;0.85;1;0.92;1" dur="4s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Subtitle -->
  <g filter="url(#glow)">
    <text x="410" y="112"
          font-family="'Courier New', Courier, monospace"
          font-size="12"
          fill="#00ff41"
          text-anchor="middle"
          letter-spacing="4"
          opacity="0.9">RUBÉN LEMOS GÓMEZ · PENTESTER IN PROGRESS
      <animate attributeName="opacity" values="0.9;0.5;0.9" dur="2.5s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- Divider line -->
  <rect x="240" y="120" width="340" height="1" fill="url(#line-grad)" opacity="0.7"/>

  <!-- Terminal prompt -->
  <g filter="url(#glow)">
    <text x="410" y="146"
          font-family="'Courier New', Courier, monospace"
          font-size="11"
          fill="#00ff41"
          text-anchor="middle"
          letter-spacing="1.5"
          opacity="0.75">root@manteigha:~$ pentakit auto --company "target"
    </text>
    <rect x="604" y="135" width="9" height="13" fill="#00ff41">
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- Circuit decoration RIGHT -->
  <line x1="700" y1="18" x2="700" y2="58" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <line x1="720" y1="18" x2="720" y2="78" stroke="#00ff41" stroke-width="1.5" opacity="0.3"/>
  <line x1="740" y1="18" x2="740" y2="48" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <line x1="760" y1="18" x2="760" y2="68" stroke="#00ff41" stroke-width="1.5" opacity="0.3"/>
  <line x1="700" y1="38" x2="720" y2="38" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <line x1="720" y1="58" x2="740" y2="58" stroke="#00ff41" stroke-width="1.5" opacity="0.3"/>
  <line x1="740" y1="33" x2="760" y2="33" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <rect x="696" y="34" width="8" height="8" fill="#00ff41" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="1.5s" repeatCount="indefinite"/>
  </rect>
  <rect x="716" y="54" width="8" height="8" fill="#00ff41" opacity="0.5">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2s" repeatCount="indefinite"/>
  </rect>
  <rect x="736" y="29" width="8" height="8" fill="#00ff41" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="1.2s" repeatCount="indefinite"/>
  </rect>
  <rect x="756" y="64" width="8" height="8" fill="#00ff41" opacity="0.4">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="1.8s" repeatCount="indefinite"/>
  </rect>
  <line x1="700" y1="158" x2="700" y2="182" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <line x1="720" y1="148" x2="720" y2="182" stroke="#00ff41" stroke-width="1.5" opacity="0.3"/>
  <line x1="740" y1="158" x2="740" y2="182" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <line x1="760" y1="153" x2="760" y2="182" stroke="#00ff41" stroke-width="1.5" opacity="0.3"/>
  <line x1="700" y1="163" x2="720" y2="163" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <line x1="720" y1="153" x2="740" y2="153" stroke="#00ff41" stroke-width="1.5" opacity="0.3"/>
  <line x1="740" y1="168" x2="760" y2="168" stroke="#00ff41" stroke-width="1.5" opacity="0.4"/>
  <rect x="696" y="159" width="8" height="8" fill="#00ff41" opacity="0.5">
    <animate attributeName="opacity" values="0.5;1;0.5" dur="2.2s" repeatCount="indefinite"/>
  </rect>
  <rect x="716" y="149" width="8" height="8" fill="#00ff41" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="1.7s" repeatCount="indefinite"/>
  </rect>
  <rect x="736" y="164" width="8" height="8" fill="#00ff41" opacity="0.4">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="1.3s" repeatCount="indefinite"/>
  </rect>
  <rect x="756" y="154" width="8" height="8" fill="#00ff41" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0.1;0.6" dur="2.5s" repeatCount="indefinite"/>
  </rect>

  <!-- Location tag -->
  <text x="18" y="185" font-family="'Courier New', monospace" font-size="9" fill="#00ff41" opacity="0.5" letter-spacing="1">VIGO · GALICIA · ESP</text>
  <!-- Version tag -->
  <text x="782" y="185" font-family="'Courier New', monospace" font-size="9" fill="#00ff41" opacity="0.5" text-anchor="end" letter-spacing="1">v1.0.0</text>
</svg>

</div>

<!-- Terminal de bienvenida -->
<div align="center">

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   root@manteigha:~$ whoami                                          │
│                                                                     │
│   > Rubén Lemos Gómez — Cybersecurity student & developer           │
│   > Building PentaKit: the toolkit Mr. Robot would use              │
│   > Based in Vigo, Galicia 🇪🇸                                      │
│   > Currently: breaking things ethically                            │
│                                                                     │
│   root@manteigha:~$ █                                               │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

</div>

---

## `> cat about_me.txt`

```python
class Manteigha:
    name       = "Rubén Lemos Gómez"
    alias      = "Manteigha"
    location   = "Vigo, Galicia, Spain"
    focus      = ["Cybersecurity", "Bug Bounty", "Pentesting", "Python"]
    building   = "PentaKit — Business Pentesting Toolkit"
    goal       = "Make PentaKit the toolkit every security researcher uses"
    ctf_player = True
    currently  = "Breaking things. Ethically."

    def __init__(self):
        self.mindset = "If you can't hack it, you don't understand it"
```

---

## `> ./pentakit --showcase`

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                  🔐  P E N T A K I T  v1.0                          ║
║             Professional Business Penetration Testing                ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║   $ pentakit auto --company "Target Corp"                            ║
║                                                                      ║
║   [✓] OSINT............. 10+ sources · emails · breaches · leaks    ║
║   [✓] Recon............. subdomains · ports · tech fingerprinting   ║
║   [✓] Bug Bounty........ 9000+ Nuclei templates · CVE + EPSS + KEV  ║
║   [✓] Web Hacking....... XSS · SQLi · SSRF · XXE · CORS · LFI      ║
║   [✓] Passwords......... credential stuffing from breach data        ║
║   [✓] Network........... MITM · ARP · SSL Strip · packet capture    ║
║   [✓] Reports........... HTML · PDF · JSON · HackerOne ready        ║
║                                                                      ║
║   🔴 4 critical  🟠 9 high  🟡 6 medium  🟢 2 low                   ║
║   📄 Full report → reports/targetcorp_2025.pdf                      ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

> *"The first open-source toolkit that goes from company name to full pentest report in a single command."*
>
> **Competing with Burp Suite Pro ($449/yr) and Nessus ($3,990/yr). For free.**

[![PentaKit](https://img.shields.io/badge/🔐_PentaKit-WIP-00ff41?style=for-the-badge&labelColor=0d0d0d)](https://github.com/RubenLemosGomez)
[![Status](https://img.shields.io/badge/Status-In_Development-ff6600?style=for-the-badge&labelColor=0d0d0d)]()
[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0d0d0d)]()

</div>

---

## `> cat tech_stack.yaml`

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-0d0d0d?style=for-the-badge&logo=python&logoColor=00ff41)
![JavaScript](https://img.shields.io/badge/JavaScript-0d0d0d?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-0d0d0d?style=for-the-badge&logo=html5&logoColor=E34F26)
![Bash](https://img.shields.io/badge/Bash-0d0d0d?style=for-the-badge&logo=gnubash&logoColor=00ff41)

**Security Tools**

![Nmap](https://img.shields.io/badge/Nmap-0d0d0d?style=for-the-badge&logoColor=00ff41)
![Nuclei](https://img.shields.io/badge/Nuclei-0d0d0d?style=for-the-badge&logoColor=00ff41)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-0d0d0d?style=for-the-badge&logo=burpsuite&logoColor=FF6633)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-0d0d0d?style=for-the-badge&logo=kalilinux&logoColor=557C94)
![Wireshark](https://img.shields.io/badge/Wireshark-0d0d0d?style=for-the-badge&logo=wireshark&logoColor=1679A7)

**Stack & Infrastructure**

![MongoDB](https://img.shields.io/badge/MongoDB-0d0d0d?style=for-the-badge&logo=mongodb&logoColor=47A248)
![Docker](https://img.shields.io/badge/Docker-0d0d0d?style=for-the-badge&logo=docker&logoColor=2496ED)
![FastAPI](https://img.shields.io/badge/FastAPI-0d0d0d?style=for-the-badge&logo=fastapi&logoColor=009688)

</div>

---

## `> git log --oneline --all`

```
🔐 feat: PentaKit — Business Pentesting Toolkit          [WIP]
   ├── Auto Mode: company name → full pentest report
   ├── OSINT: 10+ API sources (Shodan, Censys, FOFA...)
   ├── Bug Bounty: Nuclei + CVE + EPSS + KEV + 15 vuln types
   ├── Web: XSS · SQLi · CSRF · SSRF · XXE · CORS · LFI
   ├── MongoDB persistence + scan history + comparativa
   └── Reports: HTML · PDF · JSON · HackerOne format

🐍 feat: Pokédex interactiva en terminal (Python + PokeAPI)
🌐 feat: Landing page personal
📄 feat: DTD ejercicio XML editorial
```

---

## `> ./stats --user manteigha`

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=RubenLemosGomez&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d0d0d&title_color=00ff41&icon_color=00ff41&text_color=ffffff"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RubenLemosGomez&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d0d0d&title_color=00ff41&text_color=ffffff"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=RubenLemosGomez&theme=chartreuse-dark&hide_border=true&background=0d0d0d&stroke=00ff41&ring=00ff41&fire=ff6600&currStreakLabel=00ff41"/>
</div>

---

## `> cat philosophy.txt`

<div align="center">

```
"The only secure system is one that's been properly tested.
 Everything else is just waiting to be found."

                                        — Manteigha
```

</div>

---

## `> ./contact --list`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-RubenLemosGomez-0d0d0d?style=for-the-badge&logo=github&logoColor=00ff41)](https://github.com/RubenLemosGomez)
[![Location](https://img.shields.io/badge/📍_Vigo-Galicia,_Spain-0d0d0d?style=for-the-badge)]()

```
root@manteigha:~$ echo "Open to bug bounty collabs, CTF teams & security research"
> Open to bug bounty collabs, CTF teams & security research
root@manteigha:~$ █
```

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=RubenLemosGomez&color=00ff41&style=flat-square&label=profile+views"/>
</div>
