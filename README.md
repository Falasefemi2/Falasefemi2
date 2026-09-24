<h1 align="center">Hi, I'm Falase 👋</h1>

<p align="center">
  <strong>Backend-leaning software engineer building APIs, services, and full-stack products with Go and TypeScript.</strong><br>
  I care about concurrency, databases, distributed systems, and the trade-offs that appear once software meets production.
</p>

<p align="center">
  <a href="https://pharlase-femmie.vercel.app">Portfolio</a> ·
  <a href="https://femifalase.vercel.app">Backend Portfolio</a> ·
  <a href="https://www.linkedin.com/in/falase-femi-91121b227">LinkedIn</a> ·
  <a href="https://github.com/Falasefemi2">GitHub</a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,ts,js,java,python,react,nextjs,postgres,supabase,docker,aws,git,github" alt="Technology stack" />
</p>

---

## About Me

- Backend engineer working primarily with **Go**, **TypeScript**, and **Effect**
- Author of [`@pharlase/paystack-effect`](https://www.npmjs.com/package/@pharlase/paystack-effect), a published Effect SDK for 20+ Paystack resources
- Experienced in building accessible React/TypeScript products used in enterprise environments
- Enjoys rebuilding interesting systems in different stacks to understand the trade-offs firsthand
- Currently exploring Go backend engineering, Effect, PostgreSQL internals, distributed systems, system design, DSA, and Spring Boot

## Featured Work

### [`local-deploy`](https://github.com/Falasefemi2/local-deploy) — Local-first deployment platform

A Vercel-style deployment pipeline built with Effect v4, Bun, PostgreSQL, and Next.js. It detects project types, builds and archives applications, stores deploy artifacts in Supabase Storage, and streams build logs and deployment events to a React dashboard over REST and Server-Sent Events.

**Stack:** Effect · TypeScript · Bun · PostgreSQL · Supabase · Next.js · React · TanStack Query · SSE

### [`paystack-effect`](https://github.com/Falasefemi2/paystack-effect) — Typed Paystack SDK

An Effect-native SDK covering more than 20 Paystack resources through typed, schema-validated services, with a declarative `HttpApi` specification and a runnable Swagger/OpenAPI server.

**Stack:** Effect · TypeScript · Schema · HttpApi · OpenAPI · Vitest

### [`eazyrent`](https://github.com/Falasefemi2/eazyrent) — Geospatial rental platform

A rental backend built with Go's standard library, PostgreSQL/PostGIS, JWT authentication, rotating refresh tokens, generated Swagger documentation, and geospatial property search. The same domain was also implemented in Effect-TS with Redis, Drizzle, and TanStack Start.

**Stack:** Go · PostgreSQL · PostGIS · JWT · Swagger · Effect · Redis · Drizzle

### [`fileupload`](https://github.com/Falasefemi2/fileupload) — Object storage platform

A Google Drive-inspired file storage system with folder hierarchies, file metadata, Google OAuth, and direct-to-object-storage uploads. The architecture keeps file bytes away from the API server while maintaining typed metadata and access control.

**Stack:** Go · `net/http` · pgx · Neon · Cloudflare R2 · Next.js · React · OAuth 2.0

### [`bot-review`](https://github.com/Falasefemi2/bot-review) — CI quality-gate action

A reusable GitHub Action that runs 18 checks across type checking, linting, test coverage, secret detection, static analysis, and dependency auditing, followed by an advisory LLM code review.

**Stack:** Effect · TypeScript · GitHub Actions · Semgrep · Gitleaks

### [`companyflow`](https://github.com/Falasefemi2/companyflow) — Multi-tenant HRMS/ERP

A full-stack HR and operations platform with tenant isolation, RBAC, JWT authentication, audit logging, Swagger documentation, and a responsive administration interface for employees, departments, leave, memos, and approvals.

**Stack:** Go · PostgreSQL · Gorilla Mux · React · TypeScript · REST API

## Tech Stack

| Area | Technologies |
| --- | --- |
| **Backend** | Go · TypeScript · Effect · Node.js · Bun · Hono · REST · OAuth 2.0 · JWT |
| **Data** | PostgreSQL · PostGIS · Redis · Drizzle ORM · pgx · Neon · Supabase |
| **Frontend** | React 19 · Next.js · TanStack Start · TanStack Query · Tailwind CSS · shadcn/ui |
| **Cloud & DevOps** | Docker · AWS · GitHub Actions · Vercel · Railway · Koyeb · Linux |
| **Testing & Quality** | Vitest · Go testing · OpenAPI · Swagger · Gitleaks · Semgrep |

## How I Build

- Model business logic with clear domain boundaries and typed errors
- Use Effect services, layers, schemas, and managed runtimes for explicit dependencies
- Keep file data out of application servers with direct-to-object-storage uploads
- Protect refresh tokens with rotation and reuse detection
- Test failure paths, not only the happy path
- Treat observability, security, and maintainability as product features

## GitHub Activity

<p align="center">
  <img src="https://github-contribution-card.vercel.app/api?username=Falasefemi2" alt="Falasefemi2's GitHub contribution graph" />
</p>

---

Let's build something dependable. If you're interested in Go, Effect, backend architecture, or system design, [let's connect on LinkedIn](https://www.linkedin.com/in/falase-femi-91121b227).
