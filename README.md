<!--
  GitHub Profile README — Tron-style "Website"
  Author: Brian
  Notes:
    - Pure README, no external assets required.
    - Uses inline SVG for neon grid + glow accents (renders on GitHub).
    - Sections linked like a single-page site.
    - Edit placeholders as needed.
-->

<!-- HERO / BANNER -->
<p align="center">
  <!-- Inline SVG neon grid banner -->
  <svg viewBox="0 0 1400 360" width="100%" height="auto" role="img" aria-label="TRON neon banner">
    <defs>
      <!-- Neon cyan -->
      <linearGradient id="cyangrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00FFF0"/>
        <stop offset="50%" stop-color="#00D1FF"/>
        <stop offset="100%" stop-color="#00A3FF"/>
      </linearGradient>
      <!-- Glow filter -->
      <filter id="glow" x="-100%" y="-100%" width="300%" height="300%">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <!-- Soft scanlines -->
      <pattern id="scan" width="4" height="4" patternUnits="userSpaceOnUse">
        <rect width="4" height="2" fill="rgba(255,255,255,0.03)"/>
        <rect y="2" width="4" height="2" fill="rgba(0,0,0,0.0)"/>
      </pattern>
    </defs>

    <!-- Background -->
    <rect width="1400" height="360" fill="#0a0f14"/>
    <rect width="1400" height="360" fill="url(#scan)"/>

    <!-- Horizon glow -->
    <ellipse cx="700" cy="250" rx="520" ry="60" fill="url(#cyangrad)" opacity="0.18" filter="url(#glow)"/>

    <!-- Tron grid -->
    <g stroke="url(#cyangrad)" stroke-width="1.2" opacity="0.6">
      <!-- Vertical lines -->
      <g>
        <!-- 0..28 ~ every 50px -->
        <script type="application/ecmascript"><![CDATA[
          // (Ignored on GitHub; lines are hardcoded below.)
        ]]></script>
      </g>
      <!-- Hardcoded grid lines for GitHub sanitization safety -->
      <!-- Vertical -->
      <g>
        <line x1="0" y1="260" x2="0" y2="360"/>
        <line x1="50" y1="245" x2="50" y2="360"/>
        <line x1="100" y1="235" x2="100" y2="360"/>
        <line x1="150" y1="228" x2="150" y2="360"/>
        <line x1="200" y1="223" x2="200" y2="360"/>
        <line x1="250" y1="220" x2="250" y2="360"/>
        <line x1="300" y1="218" x2="300" y2="360"/>
        <line x1="350" y1="217" x2="350" y2="360"/>
        <line x1="400" y1="216" x2="400" y2="360"/>
        <line x1="450" y1="216" x2="450" y2="360"/>
        <line x1="500" y1="216" x2="500" y2="360"/>
        <line x1="550" y1="216" x2="550" y2="360"/>
        <line x1="600" y1="216" x2="600" y2="360"/>
        <line x1="650" y1="216" x2="650" y2="360"/>
        <line x1="700" y1="216" x2="700" y2="360"/>
        <line x1="750" y1="216" x2="750" y2="360"/>
        <line x1="800" y1="216" x2="800" y2="360"/>
        <line x1="850" y1="216" x2="850" y2="360"/>
        <line x1="900" y1="216" x2="900" y2="360"/>
        <line x1="950" y1="216" x2="950" y2="360"/>
        <line x1="1000" y1="216" x2="1000" y2="360"/>
        <line x1="1050" y1="216" x2="1050" y2="360"/>
        <line x1="1100" y1="216" x2="1100" y2="360"/>
        <line x1="1150" y1="220" x2="1150" y2="360"/>
        <line x1="1200" y1="223" x2="1200" y2="360"/>
        <line x1="1250" y1="228" x2="1250" y2="360"/>
        <line x1="1300" y1="235" x2="1300" y2="360"/>
        <line x1="1350" y1="245" x2="1350" y2="360"/>
        <line x1="1400" y1="260" x2="1400" y2="360"/>
      </g>
      <!-- Horizontal perspective lines -->
      <g>
        <line x1="0" y1="216" x2="1400" y2="216"/>
        <line x1="0" y1="236" x2="1400" y2="226"/>
        <line x1="0" y1="256" x2="1400" y2="238"/>
        <line x1="0" y1="276" x2="1400" y2="254"/>
        <line x1="0" y1="296" x2="1400" y2="274"/>
        <line x1="0" y1="316" x2="1400" y2="298"/>
        <line x1="0" y1="336" x2="1400" y2="326"/>
        <line x1="0" y1="356" x2="1400" y2="358"/>
      </g>
    </g>

    <!-- Title -->
    <g filter="url(#glow)">
      <text x="50%" y="110" text-anchor="middle" fill="url(#cyangrad)" font-family="Segoe UI, Roboto, Ubuntu, Cantarell, 'Helvetica Neue', Arial, sans-serif" font-size="64" font-weight="800" letter-spacing="4">
        B R I A N · C O D E S
      </text>
      <text x="50%" y="155" text-anchor="middle" fill="#73FFFF" font-size="20" opacity="0.9" letter-spacing="2">
        precision • efficiency • relevance
      </text>
    </g>

    <!-- Neon divider -->
    <g filter="url(#glow)">
      <rect x="350" y="175" width="700" height="2.5" fill="url(#cyangrad)"/>
    </g>

    <!-- Callout -->
    <g>
      <text x="50%" y="205" text-anchor="middle" fill="#B3F4FF" font-size="16" opacity="0.85">
        building layered, dynamic, future-oriented systems
      </text>
    </g>
  </svg>
