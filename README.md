<div align="center">

# Dipto Thakur

**Full-stack developer building editorial, motion-driven web products.**

Next.js · TypeScript · React · Tailwind · Framer Motion

[Portfolio](https://diptothakur.dev) · [LinkedIn](https://www.linkedin.com/in/diptothakur) · [GitHub](https://github.com/dipto-thakur) · [Email](mailto:dkt.officials@gmail.com)

</div>

---

## About

I build production web apps end to end architecture, UI, and the details in between. Most of my work sits at the intersection of frontend craftsmanship and product delivery: full-stack apps for local businesses, a canvas-based animation system for my own portfolio, and internal tools shipped under real deadlines.

I favor minimal, editorial interfaces over dashboard defaults — informed by Apple, Vercel and I care about the parts users don't see: accessible markup, typed data contracts, and code that reads clean a year later.

---

## Current Focus

- Building a personal portfolio with a generator-based canvas system (`PixelCanvas`) driven by live GitHub contribution data
- Shipping a typed blog system using discriminated unions for content models
- Exploring motion systems with Framer Motion and GSAP for scroll-based storytelling
- Available for full-stack and frontend engineering work

---

## Tech Stack

**Languages**
TypeScript · JavaScript · Python

**Frontend**
React · Next.js (App Router) · Tailwind CSS · Framer Motion · GSAP · shadcn/ui

**Backend**
Node.js · NestJS · Express

**Databases**
PostgreSQL · MongoDB · Supabase · Dexie

**Tooling**
Zustand · Puppeteer · Chart.js · Vite

**Cloud**
Vercel · AWS · Firebase

---

## Selected Projects

<details>
<summary><strong>Personal Portfolio — PixelCanvas Engine</strong></summary>

| Area | Details |
|---|---|
| Purpose | Editorial personal site with a canvas-based visual identity |
| Stack | Next.js, TypeScript, Tailwind CSS |
| Highlights | Generator-based `PixelCanvas` rendering system driven by live GitHub contribution heatmap data; isomorphic data layer shared between server and client |
| Challenges | Resolved a server/client data contract mismatch by unifying fetch logic into a single isomorphic module; a parallel simulation subsystem was built, evaluated, then deliberately reverted to keep the original rendering pipeline stable |
| Repository | private |
| Live Demo | — |

Rebuilt the contribution-graph renderer around a shared data module after diagnosing a divergence between server-fetched and client-fetched GitHub data. Kept the simulation branch dormant rather than merging it, prioritizing a stable render path over unfinished complexity.

</details>

<details>
<summary><strong>ForgeCV — AI CV Builder</strong></summary>

| Area | Details |
|---|---|
| Purpose | CV builder with AI-assisted content generation and job-description matching |
| Stack | Next.js, Supabase, Zustand, Puppeteer |
| Highlights | Multi-model AI routing via OpenRouter with fallback chains; PDF export pipeline; diff viewer for AI-suggested edits |
| Challenges | Resolved TypeScript build mismatches, a `Set` iteration bug, and rate-limit failures in production by adding a fallback model chain |
| Repository | private |
| Live Demo | forgecv.app |

Routes CV generation requests across multiple AI models with automatic fallback when a provider is rate-limited, keeping the app usable under real traffic instead of failing silently.

</details>

<details>
<summary><strong>Habit Impact Tracker</strong></summary>

| Area | Details |
|---|---|
| Purpose | Addiction/habit recovery tracker with AI-generated insights |
| Stack | NestJS, Handlebars, Tailwind, Chart.js, OpenRouter |
| Highlights | 16 habit types, cached AI insights, dark/light theming, vertical recovery timeline UI |
| Challenges | Iterated through nine versions to balance insight quality against API cost via response caching |
| Repository | private |
| Live Demo | — |

</details>

<details>
<summary><strong>QR Ordering App — Kolkata Café</strong></summary>

| Area | Details |
|---|---|
| Purpose | QR-based table ordering system for a café client |
| Stack | Next.js, localStorage cart |
| Highlights | WhatsApp order dispatch, no backend required for order handoff |
| Challenges | Kept the stack deliberately lightweight to match the client's operational scale |
| Repository | private |
| Live Demo | — |

</details>

<details>
<summary><strong>The Calcutta Fitness Studio</strong></summary>

| Area | Details |
|---|---|
| Purpose | Marketing site for a fitness studio client |
| Stack | Next.js, Framer Motion, Swiper.js |
| Highlights | Dark aesthetic with red accent, motion-driven section transitions |
| Repository | private |
| Live Demo | — |

</details>

More projects → [github.com/dipto-thakur](https://github.com/dipto-thakur?tab=repositories)

---

## Writing

Technical notes on search, SEO, and engineering practice, published on Medium.

**Geo Is No Longer Optional: What Google Trends Taught Me About the Future of Search**
Medium · [medium.com/@dkt.officials](https://medium.com/@dkt.officials)

---

## GitHub Analytics

<p align="center">
<img width="48%" src="https://github-readme-stats.vercel.app/api?username=dipto-thakur&show_icons=true&theme=transparent&hide_border=true" />
<img width="46%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dipto-thakur&layout=compact&theme=transparent&hide_border=true" />
</p>

---

## Contact

[Portfolio](https://diptothakur.dev) · [LinkedIn](https://www.linkedin.com/in/diptothakur) · [Email](mailto:dkt.officials@gmail.com) · [GitHub](https://github.com/dipto-thakur)

---

<div align="center">

Built one deliberate decision at a time.

</div>
