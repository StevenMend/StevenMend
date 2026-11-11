<img src="assets/banner.png" alt="Steven Méndez — Product Engineer · Full-Stack & AI Agents. Available now, remote, US hours." width="100%">

Product engineer in Costa Rica. I take products from the first conversation to production — discovery, database and security, backend, design system, frontend, payments and launch — with Claude in the loop at every layer. If it can be automated, I automate it.

<img src="assets/impact.png" alt="1,000+ PRs merged at Dojo · 3 restaurants run my POS · 5 agent personas live · 8 countries use DOJO" width="100%">

## What I've built

### DOJO · [trydojo.io](https://www.trydojo.io)

Learn, build, get paid and launch: the platform for tech talent in Latin America, used in 8 countries. Software Engineer at Dojo Coding Labs, Dec 2025 – Oct 2026.

- **[Doji](https://www.trydojo.io), the AI agent** — five personas (The Mentor, The Tech Lead, The Founder, The Connector, The Guide) behind a router, with semantic search on pgvector, RLS-safe SQL tools, developer matching and project intake. Live in the app and on WhatsApp through the WhatsApp Business API, with voice notes, opt-out and account linking.
- **[Projects](https://www.trydojo.io/projects)** — notarial-grade marketplace: Stripe Connect escrow, dual-signature attestations, milestone gates, dispute resolution and stake-weighted reputation. 11 pgTAP RLS suites passing.
- **[Pathways](https://www.trydojo.io/pathways)** — the learning engine: courses, Mux video lessons, quizzes, assignments and verifiable certificates.
- **CRM + MCP connector** — the company CRM, fed by signature-verified webhooks for Meta leads and WhatsApp, and operated from Claude by the ops team through an MCP server.

`React 19` `TypeScript` `Vite` `Supabase` `pgvector` `Stripe Connect` `Mux` `Gemini` `MCP`

### Fischer POS · [pos-fischer.vercel.app](https://pos-fischer.vercel.app)

Point of sale with Costa Rica electronic invoicing, running every day in 3 restaurants. My own product: I designed it, built it and support it in production.

- **Electronic invoicing with Hacienda** — invoices, tickets and credit notes as signed XML, validated against Hacienda's schemas, sent to the Ministry of Finance and emailed to the customer as PDF + XML. Two issuers on the same tablet (a restaurant and a car wash under different tax IDs), consecutive numbers reserved atomically in Postgres so two tablets never collide, and "fix an invoice" in one tap: credit note + new invoice.
- **The floor** — tables, takeout and QR orders, kitchen printer tickets, customer tabs, inventory, cash count and weekly payroll. Works offline on the tablets and merges changes when the connection comes back.
- **Claude connector** — owners ask Claude for the day's summary, sales, expenses and financial health through an OAuth 2.1 MCP server.

`React` `TypeScript` `Vite` `Supabase` `Postgres` `Hono` `Vercel` `MCP` `OAuth 2.1`

### MenteFut · [mentefutbol.com](https://www.mentefutbol.com)

AI mental coaching for footballers, narrated by Jeaustin Campos, the winningest coach in Costa Rican football history. Diagnostic quiz on four pillars, AI-generated audio sessions, PDF kits and a 30-day plan, with Stripe one-time and monthly plans and an admin retention dashboard. Lead developer.

`Next.js 16` `Supabase` `Stripe` `Gemini`

### Hikari Intelligence Platform

Investor platform for a fund holding: KYC onboarding state machine, portfolios and transactions, a daily-accrual subledger with DECIMAL precision, an audit trail across 7 tables, an affiliate network and an admin back office, 57 screens in all. Lead developer; scaffold to v1.0-beta in 3 days.

`React` `TypeScript` `Supabase` `Postgres` `Vitest`

### DIESSA OS · in development

Water telemetry and remote control for rural aqueducts: tank level, flow, pressure, water quality and pump health on one mobile dashboard. Leading a 3-person team. Demo at [diessa-os.vercel.app](https://diessa-os.vercel.app).

`Next.js` `Supabase`

### Client sites

- **[Rusz Shop](https://ruszshop.com)** — sneaker and streetwear store with ONVO checkout and an admin panel.
- **[Darlope Travels](https://darlopetravels.com)** — private transfers from Liberia airport, with a booking system, ONVO payments and a CRM.

## How I work

> Ship the system, not the snippet.<br>Hardening before users.<br>Clarity is the bottleneck.

Observation first: I spend time with the people who live with the problem before any architecture decision. Then Claude in the loop at every layer (schema, security review, refactors) with code review and CI as the safety net.

## Stack

**Frontend** `React 19` `Next.js` `TypeScript` `Vite` `Tailwind` `shadcn/ui` `TanStack Query`<br>
**Backend & data** `Supabase` `Postgres` `RLS` `Edge Functions` `Node.js` `Hono` `Python` `FastAPI`<br>
**AI** `Claude API` `Claude Code` `Gemini` `OpenAI` `MCP` `RAG` `pgvector`<br>
**Payments & infra** `Stripe Connect` `Vercel` `GitHub Actions`<br>
**Observability** `PostHog` `Sentry` `Langfuse`

## Certifications

| Issuer | Certificates |
|---|---|
| **Anthropic** | [Building with the Claude API](https://verify.skilljar.com/c/ru3tfnwbih7h) · [Claude Code in Action](https://verify.skilljar.com/c/bows5ph8ioze) · [Introduction to Agent Skills](https://verify.skilljar.com/c/3s3hkuby3ikt) |
| **Google** · Coursera | [Foundations of Data Science](https://www.coursera.org/account/accomplishments/verify/8ZRX13R7INNN) · [Go Beyond the Numbers: Translate Data into Insights](https://www.coursera.org/account/accomplishments/verify/RNTPMN4R7IPU) · Get Started with Python |
| **IBM** · Coursera | Introduction to Software Engineering · Introduction to Cloud Computing |
| **Udemy** | [IA Generativa, LLM Apps, Agentes IA (bootcamp)](https://www.udemy.com/certificate/UC-144eeef4-07c6-4132-bcc1-328732d7976b/) · [The Complete Full-Stack Web Development Bootcamp](https://www.udemy.com/certificate/UC-ff9a203d-ebaf-495f-a2ea-c1d0bdaac4cd/) · [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/certificate/UC-40efb957-1598-459e-b26f-e82954716766/) · [Curso completo de Python: Programación en Python desde cero](https://www.udemy.com/certificate/UC-92e2a394-e5cb-47a0-b1ab-aa2732ac74c7/) · [The Ultimate Beginners Course for Computer Science or IT](https://www.udemy.com/certificate/UC-c2c764b8-b981-4a8a-88f8-3b1b7d29cd06/) |

## Let's talk

[rodri.stevenmendez@gmail.com](mailto:rodri.stevenmendez@gmail.com) · [LinkedIn](https://www.linkedin.com/in/steven-mendez-4277602ba/) · [Download my CV](Steven-Mendez-CV.pdf)
