<!--
  README for BhagathK7 — Minimal • Cloud-themed • Professional
  - Inline animated SVG header & quote (no external gif)
  - Stable icons via skillicons / simpleicons
  - GitHub Stats cards included
  -->

<div align="center">

<!-- Inline animated cloud header SVG (self-contained) -->
<!-- This SVG uses simple moving clouds (SMIL). It renders directly on GitHub. -->
<svg width="100%" height="140" viewBox="0 0 1200 140" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" role="img" aria-label="cloud header">
  <defs>
    <linearGradient id="skyGrad" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0" stop-color="#ffffff"/>
      <stop offset="1" stop-color="#f6f7fb"/>
    </linearGradient>
  </defs>

  <rect width="1200" height="140" fill="url(#skyGrad)"/>

  <!-- cloud group 1 -->
  <g transform="translate(0,10)" opacity="0.95">
    <g id="cloud1" transform="translate(-300,0)">
      <ellipse cx="180" cy="50" rx="80" ry="30" fill="#f3f5f9"/>
      <ellipse cx="230" cy="40" rx="60" ry="28" fill="#f3f5f9"/>
      <ellipse cx="140" cy="40" rx="50" ry="25" fill="#f3f5f9"/>
    </g>
    <animate xlink:href="#cloud1" attributeName="transform" dur="28s" repeatCount="indefinite" from="translate(-300,0)" to="translate(1400,0)"/>
  </g>

  <!-- cloud group 2 -->
  <g transform="translate(0,40)" opacity="0.9">
    <g id="cloud2" transform="translate(-500,0)" >
      <ellipse cx="380" cy="30" rx="110" ry="36" fill="#fbfbfd"/>
      <ellipse cx="320" cy="20" rx="70" ry="28" fill="#fbfbfd"/>
      <ellipse cx="440" cy="22" rx="60" ry="24" fill="#fbfbfd"/>
    </g>
    <animate xlink:href="#cloud2" attributeName="transform" dur="38s" repeatCount="indefinite" from="translate(-500,0)" to="translate(1400,0)"/>
  </g>

  <!-- subtle horizon line -->
  <line x1="80" y1="118" x2="1120" y2="118" stroke="#e6e8ee" stroke-width="1"/>
</svg>

<h1 style="margin:8px 0 4px 0; font-weight:600; letter-spacing:0.2px;">Hey, I’m Bhagath Krishna</h1>
<p style="margin:0 0 12px 0; color:#505962; font-style:normal; font-weight:400;">Frontend-focused Full-Stack Developer</p>

</div>

<!-- short intro -->
<div align="center" style="max-width:820px; margin:14px auto 18px auto; color:#5a6570;">
  I design minimal, responsive front-ends and build full-stack apps when needed. I care about polished UI, accessibility and performance.
</div>

<hr style="border:none; height:1px; background:#eceff3; margin:18px 0;" />

<!-- Tech stack -->
## Tech stack
<div align="center" style="margin:12px 0 18px 0;">
  <!-- skillicons is reliable and returns small neutral icons -->
  <img src="https://skillicons.dev/icons?i=html" alt="html" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=css" alt="css" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=js" alt="javascript" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=react" alt="react" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=nodejs" alt="nodejs" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=express" alt="express" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=mongodb" alt="mongodb" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=git" alt="git" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=python" alt="python" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=java" alt="java" width="36" style="margin:6px"/>
  <img src="https://skillicons.dev/icons?i=c" alt="c" width="36" style="margin:6px"/>
</div>

<hr style="border:none; height:1px; background:#eceff3; margin:18px 0;" />

<!-- Stats: cards from github-readme-stats (widely used) -->
## GitHub activity
<div align="center" style="margin-top:4px;">

<!-- Stats cards: these are server-side images from the project owner -->
<img alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=BhagathK7&show_icons=true&count_private=false&hide_border=true&theme=default" style="max-width:460px; margin:8px;"/>

<img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BhagathK7&layout=compact&hide_border=true&theme=default" style="max-width:320px; margin:8px;"/>
</div>

<hr style="border:none; height:1px; background:#eceff3; margin:18px 0;" />

<!-- Animated rotating quotes using inline SVG (no external services). -->
## Selected notes
<div align="center" style="max-width:760px; margin:8px auto 20px auto;">

<!-- rotating quotes SVG: three short professional quotes; SMIL animation rotates opacity -->
<svg width="720" height="70" viewBox="0 0 720 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="rotating quotes">
  <rect width="100%" height="100%" fill="#ffffff" />
  <style>
    .q { font: 16px/1.2 "Segoe UI", Roboto, -apple-system, "Helvetica Neue", Arial; fill:#3f4a52; }
    .author { font: 12px/1 "Segoe UI", Roboto, -apple-system, "Helvetica Neue", Arial; fill:#8b949e; }
  </style>

  <!-- quote 1 -->
  <g id="t1" opacity="1">
    <text x="18" y="28" class="q">Design is not decoration — it makes products usable, faster and kinder to use.</text>
    <text x="18" y="48" class="author">— Bhagath Krishna</text>
    <animate attributeName="opacity" from="1" to="0" begin="4s" dur="0.8s" fill="freeze" />
  </g>

  <!-- quote 2 -->
  <g id="t2" opacity="0">
    <text x="18" y="28" class="q">Small, consistent UI improvements create a markedly better experience.</text>
    <text x="18" y="48" class="author">— Frontend philosophy</text>
    <animate attributeName="opacity" from="0" to="1" begin="4.8s" dur="0.8s" fill="freeze" />
    <animate attributeName="opacity" from="1" to="0" begin="8.8s" dur="0.8s" fill="freeze" />
  </g>

  <!-- quote 3 -->
  <g id="t3" opacity="0">
    <text x="18" y="28" class="q">I prefer interfaces that are intentional, accessible and fast.</text>
    <text x="18" y="48" class="author">— Product mindset</text>
    <animate attributeName="opacity" from="0" to="1" begin="9.6s" dur="0.8s" fill="freeze" />
    <animate attributeName="opacity" from="1" to="0" begin="13.6s" dur="0.8s" fill="freeze" />
  </g>

  <!-- loop control: jump back to visible first quote -->
  <animate attributeName="visibility" from="visible" to="visible" begin="14.6s" dur="0.01s" repeatCount="indefinite"/>
  <!-- We rely on the long-run nature of SMIL animations above to give a gentle rotation -->
</svg>

</div>

<hr style="border:none; height:1px; background:#eceff3; margin:18px 0;" />

## What I work on
- Clean, responsive frontends and accessible UI patterns.  
- Interactive components and micro-interactions in React.  
- Small full-stack apps (Node.js + Express + MongoDB) when backend is needed.

---

<div align="center" style="margin-top:16px;">
  <a href="https://github.com/BhagathK7" style="text-decoration:none; color:#2b2f33; padding:10px 14px; border-radius:8px; border:1px solid #e6e9ee;">View GitHub profile</a>
  &nbsp;&nbsp;
  <!-- Replace '#' with your LinkedIn URL if desired -->
  <a href="#" style="text-decoration:none; color:#2b2f33; padding:10px 14px; border-radius:8px; border:1px solid #e6e9ee;">LinkedIn</a>
  &nbsp;&nbsp;
  <a href="mailto:your.email@example.com" style="text-decoration:none; color:#2b2f33; padding:10px 14px; border-radius:8px; border:1px solid #e6e9ee;">Contact</a>
</div>

<br/>

<div align="center" style="color:#98a3ad; font-size:13px; margin-bottom:18px;">
  Designed to be minimal, calm and professional.
</div>
