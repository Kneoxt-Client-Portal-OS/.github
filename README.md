Here is a production-ready, clean, and developer-first **GitHub Organization Profile README** (`.github/profile/README.md`) for **InScope**.

***

```markdown
<div align="center">

# InScope

### The Privacy-First Client & Scope Management OS for Software Agencies.

Connect **Contracts** ➔ **Scope** ➔ **Visual Bug Triage** ➔ **Milestone Payouts**.  
Eliminate scope creep, protect margins, and keep developers and clients perfectly aligned.

<br />

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js&logoColor=white)](https://nextjs.org/)
[![Privacy: Zero-AI Training](https://img.shields.io/badge/Privacy-NDA_Safe_(No_AI_Training)-10B981?style=flat-square)](https://inscope.dev/privacy)
[![Discord](https://img.shields.io/badge/Community-Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/inscope)

<br />

[Website](https://inscope.dev) • [Documentation](https://docs.inscope.dev) • [Roadmap](https://inscope.dev/roadmap) • [Report an Issue](https://github.com/inscope/inscope/issues)

</div>

<hr />

## ⚡ The Problem

Building software for clients shouldn't mean drowning in out-of-scope requests, messy email threads, delayed milestone sign-offs, and unpaid maintenance.

```
       FRAGMENTED WORKFLOW                              THE INSCOPE WAY
 ┌─────────────────────────────┐                ┌─────────────────────────────┐
 │  PandaDoc / DocuSign (PDF)  │                │                             │
 ├─────────────────────────────┤                │           INSCOPE           │
 │  Linear / Jira (Code Tasks) │   ────────►    │  • Tokenized SOWs & E-Sign  │
 ├─────────────────────────────┤                │  • Deterministic Scope Guard│
 │  Stripe / Wire (Invoicing)  │                │  • Visual Staging Widget    │
 ├─────────────────────────────┤                │  • 1-Click Change Orders    │
 │  WhatsApp / Slack (Disputes)│                │  • Auto-Milestone Release   │
 └─────────────────────────────┘                └─────────────────────────────┘
```

---

## 🎯 Key Capabilities

* 📄 **Tokenized SOW & Legal Engine:** Create legally sound MSAs, NDAs, and SOWs with dynamic variables (`{{acceptance_days}}`, `{{warranty_period}}`, `{{milestones}}`).
* 🛡️ **Deterministic Scope Guardrail:** Automatically checks client tickets against contractual SOW line items without leaking client data to third-party AI models.
* ⚡ **1-Click Change Orders:** Turn out-of-scope requests into signed, payable addendums (or logged **$0 Goodwill Favors**) in under 30 seconds.
* 📸 **Embeddable Staging Widget:** Collect visual feedback from clients with auto-captured screenshots, OS/browser metadata, screen resolution, and console logs.
* ⏱️ **Auto-Acceptance Timers:** Eliminate hostage milestone payments. If clients don't submit defect reports within the contract window, sign-offs trigger automatically.
* 🔄 **2-Way Developer Sync:** Bi-directional sync with **Linear**, **GitHub Issues**, and **Jira** to keep developers inside their native tools.

---

## 📦 Core Ecosystem Repositories

| Repository | Description | Status |
| :--- | :--- | :--- |
| [`inscope/inscope`](https://github.com/inscope/inscope) | The core web application, client portal, and API service. | ![Active](https://img.shields.io/badge/status-active-success?style=flat-square) |
| [`inscope/widget`](https://github.com/inscope/widget) | Lightweight client feedback & screenshot capture script for staging sites. | ![Active](https://img.shields.io/badge/status-active-success?style=flat-square) |
| [`inscope/contracts`](https://github.com/inscope/contracts) | Open-source, internationally compliant tech MSA/NDA/SOW templates. | ![Public](https://img.shields.io/badge/status-public-blue?style=flat-square) |
| [`inscope/linear-sync`](https://github.com/inscope/linear-sync) | Webhook bridge syncing InScope portal tickets to Linear issues. | ![Active](https://img.shields.io/badge/status-active-success?style=flat-square) |

---

## 🛠️ Architecture & Tech Stack

```
inscope/
├── apps/
│   ├── web/               # Next.js App Router (Client Portal + Agency Dashboard)
│   └── docs/              # Mintlify / Nextra Documentation
├── packages/
│   ├── widget/            # Embeddable vanilla JS canvas capture snippet
│   ├── db/                # Prisma ORM & PostgreSQL schema (Row-Level Security)
│   ├── legal/             # SOW tokenization & template parser
│   └── api/               # tRPC / REST endpoints (Stripe Connect, Linear Webhooks)
```

* **Frontend:** Next.js (App Router), Tailwind CSS, shadcn/ui, Lucide Icons
* **Backend & API:** Node.js, TypeScript, tRPC
* **Database & Auth:** PostgreSQL (Supabase / Prisma) with Row-Level Security
* **Storage:** Cloudflare R2 / AWS S3 (Encrypted PDFs & staging assets)
* **Billing:** Stripe Connect API (Milestones, Retainers, & Invoices)

---

## 🔒 Privacy & Compliance

InScope is engineered for security-conscious dev agencies and strict NDA environments:

- **Zero-AI Training by Default:** Your codebase, contract terms, and client information are never fed into public LLMs.
- **Client Data Isolation:** Strict multi-tenant isolation with encrypted-at-rest document storage.
- **GDPR & DPA Ready:** Built-in European Standard Contractual Clauses (SCC) support.

---

## 🚀 Quick Start (Local Development)

Clone the mono-repository and spin up the local environment:

```bash
# Clone the repository
git clone https://github.com/inscope/inscope.git
cd inscope

# Install dependencies
pnpm install

# Setup environment variables
cp .env.example .env.local

# Run database migrations
pnpm db:migrate

# Start development server
pnpm dev
```

Visit [`http://localhost:3000`](http://localhost:3000) in your browser.

---

## 🤝 Community & Support

* 💬 Join the discussion on our [Discord Community](https://discord.gg/inscope).
* 🐦 Follow development updates on X [@InScopeDev](https://x.com/InScopeDev).
* 📜 Check out our [Contribution Guidelines](CONTRIBUTING.md) to get involved.

<br />

<div align="center">

Made with 🖤 for software agencies and builders worldwide.

**[inscope.dev](https://inscope.dev)**

</div>
```
