<svg width="900" height="220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="bg" cx="50%" cy="50%" r="70%">
      <stop offset="0%" stop-color="#0A0F1E"/>
      <stop offset="100%" stop-color="#020818"/>
    </radialGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- Particle animations -->
    <style>
      .p { animation: float linear infinite; opacity: 0; }
      .p1  { animation-duration: 6s;  animation-delay: 0s;   }
      .p2  { animation-duration: 8s;  animation-delay: 1s;   }
      .p3  { animation-duration: 7s;  animation-delay: 2s;   }
      .p4  { animation-duration: 9s;  animation-delay: 0.5s; }
      .p5  { animation-duration: 5s;  animation-delay: 3s;   }
      .p6  { animation-duration: 10s; animation-delay: 1.5s; }
      .p7  { animation-duration: 6.5s;animation-delay: 4s;   }
      .p8  { animation-duration: 8.5s;animation-delay: 2.5s; }
      .p9  { animation-duration: 7.5s;animation-delay: 0.8s; }
      .p10 { animation-duration: 9.5s;animation-delay: 3.5s; }
      .p11 { animation-duration: 5.5s;animation-delay: 1.2s; }
      .p12 { animation-duration: 11s; animation-delay: 2.2s; }
      .p13 { animation-duration: 6.2s;animation-delay: 4.5s; }
      .p14 { animation-duration: 8.2s;animation-delay: 0.3s; }
      .p15 { animation-duration: 7.2s;animation-delay: 3.2s; }
      .p16 { animation-duration: 9.2s;animation-delay: 1.8s; }
      .p17 { animation-duration: 5.8s;animation-delay: 2.8s; }
      .p18 { animation-duration: 10.5s;animation-delay:0.6s; }
      .p19 { animation-duration: 6.8s;animation-delay: 4.2s; }
      .p20 { animation-duration: 8.8s;animation-delay: 1.6s; }

      @keyframes float {
        0%   { opacity: 0;   transform: translateY(0px)   scale(0.5); }
        10%  { opacity: 0.8; }
        90%  { opacity: 0.8; }
        100% { opacity: 0;   transform: translateY(-180px) scale(1.2); }
      }

      .name-text {
        animation: nameglow 3s ease-in-out infinite alternate;
      }
      @keyframes nameglow {
        from { filter: url(#glow);     opacity: 0.9; }
        to   { filter: url(#softglow); opacity: 1.0; }
      }

      .line-anim {
        animation: linepulse 2.5s ease-in-out infinite alternate;
      }
      @keyframes linepulse {
        from { opacity: 0.4; }
        to   { opacity: 1.0; }
      }

      .subtitle {
        animation: subin 1.5s ease-out forwards;
        opacity: 0;
      }
      @keyframes subin {
        from { opacity: 0; transform: translateY(8px); }
        to   { opacity: 1; transform: translateY(0);   }
      }

      .badge {
        animation: badgein 2s ease-out forwards;
        opacity: 0;
      }
      .b1 { animation-delay: 0.5s; }
      .b2 { animation-delay: 1.0s; }
      .b3 { animation-delay: 1.5s; }
      @keyframes badgein {
        from { opacity: 0; transform: translateY(6px); }
        to   { opacity: 1; transform: translateY(0);   }
      }
    </style>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" fill="url(#bg)"/>

  <!-- Grid lines subtle -->
  <line x1="0" y1="40"  x2="900" y2="40"  stroke="#00B4D8" stroke-width="0.2" opacity="0.15"/>
  <line x1="0" y1="80"  x2="900" y2="80"  stroke="#00B4D8" stroke-width="0.2" opacity="0.15"/>
  <line x1="0" y1="120" x2="900" y2="120" stroke="#00B4D8" stroke-width="0.2" opacity="0.15"/>
  <line x1="0" y1="160" x2="900" y2="160" stroke="#00B4D8" stroke-width="0.2" opacity="0.15"/>
  <line x1="0" y1="200" x2="900" y2="200" stroke="#00B4D8" stroke-width="0.2" opacity="0.15"/>
  <line x1="150" y1="0" x2="150" y2="220" stroke="#00B4D8" stroke-width="0.2" opacity="0.1"/>
  <line x1="300" y1="0" x2="300" y2="220" stroke="#00B4D8" stroke-width="0.2" opacity="0.1"/>
  <line x1="450" y1="0" x2="450" y2="220" stroke="#00B4D8" stroke-width="0.2" opacity="0.1"/>
  <line x1="600" y1="0" x2="600" y2="220" stroke="#00B4D8" stroke-width="0.2" opacity="0.1"/>
  <line x1="750" y1="0" x2="750" y2="220" stroke="#00B4D8" stroke-width="0.2" opacity="0.1"/>

  <!-- Floating Particles -->
  <circle class="p p1"  cx="60"  cy="200" r="2.5" fill="#00B4D8"/>
  <circle class="p p2"  cx="120" cy="210" r="1.5" fill="#0077B6"/>
  <circle class="p p3"  cx="200" cy="205" r="3"   fill="#00B4D8"/>
  <circle class="p p4"  cx="280" cy="215" r="1.8" fill="#48CAE4"/>
  <circle class="p p5"  cx="350" cy="200" r="2"   fill="#00B4D8"/>
  <circle class="p p6"  cx="420" cy="210" r="2.8" fill="#0077B6"/>
  <circle class="p p7"  cx="500" cy="205" r="1.5" fill="#00B4D8"/>
  <circle class="p p8"  cx="570" cy="215" r="2.2" fill="#48CAE4"/>
  <circle class="p p9"  cx="640" cy="200" r="3"   fill="#00B4D8"/>
  <circle class="p p10" cx="710" cy="210" r="1.8" fill="#0077B6"/>
  <circle class="p p11" cx="780" cy="205" r="2.5" fill="#00B4D8"/>
  <circle class="p p12" cx="840" cy="215" r="1.5" fill="#48CAE4"/>
  <circle class="p p13" cx="90"  cy="200" r="2"   fill="#FF6B6B"/>
  <circle class="p p14" cx="320" cy="210" r="1.8" fill="#FF6B6B"/>
  <circle class="p p15" cx="540" cy="205" r="2.2" fill="#FF6B6B"/>
  <circle class="p p16" cx="760" cy="215" r="1.5" fill="#FF6B6B"/>
  <circle class="p p17" cx="170" cy="200" r="2.8" fill="#00B4D8"/>
  <circle class="p p18" cx="460" cy="210" r="2"   fill="#0077B6"/>
  <circle class="p p19" cx="680" cy="205" r="1.8" fill="#48CAE4"/>
  <circle class="p p20" cx="870" cy="215" r="2.5" fill="#00B4D8"/>

  <!-- Top accent line animated -->
  <line class="line-anim" x1="50" y1="28" x2="850" y2="28" stroke="#00B4D8" stroke-width="1" opacity="0.6"/>

  <!-- Corner accents -->
  <polyline points="18,18 18,38 38,38" stroke="#00B4D8" stroke-width="1.5" fill="none" opacity="0.7"/>
  <polyline points="882,18 882,38 862,38" stroke="#00B4D8" stroke-width="1.5" fill="none" opacity="0.7"/>
  <polyline points="18,202 18,182 38,182" stroke="#00B4D8" stroke-width="1.5" fill="none" opacity="0.7"/>
  <polyline points="882,202 882,182 862,182" stroke="#00B4D8" stroke-width="1.5" fill="none" opacity="0.7"/>

  <!-- Glow orb behind name -->
  <ellipse cx="450" cy="100" rx="220" ry="55" fill="#00B4D8" opacity="0.04"/>
  <ellipse cx="450" cy="100" rx="140" ry="35" fill="#00B4D8" opacity="0.05"/>

  <!-- Name -->
  <text class="name-text"
        x="450" y="105"
        font-family="'Courier New', monospace"
        font-size="46"
        font-weight="bold"
        fill="#ffffff"
        text-anchor="middle"
        letter-spacing="6"
        filter="url(#glow)">SOUMIK CHAUDHURI</text>

  <!-- Cyan underline -->
  <line class="line-anim" x1="160" y1="116" x2="740" y2="116" stroke="#00B4D8" stroke-width="1.2" opacity="0.8"/>

  <!-- Subtitle -->
  <text class="subtitle"
        x="450" y="148"
        font-family="'Courier New', monospace"
        font-size="14"
        fill="#00B4D8"
        text-anchor="middle"
        letter-spacing="3"
        opacity="0">Flutter × AI/ML Developer &nbsp;|&nbsp; Full Stack Engineer</text>

  <!-- Bottom badges -->
  <rect class="badge b1" x="170" y="168" width="140" height="24" rx="4" fill="#00B4D8" fill-opacity="0.12" stroke="#00B4D8" stroke-width="0.8"/>
  <text class="badge b1" x="240" y="184" font-family="monospace" font-size="11" fill="#00B4D8" text-anchor="middle" letter-spacing="1">📱 FLUTTER DEV</text>

  <rect class="badge b2" x="380" y="168" width="140" height="24" rx="4" fill="#00B4D8" fill-opacity="0.12" stroke="#00B4D8" stroke-width="0.8"/>
  <text class="badge b2" x="450" y="184" font-family="monospace" font-size="11" fill="#00B4D8" text-anchor="middle" letter-spacing="1">🧠 AI/ML ENGINEER</text>

  <rect class="badge b3" x="590" y="168" width="140" height="24" rx="4" fill="#FF6B6B" fill-opacity="0.12" stroke="#FF6B6B" stroke-width="0.8"/>
  <text class="badge b3" x="660" y="184" font-family="monospace" font-size="11" fill="#FF6B6B" text-anchor="middle" letter-spacing="1">💻 FULL STACK</text>

  <!-- Bottom accent line -->
  <line class="line-anim" x1="50" y1="208" x2="850" y2="208" stroke="#0077B6" stroke-width="1" opacity="0.5"/>
</svg>
