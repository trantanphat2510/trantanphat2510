<div align="center">

<!-- 01–04 // MASTER ATELIER NOIR ARCHITECTURAL MONOLITH -->
<a href="https://ttanphat.vercel.app/">
  <img src="./assets/atelier-noir.svg" width="100%" alt="Trần Tấn Phát — Full-Stack Developer · Atelier Noir Architecture" />
</a>

<!-- 05 // CYBERNETIC BRIDGE & 3D MECHANICAL KEYCAP COMMAND DOCK -->
<img src="./assets/launchpad-header.svg" width="100%" alt="05 // Interactive Command Dock — Select Any Module to Deploy" />

<p align="center">
  <a href="https://ttanphat.vercel.app/"><img src="./assets/nav-portfolio.svg" width="172" height="50" alt="01 // Portfolio — ttanphat.vercel.app" /></a>&nbsp;
  <a href="https://website-kaikai.vercel.app/"><img src="./assets/nav-kaikai.svg" width="172" height="50" alt="02 // SaaS Core — KAIKAI Platform" /></a>&nbsp;
  <a href="https://murmur-voice.vercel.app/"><img src="./assets/nav-murmur.svg" width="172" height="50" alt="03 // Voice AI — MurMur Voice AI" /></a>&nbsp;
  <a href="https://ttanphat.vercel.app/projects"><img src="./assets/nav-projects.svg" width="172" height="50" alt="04 // Archive — 4 Case Studies" /></a>&nbsp;
  <a href="mailto:ttanphat.work@gmail.com"><img src="./assets/nav-email.svg" width="172" height="50" alt="05 // Contact — ttanphat.work@gmail.com" /></a>
</p>

<!-- MOBILE-FIRST & KEYBOARD QUICK-JUMP ACTION BAR -->
<p align="center">
  <sub>
    <kbd>⌘1</kbd> <a href="https://ttanphat.vercel.app/"><b>Portfolio</b></a> &nbsp;·&nbsp;
    <kbd>⌘2</kbd> <a href="https://website-kaikai.vercel.app/"><b>KAIKAI SaaS</b></a> &nbsp;·&nbsp;
    <kbd>⌘3</kbd> <a href="https://murmur-voice.vercel.app/"><b>MurMur Voice AI</b></a> &nbsp;·&nbsp;
    <kbd>⌘4</kbd> <a href="https://ttanphat.vercel.app/projects"><b>4 Case Studies</b></a> &nbsp;·&nbsp;
    <kbd>⌘5</kbd> <a href="mailto:ttanphat.work@gmail.com"><b>ttanphat.work@gmail.com</b></a>
  </sub>
</p>

<!-- 06 // LIVE SKILL RADAR, CI/CD PIPELINE CONVEYOR & SAIGON TELEMETRY HUD -->
<img src="./assets/engineering-hud.svg" width="100%" alt="06 // Skill Radar, CI/CD Pipeline Conveyor & Saigon Base Station Telemetry" />

<!-- 07A // INTERACTIVE SYSTEM ARCHITECTURE & DATA-FLOW TOPOLOGY (MERMAID ENGINE) -->
<details>
  <summary><code>🕸️ NOIR-OS // 07A · LIVE SYSTEM ARCHITECTURE &amp; DATA-FLOW TOPOLOGY</code> <sub><i>(Click to inspect full-stack request &amp; WebRTC pipeline)</i></sub></summary>
  <br />

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#131C2E', 'primaryTextColor': '#F8FAFC', 'primaryBorderColor': '#38BDF8', 'lineColor': '#38BDF8', 'secondaryColor': '#1F1421', 'tertiaryColor': '#0B0F17'}}}%%
flowchart LR
  subgraph Client["01 // CLIENT & MOTION TIER"]
    UI["React 19 · Next.js 16<br/>60fps Motion · Tailwind v4"]
    RTC["WebRTC P2P Mesh<br/>Sub-100ms Audio Stream"]
  end

  subgraph Edge["02 // GATEWAY & CACHE"]
    SFC["Single-Flight Cache<br/>Stampede Protection"]
    RBAC["3-Layer RBAC Guards<br/>JWT · Tenant Context"]
  end

  subgraph Core["03 // APPLICATION & AI CORE"]
    NEST["NestJS 11 Micro-Core<br/>10+ SaaS Modules · KAIKAI"]
    FAST["Python FastAPI Engine<br/>ElevenLabs Voice AI · MurMur"]
  end

  subgraph Data["04 // DATA & QUALITY GATE"]
    PG[("PostgreSQL 16 · Prisma<br/>Row-Level Security — RLS")]
    SUPA[("Supabase Realtime<br/>Optimistic Graph Sync")]
    E2E["Playwright E2E Suite<br/>100/100 Lighthouse Gate"]
  end

  UI ==>|"SSR / ISR"| SFC
  SFC ==>|"Validated"| RBAC
  RBAC ==>|"Tenant Scoped"| NEST
  NEST ==>|"RLS Policy"| PG
  UI -.->|"Optimistic UI"| SUPA
  RTC <-->|"P2P · SFU"| FAST
  FAST ==>|"Verified"| E2E
