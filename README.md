<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!--           ANIMATED HERO BANNER — pure SVG inline           -->
<!-- ═══════════════════════════════════════════════════════════ -->

<svg width="860" height="200" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d0d1a"/>
      <stop offset="50%" style="stop-color:#0a1628"/>
      <stop offset="100%" style="stop-color:#0d0d1a"/>
    </linearGradient>
    <filter id="neonGlow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="titleGlow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <radialGradient id="particleGrad" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00f5ff;stop-opacity:0"/>
    </radialGradient>
    <clipPath id="bannerClip">
      <rect width="860" height="200" rx="16"/>
    </clipPath>
  </defs>
  <g clip-path="url(#bannerClip)">
    <rect width="860" height="200" fill="url(#bgGrad)"/>
    <!-- Animated grid lines -->
    <g opacity="0.15" stroke="#00f5ff" stroke-width="0.5">
      <line x1="0" y1="40" x2="860" y2="40"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/></line>
      <line x1="0" y1="80" x2="860" y2="80"><animate attributeName="opacity" values="0.5;0.2;0.5" dur="2.5s" repeatCount="indefinite"/></line>
      <line x1="0" y1="120" x2="860" y2="120"><animate attributeName="opacity" values="0.2;0.6;0.2" dur="4s" repeatCount="indefinite"/></line>
      <line x1="0" y1="160" x2="860" y2="160"><animate attributeName="opacity" values="0.4;0.1;0.4" dur="3.5s" repeatCount="indefinite"/></line>
      <line x1="120" y1="0" x2="120" y2="200"><animate attributeName="opacity" values="0.3;0.7;0.3" dur="2s" repeatCount="indefinite"/></line>
      <line x1="280" y1="0" x2="280" y2="200"><animate attributeName="opacity" values="0.5;0.2;0.5" dur="3s" repeatCount="indefinite"/></line>
      <line x1="430" y1="0" x2="430" y2="200"><animate attributeName="opacity" values="0.2;0.5;0.2" dur="2.5s" repeatCount="indefinite"/></line>
      <line x1="580" y1="0" x2="580" y2="200"><animate attributeName="opacity" values="0.4;0.8;0.4" dur="3.5s" repeatCount="indefinite"/></line>
      <line x1="740" y1="0" x2="740" y2="200"><animate attributeName="opacity" values="0.3;0.6;0.3" dur="2.8s" repeatCount="indefinite"/></line>
    </g>
    <!-- Floating orbs -->
    <circle cx="80" cy="50" r="60" fill="#00f5ff" opacity="0.04">
      <animate attributeName="cx" values="80;120;80" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="50;90;50" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="780" cy="150" r="80" fill="#bf5fff" opacity="0.05">
      <animate attributeName="cx" values="780;740;780" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="150;110;150" dur="5s" repeatCount="indefinite"/>
    </circle>
    <!-- Shooting particles -->
    <circle cx="0" cy="30" r="2" fill="#00f5ff" opacity="0.9" filter="url(#neonGlow)">
      <animate attributeName="cx" values="-10;870" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="0" cy="80" r="1.5" fill="#bf5fff" opacity="0.8" filter="url(#neonGlow)">
      <animate attributeName="cx" values="-10;870" dur="3.8s" begin="1s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="3.8s" begin="1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="0" cy="160" r="2" fill="#ff6b6b" opacity="0.9" filter="url(#neonGlow)">
      <animate attributeName="cx" values="-10;870" dur="3s" begin="0.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="3s" begin="0.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="0" cy="120" r="1" fill="#00ffaa" opacity="0.7" filter="url(#neonGlow)">
      <animate attributeName="cx" values="-10;870" dur="4.5s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="4.5s" begin="2s" repeatCount="indefinite"/>
    </circle>
    <!-- Neon border -->
    <rect x="1" y="1" width="858" height="198" rx="15" fill="none" stroke="#00f5ff" stroke-width="1.5" opacity="0.5">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
    </rect>
    <!-- Corner accents -->
    <path d="M20,8 L8,8 L8,20" fill="none" stroke="#00f5ff" stroke-width="2.5">
      <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
    </path>
    <path d="M840,8 L852,8 L852,20" fill="none" stroke="#00f5ff" stroke-width="2.5">
      <animate attributeName="opacity" values="0.8;0.3;0.8" dur="2s" repeatCount="indefinite"/>
    </path>
    <path d="M20,192 L8,192 L8,180" fill="none" stroke="#bf5fff" stroke-width="2.5">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2.5s" repeatCount="indefinite"/>
    </path>
    <path d="M840,192 L852,192 L852,180" fill="none" stroke="#bf5fff" stroke-width="2.5">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="2.5s" repeatCount="indefinite"/>
    </path>
    <!-- Main Title with glitch -->
    <text x="430" y="88" font-family="'Courier New', monospace" font-size="52" font-weight="900" fill="#00f5ff" text-anchor="middle" filter="url(#titleGlow)" letter-spacing="4">MANN TOMAR</text>
    <text x="430" y="88" font-family="'Courier New', monospace" font-size="52" font-weight="900" fill="#ff6b6b" text-anchor="middle" opacity="0" letter-spacing="4">MANN TOMAR
      <animate attributeName="x" values="430;427;433;430" dur="0.2s" begin="3s" repeatCount="indefinite" calcMode="discrete"/>
      <animate attributeName="opacity" values="0;0.5;0;0.3;0" dur="0.3s" begin="3s" repeatCount="indefinite"/>
    </text>
    <!-- Subtitle -->
    <text x="430" y="128" font-family="'Courier New', monospace" font-size="16" fill="#aaaacc" text-anchor="middle" letter-spacing="3">&lt; PASSIONATE ENGINEER FROM INDIA /&gt;</text>
    <!-- Animated underline -->
    <line x1="200" y1="140" x2="660" y2="140" stroke="#00f5ff" stroke-width="1" opacity="0.4">
      <animate attributeName="x1" values="430;200;430" dur="1.5s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.2 1;0.4 0 0.2 1"/>
      <animate attributeName="x2" values="430;660;430" dur="1.5s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.2 1;0.4 0 0.2 1"/>
    </line>
    <!-- Status badges -->
    <rect x="270" y="158" width="140" height="26" rx="13" fill="#00f5ff" opacity="0.15" stroke="#00f5ff" stroke-width="1"/>
    <text x="340" y="175" font-family="'Courier New', monospace" font-size="11" fill="#00f5ff" text-anchor="middle" font-weight="bold">LEARNING C</text>
    <rect x="450" y="158" width="140" height="26" rx="13" fill="#bf5fff" opacity="0.15" stroke="#bf5fff" stroke-width="1"/>
    <text x="520" y="175" font-family="'Courier New', monospace" font-size="11" fill="#bf5fff" text-anchor="middle" font-weight="bold">HTML / CSS / C</text>
    <!-- Scan line -->
    <rect x="0" y="0" width="860" height="3" fill="url(#particleGrad)" opacity="0.3">
      <animate attributeName="y" values="-3;203" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.5;0.5;0" dur="3s" repeatCount="indefinite"/>
    </rect>
  </g>
