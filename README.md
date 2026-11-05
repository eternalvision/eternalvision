# Alexander Priadchenko

**Software Engineer · Full-stack, frontend platforms & DevOps**

Prague, Czechia

[Portfolio](https://portfolio.eternalvision.cc/) · [LinkedIn](https://www.linkedin.com/in/priadchenko) · [GitHub repositories](https://github.com/eternalvision?tab=repositories) · [GitLab](https://gitlab.com/eternalvision) · [Email](mailto:al.priadchenko@gmail.com)

I build web products and the systems that ship them. My work spans travel booking, fintech, and B2B SaaS, from React and Svelte interfaces to Node.js APIs, shared packages, CI/CD, and production infrastructure. I’ve also built native Android software and taught web engineering.

## What I’m working on

### [ASIANA / Letuška](https://www.letuska.cz/) · Full-Stack & DevOps Engineer

**Aug 2026 – present**

- Work across [letim.cz](https://letim.cz/), a travel booking platform built with SvelteKit, Svelte 5, and Express 5, and existing Letuška applications built with Angular and NgRx.
- Modernized a TypeScript monorepo through a pnpm migration, staged dependency upgrades, per-package Vitest coverage, and stronger types in shared models. Built shared development configuration and a CLI for Angular, SvelteKit, and Express projects.
- Work on booking and payment integrations, PostgreSQL-backed services, and typed authentication with Redis-backed sessions. Support production delivery with GitLab CI/CD, Docker, Kubernetes, private registries, and OpenTelemetry tracing. Build internal AI tooling for engineering workflows with Claude Code and MCP.

### [VýpisFlow](https://www.vypisflow.cz/en) · Browser-based accounting SaaS

I built the initial product for [LV účetnictví](https://www.lvaccounting.eu/) in Jul–Aug 2026 and continue to develop it. It converts bank statements into **POHODA XML, MultiCash, and ABO/GPC**. The product now also supports invoice imports for POHODA. Source documents are processed in the browser.

- Built bank-specific parsers, opening and closing balance reconciliation, and a Vitest matrix covering **165 bank, currency, and export combinations** at launch.
- Added conversion previews, saved export profiles, and batch ZIP downloads. Built with Next.js, TypeScript, Redux Toolkit, and Tailwind CSS, with Clerk for authentication, Stripe for billing, and Cloudflare Pages and D1 for hosting and data.

## Engineering experience

<details>
<summary><strong>Time Anthropology Foundation</strong> · Frontend Team Lead · Started Mar 2026</summary>

- Led a three-person frontend team while implementing features, reviewing code, and making architecture decisions.
- Built a React 19 and TypeScript monorepo with Vite, pnpm, and Turborepo. Published a shared Mantine-based UI library to a private GitLab npm registry.
- Shipped a mobile-first customer app and a back-office admin app from the same UI foundation, with Redux Toolkit, localization, analytics, and a shared release pipeline.

[TAF Projects](https://www.tafprojects.com/)

</details>

<details>
<summary><strong>Simplecoin</strong> · Frontend Platform, DevOps &amp; Android · Nov 2024 – May 2026</summary>

- **Frontend Platform Engineer · Nov 2024 – May 2026.** Rebuilt the frontend of a live crypto exchange from React 17 and Parcel into a React 19, Vite, and pnpm/Turborepo monorepo. Split exchange, wallet, landing, and maintenance into independently deployable apps and built shared UI and app foundations. Owned frontend API contracts, state, localization, tests, and release tooling.
- **Platform & Release / DevOps Engineer · Jun 2025 – May 2026.** Owned multi-host Docker and Traefik delivery for the exchange, wallet, landing, and WordPress sites. Set up per-app GitLab pipelines, private npm publishing, environment promotion, and production observability. Ran wallet infrastructure and managed secure operator access.
- **Android Application Engineer · Sep 2025 – Jan 2026.** Built a Kotlin and Jetpack Compose app for hardware-backed transaction signing using Android Keystore and ECDSA. Used Room, DataStore, OkHttp, and WorkManager. Automated signed APK releases in GitLab CI, added in-app updates, and reduced APK size by 64% with R8.

[Simplecoin](https://www.simplecoin.eu/en) · [Exchange](https://exchange.simplecoin.eu/) · [Wallet](https://wallet.simplecoin.eu/)

</details>

<details>
<summary><strong>Odin Pay</strong> · Infrastructure Team Lead / Acting CTO · Jun–Dec 2025</summary>

- Owned Linux, PostgreSQL, Nginx, and systemd infrastructure for a fintech payments platform. Defined backup and disaster recovery runbooks, vulnerability management, and production operations.
- Set up identity and access with Keycloak and Camunda, integrated DFNS, and implemented security monitoring with Wazuh and SIEM tooling.
- Delivered and maintained the Angular operator console and its deployment pipeline.

[Odin Pay](https://odinpay.eu/)

</details>

<details>
<summary><strong>Client work</strong> · INSTARUM, LV účetnictví, Create Business Club &amp; ART VIKO</summary>

- **INSTARUM · Freelance Frontend Engineer · May–Jun 2026.** Delivered a four-language Next.js 16 and React 19 site for a Prague engineering company, with an accessible project gallery, light and dark themes, a validated contact form, Resend, structured SEO, and Google Consent Mode. [INSTARUM](https://www.instarum.cz/)
- **LV účetnictví · Frontend Engineer · Aug 2025.** Built a multilingual Next.js marketing site with pricing tied to package-specific enquiries, Resend confirmations, Google Sheets review ingestion, GTM lead events, and GitHub Actions deployments to Vercel. [LV účetnictví](https://www.lvaccounting.eu/)
- **Create Business Club · Webflow Developer / Layout Designer · Nov 2024 – Jan 2025.** Built responsive marketing pages and maintained their content in Webflow.
- **ART VIKO · Full-Stack Web Developer · Oct 2022 – Mar 2023.** Built a React, Express, and MongoDB workforce and payroll platform with role-based access, JWT, multilingual workflows, editable grouped tables, ASMIS integration, and internal reporting. [ART VIKO](https://www.artviko.cz/cs)

</details>

<details>
<summary><strong>STEP IT Academy</strong> · Engineering Educator &amp; Course Author</summary>

- **Prague · Frontend Engineering Educator & Mentor · Jan 2023 – Oct 2025.** Mentored 18+ cohorts through project-based HTML, CSS, JavaScript, React, architecture, and debugging. [STEP IT Academy Praha](https://praha.itstep.org/)
- **Kyiv · Backend Engineering Educator & Course Author · Jan–Jul 2024.** Designed and taught a practical Node.js course covering Express, PostgreSQL, MongoDB, authentication, WebSockets, email workflows, and cloud deployment. [STEP IT Academy](https://itstep.org/ru)

</details>

## Toolbox

| Area | Tools and practices |
| --- | --- |
| Web applications | TypeScript, JavaScript, HTML, CSS, Sass, React, Next.js, Preact, Vue, Svelte 5, SvelteKit, Angular, NgRx, Redux Toolkit, TanStack Query, i18n |
| UI and forms | Tailwind CSS, Material UI, Mantine, Radix UI, shadcn/ui, Framer Motion, React Hook Form, Zod, Storybook, Figma, Webflow, Spline, Photoshop |
| APIs and data | Node.js, Express, NestJS, Fastify, REST, OpenAPI, WebSockets, PostgreSQL, Prisma, Redis, MongoDB, Cloudflare D1, Firebase, SurrealDB |
| Platform and delivery | pnpm, Turborepo, Vite, Webpack, Babel, Linux, Bash, Git, Docker, Kubernetes, Traefik, Nginx, GitLab CI/CD, GitHub Actions, Cloudflare Pages, AWS EC2, Coolify, Proxmox, Teleport, Warpgate |
| Quality and operations | Vitest, Testing Library, Cypress, Postman, OpenTelemetry, SigNoz, Graylog, Filebeat, Wazuh, SIEM |
| Mobile, identity and payments | Kotlin, Jetpack Compose, Android Studio, Android Keystore, ECDSA, Keycloak, Camunda, OAuth 2.0, JWT, Clerk, Stripe |

<details>
<summary><strong>Education &amp; certifications</strong></summary>

- **MSc, Automation and Computer-Integrated Technologies** · Donbas State Engineering Academy · 2022–2023
- **BSc, Automation and Computer-Integrated Technologies** · Donbas State Engineering Academy · 2018–2022
- **Full-Stack Developer** · [GoIT](https://goit.global/ua/) · 2022
- **Front-End Developer** · [Computer Academy STEP](https://itstep.org/ru) · 2021

[Donbas State Engineering Academy](https://www.dgma.donetsk.ua/)

</details>
