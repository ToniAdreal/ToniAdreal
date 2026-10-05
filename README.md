<div align="center">

<img src="assets/header.svg" width="100%"/>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-toniadreal-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/toniadreal)
[![GitHub](https://img.shields.io/badge/GitHub-ToniAdreal-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ToniAdreal)
[![MIT Blockchain](https://img.shields.io/badge/MIT%2015.S12-Blockchain%20%26%20Money-a31f34?style=flat-square)](https://ocw.mit.edu/courses/15-s12-blockchain-and-money-fall-2018/)
[![Patents](https://img.shields.io/badge/Patents-2%20Filed-334155?style=flat-square&logo=googlepatents&logoColor=white)]()
[![Papers](https://img.shields.io/badge/Publications-3%20Papers-334155?style=flat-square&logo=arxiv&logoColor=white)]()

</div>

---

## About

Senior Software Engineer (backend/systems), 5+ years production, with a track record spanning verifiable AI asset protocols, on-chain trust infrastructure, and high-stakes trading products. I design systems where proof comes before liquidity — combining systems-engineering rigor with hands-on full-stack delivery.

Previously **WeBank** (Federated Learning Intern, Blockchain Risk Systems), **Sony** (AI Product Design), and **SUSTech** (Research, Digital Twin Systems). Currently building **Tokenta**, a verifiable AI asset exchange, and the **AllWeb3** trust platform.

Academic background in systems engineering, with 3 published papers and 2 patent applications in AI, digital twin, and ergonomic systems.

---

## Core Competencies

<div align="center">

| Domain | Capabilities |
|---|---|
| **Blockchain Product** | Smart contract escrow, tokenomics design, PRFi/SocialFi mechanics, on-chain reputation systems, DAO governance |
| **AI Infrastructure** | Federated learning (FATE/PyTorch), verification pipelines, oracle-compatible workflows, proof-of-task systems |
| **Full Stack** | Next.js 15, React 19, TypeScript, NestJS, PostgreSQL (Prisma), Docker, GitHub Actions |
| **Web3 Stack** | Wagmi 2, Ethers.js 6, RainbowKit, Viem, multi-wallet authentication, Privy |
| **3D / Creative** | React Three Fiber, Rapier physics simulation, WebGL, interactive badge generators |
| **Data & Analytics** | A/B testing, cohort analysis, KPI modeling, attribution modeling, tokenomics simulations |

</div>

---

## Open Source Engineering

Small, honest, executable projects — TypeScript, zero runtime dependencies, full test suites:

- **[rfc9421-signing-demo](https://github.com/ToniAdreal/rfc9421-signing-demo)** — Executable subset of RFC 9421 HTTP Message Signatures (ed25519 / hmac-sha256, RFC 9530 `Content-Digest` binding), with negative verification tests, typed error codes, real benchmarks, and an honest `SECURITY.md`.
- **[escrow-state-machine-ts](https://github.com/ToniAdreal/escrow-state-machine-ts)** — Rule-level reconstruction of an escrow settlement flow from a portfolio case study: state machine with golden fixtures, settlement reports, fund-flow conservation checks, and invariant tests.
- **[dataquest-task-lifecycle](https://github.com/ToniAdreal/dataquest-task-lifecycle)** — Reconstruction of a task-lifecycle state machine (13 states, 19 transitions, incl. abandonment/expiration/dispute/resubmit) from a case study: Mermaid diagram generation, SLA deadlines, and a runnable CLI demo.

---

## Featured Projects

### Tokenta — Verifiable AI Asset Exchange

> Institutional-grade terminal for trading, verifying, and escrowing AI compute capacity and API access rights. Core thesis: **Proof Before Liquidity**.

A full-stack protocol platform where AI quotas and API access rights are verified, tokenized, and traded through non-custodial smart escrow. Every asset must pass a multi-step verification pipeline before it can be listed. On-chain reputation anchors each participant's history to their wallet identity.

**Architecture:**
- Verification Pipeline: automated endpoint testing, quota validation, proof-hash minting
- Smart Escrow Contracts: non-custodial, condition-based fund release with dispute resolution
- On-Chain Reputation: SBT-anchored trust scores, staking collateral, slashing mechanics
- Tokenta Terminal UI: Bloomberg-inspired monochrome interface, buyer/seller mode toggle, live escrow panel

**Stack:** Next.js · TypeScript · NestJS · PostgreSQL · Prisma · Docker · Smart Contracts · Wagmi · Ethers.js · RainbowKit

**Whitepaper available on request.**

---

### AllWeb3 — Decentralized Web3 Trust Platform

> A multi-portal platform solving the transparency and KOL accountability crisis in Web3 marketing and PR.

Built the complete frontend architecture and product specification for a platform that aggregates on-chain KOL behavior, computes multi-dimensional trust scores, and provides project teams with verifiable marketing intelligence.

**Key Modules:**
- Trust Verification Center: multi-factor KOL wallet analysis, risk scoring, evidence chains
- Blockchain Tracker: interactive timeline of on-chain KOL activity across multiple chains
- KOL Assessment Center: ranked pool with verified badges, investment performance data
- Strategy Builder: smart-contract milestone tools, budget allocation, performance dashboards
- Transparency Monitor: real-time project transparency scoring, on-chain data integrity tracking

**Stack:** Next.js 15 · React 19 · TypeScript · Wagmi 2 · RainbowKit · Ethers.js 6 · Viem · Radix UI · TailwindCSS 4 · React Query 5

**Technical SEO uplift from 38% to 83% site health through structured implementation.**

---

### AW3 PRFi — On-Chain PR Collaboration Protocol

> Product architecture for a trust-minimized PR collaboration and effect verification system on-chain.

Designed the complete product model for a three-portal Web3 platform with smart contract escrow integration, oracle-based verification, and blockchain transaction management across Creator Portal, Project Portal, and Admin Portal.

**Deliverables produced:**
- Full PRD with 500+ Linear task items across 12 workstreams
- Smart contract escrow staking and phased settlement mechanism specifications
- Multi-KOL attribution and incentive distribution modeling (with numerical simulation)
- Database schema design (DrawSQL): users, wallets, campaigns, on-chain transactions, deliverables, KPIs
- Custom admin authentication architecture separate from Privy wallet-based portal auth
- NestJS + PostgreSQL + Prisma + Swagger + Docker + GitHub Actions backend specifications

---

### v0 IRL Event Landing — 3D Interactive Badge System

> Open-source event landing page template with real-time 3D lanyard physics, personalized badge generation, and shareable encrypted URLs.

Built as a production-grade template for global Web3 developer events. Features a fully interactive 3D lanyard with real-time physics simulation, a personalized badge generator with dark/light variants, PNG export, and dynamic Open Graph image generation for social sharing.

[![Built with Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=nextdotjs)](https://nextjs.org)
[![React Three Fiber](https://img.shields.io/badge/React%20Three%20Fiber-black?style=flat-square&logo=threedotjs)](https://r3f.docs.pmnd.rs/)

**Stack:** Next.js · React Three Fiber · Rapier Physics · TypeScript · TailwindCSS · WebGL · Canvas API

**Features:**
- Physics-simulated 3D lanyard with real-time interaction
- Canvas-based badge texture rendering with user name input
- Encrypted shareable URLs with per-user lanyard state
- Dynamic OG image generation via Edge API routes
- Dithered animated background, decrypted text reveal animations

---

### CyberOrigin PRFi — Growth & Incentive Systems

> Led 0-to-1 product build and two fast iterations for a proof-of-reputation-based marketing platform.

**Outcomes:**
- Scaled early user base from 500 to 15,000 in two weeks via referral quest design
- Top campaign exceeded 1 million views
- IA and onboarding redesign delivered +30% retention and conversion uplift
- Designed Sybil-resistant reward mechanics, dispute resolution flows, and slashing rules

---

## Research and Patents

**Published Papers**

- Reform and Practice of Material Sorting Training Course Based on Digital Twin Technology — Springer, BigIoT-EDU 2024, LNICST vol. 659 ([link](https://link.springer.com/chapter/10.1007/978-3-032-18631-7_18))
- Current State and Prospects of Research on AI for Model-Based Systems Engineering — *Systems Engineering and Electronics*, Vol. 47 No. 12, 2025 ([link](https://www.spacejournal.cn/xtgcydzjs/article/doi/10.12305/j.issn.1001-506X.2025.12.21))
- Research on an Image Recognition Automatic Counting System Based on Improved YOLOv8 — IEEE ICPICS 2024 ([link](https://ieeexplore.ieee.org/abstract/document/10795929))

**Patent Applications** (not granted)

- Adaptive Scalp Massage Method, System and Terminal Based on Logarithmic Spiral Structural Algorithm — CN120690375A, filed 2025-05-19, pending ([link](https://patents.google.com/patent/CN120690375A/en))
- Remote Control System of Intelligent Robotic Arm Based on Digital Twin — CN115741682A, filed 2022-11-08, rejected 2024-12-27 ([link](https://patents.google.com/patent/CN115741682A/en))

---

## Professional Timeline

```
2026 — Present   Tokenta (Personal Project)      Founder / Full Stack Engineer
                 Ningbo, China
                 Verifiable AI asset exchange, escrow protocol, on-chain reputation system

2025 — 2026      AllWeb3 (CyberOrigin)         Senior Product Manager
                 Hong Kong SAR
                 Three-portal Web3 PR platform, smart contract escrow, blockchain KOL verification

2025             CyberOrigin PRFi              Product Manager
                 Shenzhen, China
                 0-to-1 PRFi platform, 500→15K users in 2 weeks, +30% retention uplift

2024 — 2025      WeBank                        Federated Learning Intern — Blockchain Risk
                 Shenzhen, China
                 FATE + PyTorch federated models; top 10 Shenzhen FinTech Competition finalist
                 +25% prediction accuracy, -40% machine downtime, +40% credit decision efficiency

2023 — 2025      SUSTech                       Research Assistant, Systems Engineering
                 Shenzhen, China
                 National Innovation Program advisor, 2 patents, 3 papers, 2x national competition prizes

2023 — 2024      Sony (China)                  AI Product Designer
                 Shanghai, China
                 0-to-1 PRD for AurionX; NLP+CV video editing, voice interaction, cross-language media translation
```

---

## Technology Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

</div>

## Certifications

- MIT 15.S12 — Blockchain and Money (Gary Gensler)
- IELTS — Speaking Band 7.5
- Business English Certificate Higher (Cambridge)

---

<div align="center">

**Open to: Senior Software Engineer roles — backend/systems, Web3 protocol engineering, AI infrastructure**

`toniadreal11@gmail.com` · [linkedin.com/in/toniadreal](https://www.linkedin.com/in/toniadreal)

<img src="assets/footer.svg" width="100%"/>

</div>
