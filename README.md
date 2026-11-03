<div align="center">

<!-- 01–04 // MASTER ATELIER NOIR ARCHITECTURAL MONOLITH -->
<a href="https://ttanphat.vercel.app/">
  <img src="./assets/atelier-noir.svg" width="100%" decoding="async" fetchpriority="high" alt="Trần Tấn Phát — Full-Stack Developer · Atelier Noir Architecture" />
</a>

<!-- 05 // LIVE SKILL RADAR, CI/CD PIPELINE CONVEYOR & SAIGON BASE STATION HUD -->
<img src="./assets/engineering-hud.svg" width="100%" loading="lazy" decoding="async" alt="05 // Skill Radar, CI/CD Pipeline Conveyor & Saigon Base Station Telemetry" />

<!-- 06 // INTERACTIVE 3D MECHANICAL KEYCAP COMMAND DOCK -->
<img src="./assets/launchpad-header.svg" width="100%" loading="lazy" decoding="async" alt="06 // Interactive Command Dock — Click Any Keycap Below to Launch" />

<p align="center">
  <a href="https://ttanphat.vercel.app/"><img src="./assets/nav-portfolio.svg" width="19.2%" loading="lazy" decoding="async" alt="⌘1 Portfolio — ttanphat.vercel.app" /></a>
  <a href="https://website-kaikai.vercel.app/"><img src="./assets/nav-kaikai.svg" width="19.2%" loading="lazy" decoding="async" alt="⌘2 KAIKAI SaaS — website-kaikai.vercel.app" /></a>
  <a href="https://murmur-voice.vercel.app/"><img src="./assets/nav-murmur.svg" width="19.2%" loading="lazy" decoding="async" alt="⌘3 MurMur AI — murmur-voice.vercel.app" /></a>
  <a href="https://ttanphat.vercel.app/projects"><img src="./assets/nav-projects.svg" width="19.2%" loading="lazy" decoding="async" alt="⌘4 Case Studies — ttanphat.vercel.app/projects" /></a>
  <a href="mailto:ttanphat.work@gmail.com"><img src="./assets/nav-email.svg" width="19.2%" loading="lazy" decoding="async" alt="⌘5 Direct Email — ttanphat.work@gmail.com" /></a>
</p>

<!-- 07 // TELEMETRY CLOSING RAIL (COMPLETES THE CONTINUOUS ARCHITECTURAL SPINE) -->
<img src="./assets/telemetry-footer.svg" width="100%" loading="lazy" decoding="async" alt="NOIR-OS v4.2 — All 4 Production Systems Online" />

<!-- 08 // UNIFIED EXECUTIVE TECHNICAL DOSSIER (SINGLE EXPANDABLE DRAWER) -->
<details>
  <summary><code>08 // SYSTEM ARCHITECTURE TOPOLOGY, PRODUCTION SLA &amp; CLI VERIFICATION</code> &nbsp;<sub><b>[EXPAND DOSSIER ▾]</b></sub></summary>
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

  | ID | Production System | Domain &amp; SLA Metric | Architectural Engineering Highlights | Primary Core Stack | Live Endpoint |
  | :---: | :--- | :---: | :--- | :--- | :---: |
  | `01` | **KAIKAI** | `Multi-Tenant SaaS`<br/>**10+ Modules · PG RLS** | • **Single-flight cache** stampede protection on high-concurrency booking reads<br/>• **3-layer RBAC** guards &amp; **PostgreSQL 16 Row-Level Security (RLS)** isolation | `Next.js 16` `NestJS 11` `PostgreSQL` `Prisma` `Supabase` | [**Launch App ↗**](https://website-kaikai.vercel.app/) |
  | `02` | **MurMur** | `Realtime Voice AI`<br/>**&lt;100ms P2P Audio** | • Low-latency **WebRTC peer-to-peer** voice rooms with sub-100ms audio routing<br/>• **Python FastAPI** orchestrator + **ElevenLabs** conversational AI voice synthesis | `Next.js` `FastAPI` `Python` `WebRTC` `ElevenLabs` | [**Launch App ↗**](https://murmur-voice.vercel.app/) |
  | `03` | **Social Learning** | `Academic Graph`<br/>**Optimistic Sync** | • Instant **optimistic UI** feed mutations &amp; cache invalidation via **TanStack Query**<br/>• Live collaborative study channels powered by **Supabase Realtime** &amp; RLS | `React 19` `TypeScript` `Supabase` `Zustand` `Docker` | [**Case Study ↗**](https://ttanphat.vercel.app/projects) |
  | `04` | **Atelier Noir** | `Design Engineering`<br/>**100/100 Lighthouse** | • **60fps spring-physics** motion system, Lenis smooth scroll &amp; zero layout shift<br/>• Verified **100/100 Core Web Vitals** with automated **Playwright E2E** CI suite | `React 19` `TypeScript` `Tailwind v4` `Motion` `Playwright` | [**Launch App ↗**](https://ttanphat.vercel.app/) |

  <div align="left">

  ```bash
  # Quick-Verify Live Production Endpoints & Edge TLS Headers
  curl -ILs https://ttanphat.vercel.app/ https://website-kaikai.vercel.app/ https://murmur-voice.vercel.app/ | grep -E "HTTP/|server|x-vercel-cache"
  ```

  </div>
</details>

</div>