</svg>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--              ANIMATED SKILL BARS — inline SVG              -->
<!-- ═══════════════════════════════════════════════════════════ -->

<br/>

<svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="htmlGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff6b35"/>
      <stop offset="100%" style="stop-color:#ff4500"/>
    </linearGradient>
    <linearGradient id="cssGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#264de4"/>
      <stop offset="100%" style="stop-color:#00d9ff"/>
    </linearGradient>
    <linearGradient id="cGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00599c"/>
      <stop offset="100%" style="stop-color:#004482"/>
    </linearGradient>
    <linearGradient id="pyGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3776ab"/>
      <stop offset="100%" style="stop-color:#ffd43b"/>
    </linearGradient>
    <linearGradient id="gitGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f05032"/>
      <stop offset="100%" style="stop-color:#ff8c69"/>
    </linearGradient>
    <filter id="barGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="skillClip"><rect width="860" height="280" rx="14"/></clipPath>
  </defs>
  <g clip-path="url(#skillClip)">
    <rect width="860" height="280" fill="#0a0a14"/>
    <rect x="1" y="1" width="858" height="278" rx="13" fill="none" stroke="#1a1a2e" stroke-width="1"/>
    <text x="430" y="36" font-family="'Courier New', monospace" font-size="14" fill="#00f5ff" text-anchor="middle" letter-spacing="6" font-weight="bold">SKILLS &amp; ARSENAL</text>
    <line x1="160" y1="46" x2="700" y2="46" stroke="#00f5ff" stroke-width="0.5" opacity="0.3"/>
    <!-- HTML Bar -->
    <text x="40" y="84" font-family="'Courier New', monospace" font-size="13" fill="#ff6b35" font-weight="bold">HTML5</text>
    <text x="820" y="84" font-family="'Courier New', monospace" font-size="12" fill="#ff6b35" text-anchor="end">85%</text>
    <rect x="40" y="90" width="780" height="10" rx="5" fill="#1a1a2e"/>
    <rect x="40" y="90" width="0" height="10" rx="5" fill="url(#htmlGrad)" filter="url(#barGlow)">
      <animate attributeName="width" from="0" to="663" dur="2s" begin="0.2s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
    </rect>
    <!-- CSS Bar -->
    <text x="40" y="126" font-family="'Courier New', monospace" font-size="13" fill="#264de4" font-weight="bold">CSS3</text>
    <text x="820" y="126" font-family="'Courier New', monospace" font-size="12" fill="#00d9ff" text-anchor="end">80%</text>
    <rect x="40" y="132" width="780" height="10" rx="5" fill="#1a1a2e"/>
    <rect x="40" y="132" width="0" height="10" rx="5" fill="url(#cssGrad)" filter="url(#barGlow)">
      <animate attributeName="width" from="0" to="624" dur="2s" begin="0.5s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
    </rect>
    <!-- C Bar -->
    <text x="40" y="168" font-family="'Courier New', monospace" font-size="13" fill="#00599c" font-weight="bold">C</text>
    <text x="820" y="168" font-family="'Courier New', monospace" font-size="12" fill="#00599c" text-anchor="end">70%</text>
    <rect x="40" y="174" width="780" height="10" rx="5" fill="#1a1a2e"/>
    <rect x="40" y="174" width="0" height="10" rx="5" fill="url(#cGrad)" filter="url(#barGlow)">
      <animate attributeName="width" from="0" to="546" dur="2s" begin="0.8s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
    </rect>
    <!-- Python Bar -->
    <text x="40" y="210" font-family="'Courier New', monospace" font-size="13" fill="#3776ab" font-weight="bold">PYTHON</text>
    <text x="820" y="210" font-family="'Courier New', monospace" font-size="12" fill="#ffd43b" text-anchor="end">55%</text>
    <rect x="40" y="216" width="780" height="10" rx="5" fill="#1a1a2e"/>
    <rect x="40" y="216" width="0" height="10" rx="5" fill="url(#pyGrad)" filter="url(#barGlow)">
      <animate attributeName="width" from="0" to="429" dur="2s" begin="1.1s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
    </rect>
    <!-- Git Bar -->
    <text x="40" y="252" font-family="'Courier New', monospace" font-size="13" fill="#f05032" font-weight="bold">GIT</text>
    <text x="820" y="252" font-family="'Courier New', monospace" font-size="12" fill="#ff8c69" text-anchor="end">65%</text>
    <rect x="40" y="258" width="780" height="10" rx="5" fill="#1a1a2e"/>
    <rect x="40" y="258" width="0" height="10" rx="5" fill="url(#gitGrad)" filter="url(#barGlow)">
      <animate attributeName="width" from="0" to="507" dur="2s" begin="1.4s" fill="freeze" calcMode="spline" keySplines="0.4 0 0.2 1"/>
    </rect>
  </g>