```

</details>

<!-- 07B // EXPANDABLE SYSTEM SPECIFICATIONS, SLA BENCHMARKS & CLI QUICK-VERIFY -->
<details>
  <summary><code>⚡ NOIR-OS // 07B · SLA BENCHMARKS, CORE WEB VITALS &amp; CLI QUICK-VERIFY</code> <sub><i>(Click to expand interactive terminal &amp; architecture index)</i></sub></summary>
  <br />

  <div align="left">

  ```bash
  # ⚡ 01 // Quick-Verify Live Production Endpoints & Edge TLS Headers
  curl -ILs https://ttanphat.vercel.app/       | grep -E "HTTP/|server|x-vercel-cache"
  curl -ILs https://website-kaikai.vercel.app/ | grep -E "HTTP/|server|x-vercel-cache"
  curl -ILs https://murmur-voice.vercel.app/   | grep -E "HTTP/|server|x-vercel-cache"
  ```

  </div>

  | ID | Production System | Domain &amp; SLA Metric | Architectural Engineering Highlights | Primary Core Stack | Live Endpoint |
  | :---: | :--- | :---: | :--- | :--- | :---: |
  | `01` | **KAIKAI** | `Multi-Tenant SaaS`<br/>**10+ Modules · PG RLS** | • **Single-flight cache** stampede protection on high-concurrency booking reads<br/>• **3-layer RBAC** guards &amp; **PostgreSQL 16 Row-Level Security (RLS)** isolation | `Next.js 16` `NestJS 11` `PostgreSQL` `Prisma` `Supabase` | [**Launch App ↗**](https://website-kaikai.vercel.app/) |
  | `02` | **MurMur** | `Realtime Voice AI`<br/>**&lt;100ms P2P Audio** | • Low-latency **WebRTC peer-to-peer** voice rooms with sub-100ms audio routing<br/>• **Python FastAPI** orchestrator + **ElevenLabs** conversational AI voice synthesis | `Next.js` `FastAPI` `Python` `WebRTC` `ElevenLabs` | [**Launch App ↗**](https://murmur-voice.vercel.app/) |
  | `03` | **Social Learning** | `Academic Graph`<br/>**Optimistic Sync** | • Instant **optimistic UI** feed mutations &amp; cache invalidation via **TanStack Query**<br/>• Live collaborative study channels powered by **Supabase Realtime** &amp; RLS | `React 19` `TypeScript` `Supabase` `Zustand` `Docker` | [**Case Study ↗**](https://ttanphat.vercel.app/projects) |
  | `04` | **Atelier Noir** | `Design Engineering`<br/>**100/100 Lighthouse** | • **60fps spring-physics** motion system, Lenis smooth scroll &amp; zero layout shift<br/>• Verified **100/100 Core Web Vitals** with automated **Playwright E2E** CI suite | `React 19` `TypeScript` `Tailwind v4` `Motion` `Playwright` | [**Launch App ↗**](https://ttanphat.vercel.app/) |

  <p align="center">
    <code>IDENTITY: Trần Tấn Phát</code> &nbsp;·&nbsp;
    <code>ROLE: Full-Stack Developer</code> &nbsp;·&nbsp;
    <code>EDUCATION: B.S. in IT @ HUTECH (2021–2025)</code> &nbsp;·&nbsp;
    <a href="mailto:ttanphat.work@gmail.com"><code>ttanphat.work@gmail.com</code></a>
  </p>
</details>

<!-- 08 // TELEMETRY CLOSING RAIL -->
<img src="./assets/telemetry-footer.svg" width="100%" alt="NOIR-OS v4.2 — All 4 Production Systems Online" />

</div>
