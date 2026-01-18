<p align="center">
  <svg width="440" height="280" viewBox="0 0 440 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="neoBG" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f172a"/>
      <stop offset="50%" stop-color="#4c1d95"/>
      <stop offset="100%" stop-color="#00f5ff"/>
    </linearGradient>

    <!-- Glow -->
    <filter id="glow">
      <feDropShadow dx="0" dy="0" stdDeviation="12" flood-color="#00f5ff" flood-opacity="0.6"/>
    </filter>

    <!-- Shine -->
    <linearGradient id="shine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="rgba(255,255,255,0)"/>
      <stop offset="50%" stop-color="rgba(255,255,255,0.35)"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0)"/>
    </linearGradient>
  </defs>

  <!-- Card Base -->
  <rect x="20" y="20" rx="22" ry="22" width="400" height="240"
        fill="url(#neoBG)" filter="url(#glow)">
    <animateTransform
      attributeName="transform"
      type="scale"
      from="1"
      to="1.015"
      begin="0s"
      dur="3s"
      repeatCount="indefinite"
      direction="alternate"/>
  </rect>

  <!-- Moving Shine -->
  <rect x="-200" y="20" width="200" height="240" fill="url(#shine)">
    <animateTransform
      attributeName="transform"
      type="translate"
      from="0 0"
      to="700 0"
      dur="4.5s"
      repeatCount="indefinite"/>
  </rect>

  <!-- Chip -->
  <rect x="60" y="90" width="75" height="55" rx="8" fill="#e5e7eb" opacity="0.85"/>

  <!-- Username -->
  <text x="60" y="175" fill="#00f5ff" font-size="18" font-family="monospace">
    AlMahmodulHasanAlif
  </text>

  <!-- Role -->
  <text x="60" y="198" fill="#a5f3fc" font-size="14" font-family="monospace">
    Junior MERN Stack Developer
  </text>

  <!-- VISA Branding -->
  <text x="305" y="200" fill="#ffffff" font-size="30"
        font-family="monospace" font-weight="bold">
    VISA
  </text>

  <text x="305" y="220" fill="#e5e7eb" font-size="12" font-family="monospace">
    GITHUB
  </text>
</svg>

</p