</svg>

</div>

---

## 🖥️ About Me

<div align="center">

<!-- ANIMATED TERMINAL SVG -->
<svg width="860" height="320" viewBox="0 0 860 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="termBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#010409"/>
    </linearGradient>
    <filter id="textGlow">
      <feGaussianBlur stdDeviation="1" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="termClip"><rect width="860" height="320" rx="12"/></clipPath>
  </defs>
  <g clip-path="url(#termClip)">
    <rect width="860" height="320" fill="url(#termBg)"/>
    <rect width="860" height="36" fill="#1c1c2e"/>
    <circle cx="20" cy="18" r="6" fill="#ff5f56"/>
    <circle cx="40" cy="18" r="6" fill="#ffbd2e"/>
    <circle cx="60" cy="18" r="6" fill="#27c93f"/>
    <text x="430" y="23" font-family="'Courier New', monospace" font-size="12" fill="#888" text-anchor="middle">mann@github: ~/profile</text>
    <rect x="0.5" y="0.5" width="859" height="319" rx="11.5" fill="none" stroke="#30363d" stroke-width="1"/>
    <!-- Staggered reveal lines -->
    <text x="20" y="66" font-family="'Courier New', monospace" font-size="13" fill="#27c93f" filter="url(#textGlow)" opacity="0">$ whoami
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="0.3s" fill="freeze"/>
    </text>
    <text x="20" y="88" font-family="'Courier New', monospace" font-size="13" fill="#58a6ff" opacity="0">  Mann Tomar — Passionate Engineer from India
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="0.8s" fill="freeze"/>
    </text>
    <text x="20" y="116" font-family="'Courier New', monospace" font-size="13" fill="#27c93f" filter="url(#textGlow)" opacity="0">$ cat info.json
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="1.3s" fill="freeze"/>
    </text>
    <text x="20" y="138" font-family="'Courier New', monospace" font-size="12" fill="#79c0ff" opacity="0">{
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="1.7s" fill="freeze"/>
    </text>
    <text x="20" y="158" font-family="'Courier New', monospace" font-size="12" opacity="0">
      <tspan fill="#ff7b72">  "name"</tspan><tspan fill="#c9d1d9">: </tspan><tspan fill="#a5d6ff">"Mann Tomar"</tspan><tspan fill="#c9d1d9">,</tspan>
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="1.9s" fill="freeze"/>
    </text>
    <text x="20" y="178" font-family="'Courier New', monospace" font-size="12" opacity="0">
      <tspan fill="#ff7b72">  "location"</tspan><tspan fill="#c9d1d9">: </tspan><tspan fill="#a5d6ff">"Mohali, Chandigarh, India"</tspan><tspan fill="#c9d1d9">,</tspan>
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="2.1s" fill="freeze"/>
    </text>
    <text x="20" y="198" font-family="'Courier New', monospace" font-size="12" opacity="0">
      <tspan fill="#ff7b72">  "learning"</tspan><tspan fill="#c9d1d9">: </tspan><tspan fill="#a5d6ff">["C", "Python", "Web Dev"]</tspan><tspan fill="#c9d1d9">,</tspan>
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="2.3s" fill="freeze"/>
    </text>
    <text x="20" y="218" font-family="'Courier New', monospace" font-size="12" opacity="0">
      <tspan fill="#ff7b72">  "ask_me_about"</tspan><tspan fill="#c9d1d9">: </tspan><tspan fill="#a5d6ff">["HTML", "CSS", "C"]</tspan><tspan fill="#c9d1d9">,</tspan>
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="2.5s" fill="freeze"/>
    </text>
    <text x="20" y="238" font-family="'Courier New', monospace" font-size="12" opacity="0">
      <tspan fill="#ff7b72">  "email"</tspan><tspan fill="#c9d1d9">: </tspan><tspan fill="#a5d6ff">"manntomar46@gmail.com"</tspan><tspan fill="#c9d1d9">,</tspan>
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="2.7s" fill="freeze"/>
    </text>
    <text x="20" y="258" font-family="'Courier New', monospace" font-size="12" opacity="0">
      <tspan fill="#ff7b72">  "fun_fact"</tspan><tspan fill="#c9d1d9">: </tspan><tspan fill="#a5d6ff">"I am a cool person"</tspan>
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="2.9s" fill="freeze"/>
    </text>
    <text x="20" y="278" font-family="'Courier New', monospace" font-size="12" fill="#79c0ff" opacity="0">}
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="3.1s" fill="freeze"/>
    </text>
    <!-- Blinking cursor -->
    <text x="20" y="302" font-family="'Courier New', monospace" font-size="13" fill="#27c93f" opacity="0">$
      <animate attributeName="opacity" values="0;1" dur="0.1s" begin="3.4s" fill="freeze"/>
    </text>
    <rect x="30" y="287" width="8" height="16" fill="#27c93f" opacity="0">
      <animate attributeName="opacity" values="0;0;1;1;0;0" dur="1s" begin="3.5s" repeatCount="indefinite"/>
    </rect>
  </g>
