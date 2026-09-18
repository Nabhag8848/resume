# Career source: old resume

User-provided resume content, saved September 18, 2026. This is a source record, not a revised resume. Claims, metrics, dates, and attribution have not yet been independently verified. Formatting markup was normalized to Markdown; commented-out material is retained separately.

## Identity and profiles

- Name: Nabhag Motivaras
- Email: motivaras.nabhag@gmail.com
- Portfolio: https://nabhag.dev
- GitHub: https://github.com/Nabhag8848
- LinkedIn: https://www.linkedin.com/in/nabhagmotivaras/
- Twitter: https://twitter.com/NabhagMotivaras
- LeetCode (added by user): https://leetcode.com/u/NabhagMotivaras/
- Phone in commented-out source: +91 79844 50754

## Technical skills

- Languages: Go, TypeScript
- Infrastructure: Terraform, ECS, Lambda, ECR, Lightsail, SQS, SNS, S3, CloudWatch, Docker
- Backend: Echo, sqlc, Goose, PostgreSQL, NestJS, Redis, BullMQ, Rxjs
- Applied AI: LangChain, Langraph, Agent SDK, MCP
- Frontend: React, React Router, React Query, Zustand, Zod

Spelling and product identity to confirm later: "Langraph", "Agent SDK".

## Work experience

### Applied AI Consultant — Dec 2025–Present

Link: https://github.com/Nabhag8848

Automating complex workflows by orchestrating agents.

### Health and Wellbeing — June 2025–Nov 2025

Documented detailed blog: https://nabhag.dev/blog/sabbatical

### Rocket Health — Freelance Software Engineer — Sept 2024–May 2025

Remote. Company: https://rockethealth.app

- Sole engineer, architected system from scratch powering 50k+ users, 160K+ teleconsults, $1m+ ARR.
- Database schema design: https://dbdiagram.io/d/Prisma-Generated-66f4e6c53430cb846ca92ea6
- Architected event-driven backend integrating Calendly, Typeform, Razorpay webhooks, orchestrating async workflows with real-time synchronization.
- Built RBAC web app for operations team managing permissions and reducing manual work by 80%.
- Engineered migration pipeline for 160K+ records maintaining data integrity.
- Automated workflows (auto-cancellation, payment reconciliation, reminders), saving 10+ hours/week and reducing errors by 90%.

### Revert — Opensource Developer (Contract) — May 2024–Aug 2024

Hybrid. Repository: https://github.com/revertinc/revert

- Built the entire user-facing client-side and managed production during critical maintenance periods.
- Implemented robust two-way data synchronization, field mappings, webhook system and end-to-end OAuth flows (authorization, token refresh, error handling) to support multiple integrations.
- Adapted and optimized the isomorphic JavaScript client SDK to align with customer workflows.
- Reviewed and validated new integrations to ensure reliability and stability.

### Rocket.Chat — Google Summer of Code — May 2023–Sept 2024

Remote. Program project: https://summerofcode.withgoogle.com/programs/2023/projects/9v76k7Q8

- Mentored AI In-channel GIF Generator in Google Summer of Code 2024: https://github.com/RocketChat/google-summer-of-code/blob/main/google-summer-of-code-2024.md#ai-in-channel-gif-image-generator
- Integrated Notion into Rocket.Chat, to benefit a user base of 12 million individuals during GSoC Program, helping org close more sales deals even after 2 years.
- Authored comprehensive solution outlining a backward-compatible approach for Apps Authorization: https://github.com/Nabhag8848/RocketChat.Apps-OAuth2
- Commented-out bullet: Resolved Critical bugs within the GitHub Integration, enhancing user experience and functionality.

### Neev Technologies Inc. — Software Engineer Intern — May 2022–July 2022

Remote. Company: https://neev.finance/

- Worked on Monitoring Tool to provide real time analytics of spread between crypto derivatives for integrating four different Crypto Exchange (FTX, OKX, Binance, Houbi Global).

## Projects

### LYO — Virtual Fitting Room

- Product: https://lyo.fashion
- Repository: https://github.com/Nabhag8848/lyo
- Stack: NestJS, React, WXT, PostgreSQL, Redis, SSE, S3, Lightsail
- LYO is virtual fitting room for trying outfits while shopping online in-browser.
- Bulit real-time pipeline using SSE with Redis pub/sub, delivering instant feedback while offloading AI inference via webhooks.
- Extension handles global state in different execution context, across multiple tabs, worker service, side panel with optimistic UI updates.
- Architected scalable backend with webhook-based async job orchestration having ability to scale to any ecommerce platform.

### Ask Postgres

- Repository: https://github.com/Nabhag8848/ask-postgres
- Stack: Go, BubbleTea, Langchain, PostgreSQL, Docker
- Built an open-source, local-first, Claude Code-like CLI for querying your own PostgreSQL in plain English, keeping the data and session on your machine.
- Uses a read-only tool loop—schema exploration plus capped, timed pulls—so the assistant works from real tables and columns rather than inventing them.
- TUI with streaming replies; conversation memory via persisted sessions on disk, slash commands, and multi-provider LLM support.

### Notion Integration for RocketChat

- Work/project repository: https://github.com/Nabhag8848/google-summer-of-code
- Integration repository: https://github.com/RocketChat/Apps.Notion
- Figma design: https://www.figma.com/file/1Tk99mGHBmbQpOiT3vP17i/NotionApp
- Demo video: https://www.youtube.com/watch?v=G1fZBqy5jp8
- Stack: Typescript, Apps Engine, DeclarativeUI, Notion API
- Led the development of a Notion integration, successfully allowing teams to manage and switch between multiple Notion Workspaces without leaving the chat interface.
- Built robust, two-way functionality that streamlined the entire workflow, enabling users to instantly create, share, view, and comment on Notion Pages directly within RocketChat.

## Commented-out projects retained from source

### Production Grade Backend API

- Repository: https://github.com/DhairyaMajmudar/Redis-Prisma-Backend-API
- Stack: NodeJs, ExpressJs, Prisma, Redis, PostgreSQL, AWS
- Engineered a scalable production-grade Backend API, for a small-scale startup in Bangalore having 100+ daily users.
- Architected and deployed scalable production-grade REST API serving 100+ daily active users for a Bangalore based startup, implementing microservices architecture with Node.js and Express.js.
- Implemented cloud infrastructure on Amazon AWS with automated CI/CD pipeline, ensuring 99.9% uptime and seamless deployment processes for the production environment.
- Attribution needs confirmation: repository belongs to a different GitHub account; do not assume ownership.

### Twenty Raycast Extension

- Extension: https://www.raycast.com/NabhagMotivaras/twenty
- Repository at supplied commit: https://github.com/raycast/extensions/tree/1f162e3a5b99c3d9cf99b8c93c2ac58c7cae9072/extensions/twenty/
- Stack: Typescript, React, Zod, RaycastUI
- Built a Raycast Extension for TwentyCRM (YC S23) to simplify CRM management.
- Enabled instant record creation across standard and custom objects.
- Implemented automatic schema updates, ensuring new or deactivated objects reflect in real-time.

## Education

Charotar University of Science and Technology, India.
B.Tech in Computer Engineering. CGPA: 8.7/10.
Graduation date not provided.

## Recent project outside old resume

### Orchex

- Repository: https://github.com/Nabhag8848/Orchex
- Description supplied by user: durable workflows.
- Positioning target: recent infrastructure work relevant to AI infrastructure, sandboxes, workflow execution, and orchestration companies.
- README, documentation, schema, design, demo, architecture, deployment, scale, and personal-contribution details still need to be extracted from the repository.
