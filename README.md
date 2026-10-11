# Christian Tang Christensen

**Chief Technology Officer @ [Edition](https://edition.dk)** · Shopify Premier Partner · Denmark<br>
**Founder of [Studio CC](https://studiocc.dk)**: independent software development

Engineering leader with 7+ years shipping custom systems, Shopify apps and integrations. TypeScript, Go and Rust across the stack, and the infrastructure to run it.

---

## 👋 About

I lead engineering at **Edition**, a Shopify Premier Partner in Denmark, where we build Shopify apps, integrations and the systems behind modern e-commerce. I own the technical side of the business: architecture, platform, infrastructure and the standards we build by.

I'm hands-on. Most days I'm in the code, shipping apps, integrations and the services behind them.

My path here:
- Self-taught roots: freelance **WordPress / PHP** builds for small clients
- Joined Edition (formerly Ejlskov Design) as an **intern**
- Landed a full-time role as **Frontend Developer**
- Moved into **Backend / Full-stack**
- Stepped up as **CTO**, leading the engineering team

What I care about most is pragmatic architecture: systems that are fast, simple to operate and easy for the next developer to change.

Alongside Edition, I take on a few independent projects through **[Studio CC](https://studiocc.dk)**: web apps, APIs and backend systems. Full case studies live there.

> **Note:** Most of my work lives in private client and company repos, so the contribution graph here only tells a fraction of the story.

---

## 🚀 Selected Work

**[Edition – Expansion Store Sync](https://apps.shopify.com/edition-expansion-store-sync)** · Shopify App Store *(live since Jan 2026)* · [case study](https://studiocc.dk/work/expansion-store-sync)

One master store keeps any number of market stores in sync: products, inventory, collections, metaobjects, pages, blogs and metafields, with rules, prices and translations per store. Every Admin API call is paced by a shared token bucket in Redis, so it runs at each store's real Shopify rate limit without getting throttled. It has synced over 1.5 million product updates in a single store network in under 24 hours.

`5.0 ★ on the Shopify App Store` · Solo developer, end to end. TypeScript, Next.js, PostgreSQL, Redis + BullMQ.

**Edition – Ops & Hosting Platform** *(in progress)* · [case study](https://studiocc.dk/work/edition-ops-platform)

Moved Edition's app fleet from DigitalOcean to Hetzner with Dokploy, for roughly 90% lower hosting cost once everything has moved. Around it, a self-hosted ops platform: OpenTelemetry into Grafana, Prometheus, Loki and Tempo, uptime checks as code in Gatus, and one login through Authentik. Putting a new app under monitoring takes one command.

**Edition – DataLayer & Tracking** *(in development)* · [case study](https://studiocc.dk/work/datalayer-tracking)

A Shopify app that gives a store one data layer across storefront and checkout, and delivers every event to up to 13 ad and analytics platforms from the browser and the server, only after consent. A plain Node collect service, one queue per platform, missed-purchase rescue from the order webhook, and visitor events that are never stored.

**Shopify App Template** · [case study](https://studiocc.dk/work/shopify-app-template)

Our foundation for production Shopify apps: Next.js, Redis + BullMQ with an inline fallback, a typed event bus, codegen'd GraphQL, GDPR, billing, alerting and OpenTelemetry built in. One setup command to a running app. Every Shopify app we ship runs on it.

**Shopify Theme Template** · [case study](https://studiocc.dk/work/shopify-theme-template)

TypeScript web components with Vite and Tailwind CSS, and a GitHub Actions pipeline that previews every change, rehearses each merge on a copy of the live theme, and deploys only changed files to one store or many, without touching what the merchant owns.

---

## 🛠️ Tech Stack

**Languages & Frameworks**
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

**Data & Jobs**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-EA1A1A?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=flat-square&logo=prisma&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

**Shopify & E-commerce**
![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white)
![Shopify Apps](https://img.shields.io/badge/Shopify_Apps-008060?style=flat-square&logo=shopify&logoColor=white)
![Liquid](https://img.shields.io/badge/Liquid-7AB55C?style=flat-square&logo=shopify&logoColor=white)
![Hydrogen](https://img.shields.io/badge/Shopify_Hydrogen-008060?style=flat-square&logo=shopify&logoColor=white)
![Payload CMS](https://img.shields.io/badge/Payload_CMS-000000?style=flat-square&logo=payloadcms&logoColor=white)

**Infrastructure & Observability**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white)
![Dokploy](https://img.shields.io/badge/Dokploy-000000?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

*Also worked with: Python, Express, Gin/Fiber, tRPC, MySQL, SQLite, Drizzle, pg-boss, shadcn/ui, Framer Motion.*

---

## 🎯 What I focus on

- **Software architecture**: event-driven systems, background job pipelines, rate limits handled at the source, and systems that are simple to operate and easy to change
- **Shopify apps & integrations**: from a public App Store product to custom apps and the glue between business-critical platforms
- **Platform & DevOps**: the app and theme templates, CI/CD, self-hosted infrastructure and observability that every Edition project runs on
- **Technical leadership**: our stack, standards and review process, and keeping the team shipping without burning out

---

## 📫 Get in touch

Always open to a good conversation about systems, Shopify or a tricky engineering problem. LinkedIn or email works best.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christian-tang-christensen/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge)](mailto:christian@studiocc.dk)
[![Studio CC](https://img.shields.io/badge/Studio_CC-111111?style=for-the-badge&logoColor=white)](https://studiocc.dk)