</svg>

</div>

---

## 📊 GitHub Stats

<div align="center">

<!-- ANIMATED STATS CARDS SVG -->
<svg width="860" height="180" viewBox="0 0 860 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#161b22"/>
    </linearGradient>
    <filter id="numGlow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="statsClip"><rect width="860" height="180" rx="12"/></clipPath>
  </defs>
  <g clip-path="url(#statsClip)">
    <rect width="860" height="180" fill="#080c10"/>
    <!-- Card 1: Contributions -->
    <rect x="10" y="10" width="258" height="160" rx="10" fill="url(#cardBg)" stroke="#21262d" stroke-width="1">
      <animate attributeName="stroke" values="#21262d;#00f5ff;#21262d" dur="3s" repeatCount="indefinite"/>
    </rect>
    <text x="139" y="50" font-family="'Courier New', monospace" font-size="10" fill="#8b949e" text-anchor="middle" letter-spacing="1">TOTAL CONTRIBUTIONS</text>
    <text x="139" y="110" font-family="'Courier New', monospace" font-size="52" font-weight="bold" fill="#00f5ff" text-anchor="middle" filter="url(#numGlow)">183</text>
    <text x="139" y="148" font-family="'Courier New', monospace" font-size="10" fill="#30363d" text-anchor="middle">Aug 2024 - Present</text>
    <circle cx="139" cy="90" r="58" fill="none" stroke="#00f5ff" stroke-width="0.8" opacity="0">
      <animate attributeName="r" values="58;75;58" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0;0.3" dur="3s" repeatCount="indefinite"/>
    </circle>
    <!-- Card 2: Streak -->
    <rect x="301" y="10" width="258" height="160" rx="10" fill="url(#cardBg)" stroke="#21262d" stroke-width="1">
      <animate attributeName="stroke" values="#21262d;#ff6b6b;#21262d" dur="3s" begin="1s" repeatCount="indefinite"/>
    </rect>
    <text x="430" y="50" font-family="'Courier New', monospace" font-size="10" fill="#8b949e" text-anchor="middle" letter-spacing="1">LONGEST STREAK</text>
    <text x="430" y="105" font-family="'Courier New', monospace" font-size="52" font-weight="bold" fill="#ff6b6b" text-anchor="middle" filter="url(#numGlow)">4</text>
    <text x="430" y="128" font-family="'Courier New', monospace" font-size="13" fill="#ff6b6b" text-anchor="middle">days</text>
    <text x="430" y="148" font-family="'Courier New', monospace" font-size="10" fill="#30363d" text-anchor="middle">Oct 3 - Oct 6, 2024</text>
    <circle cx="430" cy="95" r="58" fill="none" stroke="#ff6b6b" stroke-width="0.8" opacity="0">
      <animate attributeName="r" values="58;75;58" dur="3s" begin="1s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0;0.3" dur="3s" begin="1s" repeatCount="indefinite"/>
    </circle>
    <!-- Card 3: Repos -->
    <rect x="592" y="10" width="258" height="160" rx="10" fill="url(#cardBg)" stroke="#21262d" stroke-width="1">
      <animate attributeName="stroke" values="#21262d;#bf5fff;#21262d" dur="3s" begin="2s" repeatCount="indefinite"/>
    </rect>
    <text x="721" y="50" font-family="'Courier New', monospace" font-size="10" fill="#8b949e" text-anchor="middle" letter-spacing="1">PUBLIC REPOS</text>
    <text x="721" y="110" font-family="'Courier New', monospace" font-size="52" font-weight="bold" fill="#bf5fff" text-anchor="middle" filter="url(#numGlow)">6+</text>
    <text x="721" y="148" font-family="'Courier New', monospace" font-size="10" fill="#30363d" text-anchor="middle">github.com/MANN-TOMAR</text>
    <circle cx="721" cy="90" r="58" fill="none" stroke="#bf5fff" stroke-width="0.8" opacity="0">
      <animate attributeName="r" values="58;75;58" dur="3s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;0;0.3" dur="3s" begin="2s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