</p>

<!-- NAV -->
<p align="center">
  <a href="#projects">Projects</a> •
  <a href="#stack">Stack</a> •
  <a href="#speedrun">Speedrun</a> •
  <a href="#contact">Contact</a>
</p>

<!-- BADGE STRIP -->
<p align="center">
  <img alt="Focus: GPC scripts" src="https://img.shields.io/badge/Focus-GPC%20Scripts-00d1ff?style=for-the-badge&labelColor=001018">
  <img alt="Web: React/Next.js" src="https://img.shields.io/badge/Web-React%2FNext.js-00e7ff?style=for-the-badge&labelColor=001018">
  <img alt="Style: Tailwind" src="https://img.shields.io/badge/Style-Tailwind-00b3ff?style=for-the-badge&labelColor=001018">
  <img alt="Shaders" src="https://img.shields.io/badge/Graphics-Shaders-00a3ff?style=for-the-badge&labelColor=001018">
</p>

---

## 👾 About

I ship production-ready tools and platforms with a bias for speed and clarity. I value **tight feedback loops**, **measurable outcomes**, and code that respects existing constraints.

- 🧠 Systems: layered, composable, testable
- ⚡ UX: frictionless, keyboard-first, latency-obsessed
- 🛠️ Monetization: affiliate flows, subscriptions, usage-based

---

## 🔭 Featured Work <a id="projects"></a>

> Tip: pin 3–6 repos that match these cards.

### `neon-grid` — Realtime shader playground
- WebGL/GLSL shader packs, param morphing, and gallery export.
- Edge-ready build, per-shader worker, deterministic seeds.

### `link-accelerator` — Affiliate routing kernel
- Rule engine + geo/device targeting + A/B and failover.
- Click simulation suite + revenue attribution adapters.

### `gpc-toolkit` — Pro macros with safety rails
- Multi-profile compiler, input curves, runtime diagnostics.
- Sandbox DSL + audit log + sharable presets.

---

## 🧩 Stack <a id="stack"></a>

```text
Core:    TypeScript • React/Next.js • Node • Vite/Turborepo
UI:      Tailwind • Radix/shadcn • Framer Motion
Data:    Postgres • Prisma • Drizzle • Redis
Infra:   Docker • Fly.io/Vercel • Cloudflare • GitHub Actions
Low-lvl: WebGL/GLSL • GPC scripting • Workers • WASM (lite)
Quality: Zod • Vitest • Playwright • k6 • Sentry
```

---

## ⚙️ Speedrun: How I work <a id="speedrun"></a>

1. **Define** the contract first (types & tests).
2. **Spike** the riskiest paths; measure latency.
3. **Stabilize**: telemetry, error budgets, guardrails.
4. **Polish** the edges: docs, DX, and automations.

---

## 📈 Live Cards (optional)

<p align="center">
  <!-- Swap USERNAME -->
  <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight&hide_border=true" />
  <img alt="Top Langs" src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 📬 Contact <a id="contact"></a>

- X/Twitter: `@yourhandle`
- Email: `you@example.com`
- Link-in-bio: `https://yourdomain.xyz`

---

<!-- FOOTER: neon divider -->
<p align="center">
  <svg viewBox="0 0 1200 30" width="100%" height="30" aria-hidden="true">
    <defs>
      <linearGradient id="cyangrad2" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#00FFF0"/>
        <stop offset="50%" stop-color="#00D1FF"/>
        <stop offset="100%" stop-color="#00A3FF"/>
      </linearGradient>
      <filter id="softglow" x="-100%" y="-100%" width="300%" height="300%">
        <feGaussianBlur stdDeviation="3" result="b"/>
        <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>
    <rect x="150" y="13" width="900" height="4" fill="url(#cyangrad2)" filter="url(#softglow)"/>
  </svg>
</p>

<p align="center">
  <sub>© <span id="year">2025</span> Brian — neon-coded on the grid</sub>
</p>

<!--
Edit guide:
- Replace USERNAME and contact info.
- Reorder/rename Featured Work items or convert to pinned repo links.
- The SVGs are self-contained; no external assets required.
- GitHub strips most CSS, so styling is achieved via SVGs and layout via HTML/Markdown only.
-->