</div>

---

## 🔗 Connect with Me

<div align="center">

<!-- ANIMATED SOCIAL BUTTONS SVG -->
<svg width="700" height="80" viewBox="0 0 700 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <clipPath id="socialClip"><rect width="700" height="80" rx="8"/></clipPath>
  </defs>
  <g clip-path="url(#socialClip)">
    <rect width="700" height="80" fill="#080c10"/>
    <a href="https://www.linkedin.com/in/mann-tomar-054b63321">
      <rect x="20" y="18" width="140" height="44" rx="8" fill="#0a66c2">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="2s" repeatCount="indefinite"/>
      </rect>
      <text x="90" y="46" font-family="'Courier New', monospace" font-size="13" fill="white" text-anchor="middle" font-weight="bold">in  LinkedIn</text>
    </a>
    <a href="https://instagram.com/mann_tomar_jaat_boy">
      <rect x="180" y="18" width="140" height="44" rx="8" fill="#e1306c">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="2s" begin="0.5s" repeatCount="indefinite"/>
      </rect>
      <text x="250" y="46" font-family="'Courier New', monospace" font-size="13" fill="white" text-anchor="middle" font-weight="bold">Instagram</text>
    </a>
    <a href="https://github.com/MANN-TOMAR">
      <rect x="340" y="18" width="140" height="44" rx="8" fill="#21262d" stroke="#00f5ff" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite"/>
      </rect>
      <text x="410" y="46" font-family="'Courier New', monospace" font-size="13" fill="white" text-anchor="middle" font-weight="bold">GitHub</text>
    </a>
    <a href="mailto:manntomar46@gmail.com">
      <rect x="500" y="18" width="180" height="44" rx="8" fill="#ea4335">
        <animate attributeName="opacity" values="0.85;1;0.85" dur="2s" begin="1s" repeatCount="indefinite"/>
      </rect>
      <text x="590" y="46" font-family="'Courier New', monospace" font-size="13" fill="white" text-anchor="middle" font-weight="bold">Gmail</text>
    </a>
  </g>
</svg>

</div>

---

<div align="center">

<!-- ANIMATED FOOTER WAVE SVG -->
<svg width="860" height="100" viewBox="0 0 860 100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f5ff;stop-opacity:0.6"/>
      <stop offset="50%" style="stop-color:#bf5fff;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#ff6b6b;stop-opacity:0.6"/>
    </linearGradient>
    <clipPath id="footerClip"><rect width="860" height="100" rx="12"/></clipPath>
  </defs>
  <g clip-path="url(#footerClip)">
    <rect width="860" height="100" fill="#0a0a14"/>
    <path fill="none" stroke="url(#waveGrad)" stroke-width="2" opacity="0.7">
      <animate attributeName="d" values="M0,50 C140,20 280,80 430,50 C580,20 720,80 860,50;M0,50 C140,80 280,20 430,50 C580,80 720,20 860,50;M0,50 C140,20 280,80 430,50 C580,20 720,80 860,50" dur="4s" repeatCount="indefinite"/>
    </path>
    <path fill="none" stroke="#00f5ff" stroke-width="1" opacity="0.25">
      <animate attributeName="d" values="M0,40 C140,10 280,70 430,40 C580,10 720,70 860,40;M0,40 C140,70 280,10 430,40 C580,70 720,10 860,40;M0,40 C140,10 280,70 430,40 C580,10 720,70 860,40" dur="5s" repeatCount="indefinite"/>
    </path>
    <text x="430" y="62" font-family="'Courier New', monospace" font-size="13" fill="#8b949e" text-anchor="middle" letter-spacing="2">Built with passion by Mann Tomar</text>
    <text x="430" y="82" font-family="'Courier New', monospace" font-size="10" fill="#30363d" text-anchor="middle" letter-spacing="1">manntomar46@gmail.com  |  github.com/MANN-TOMAR</text>
  </g>
</svg>

</div>
