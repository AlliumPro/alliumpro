# Oh, hi there!

- **Name:** Ivan Murzin
- **Role:** Frontend Developer (React + TypeScript)
- **Contact me:** [Telegram](https://t.me/alliumpro)

Open to Intern / Junior positions — full-time preferred, remote.
I build production-ready React applications with TypeScript, REST API integration and structured state management.
I take a project from UI implementation to deployment using Docker and CI/CD pipelines — [one of them is live right now](https://brewlog.duckdns.org).

---

## Experience

**Croissant Studio** — Frontend Developer (internship) · May — July 2026

- Built an installable PWA for a large specialty coffee roaster: brewing guidance for customers and product analytics for the business
- Implemented mobile-first React + TypeScript interfaces with offline support

**AI-Impulse Hackathon by Sber** — Nizhny Novgorod · October 2025

- Built a GigaChat-powered recommendation system for Systeme Electric as part of a team

---

## What I Do

- Develop SPA and PWA applications using **React + TypeScript**
- Implement routing, global state management (Redux Toolkit, Context API)
- Work with REST APIs (JWT auth, refresh tokens, error handling)
- Structure frontends with Feature-Sliced Design and keep layer boundaries enforced in CI
- Apply performance optimizations (code splitting, lazy loading, memoization)
- Write the backend when a project needs one (Node.js + Fastify + Zod, schema-generated OpenAPI)
- Configure Docker and GitHub Actions for automated builds and deployments

---

## Skills & Technologies

[![My Skills](https://skillicons.dev/icons?i=react,ts,js,html,css,redux,vite,webpack,nodejs,sqlite,docker,githubactions,nginx,git,github,linux,grafana,figma,vscode&perline=7)](https://skillicons.dev)

### Frontend
- React, TypeScript, JavaScript (ES6+), Redux Toolkit, Context API, React Router, HTML5, CSS3, CSS Modules, responsive layout, PWA

### API & Networking
- REST APIs, OpenAPI, Fetch
- JWT authentication, refresh tokens
- Understanding of HTTP, networking fundamentals

### Backend
- Node.js, Fastify, Zod, SQLite (Drizzle ORM)
- Schema-first API design: validation, serialization and docs generated from one source

### Testing
- Jest, Vitest, React Testing Library, Cypress

### DevOps & Tools
- Docker, Docker Compose
- GitHub Actions (CI/CD pipelines, auto-deploy)
- nginx as reverse proxy, TLS certificates
- Linux basics, Bash
- Basic experience with Grafana + Elasticsearch

### Computer Science Foundation
- Data Structures & Algorithms fundamentals
- Networking & distributed systems basics
- Applied mathematics (Linear Algebra, Probability)
- Basic cybersecurity principles

---

## Top Projects

### **[BrewLog](https://github.com/AlliumPro/brewlog) - Full-Stack PWA Running in Production**

Multi-user coffee brewing journal: log a brew, get the extraction percentage from a TDS reading, save what worked as a recipe. Built end to end — design, frontend, backend, server — and deployed on my own VPS.

- Installable PWA with offline support, light/dark themes and iPhone safe-area layout
- Frontend structured with **Feature-Sliced Design** and CSS Modules; layer boundaries are enforced in CI, not by convention
- Fastify + **Zod** backend where a single schema drives validation, serialization and the generated OpenAPI spec
- JWT authentication in httpOnly cookies (argon2id hashing, sliding 14-day sessions) with per-user data isolation enforced by the type system
- SQLite + Drizzle with forward-only migrations and nightly backups
- Multi-stage Docker image published to GHCR, deployed by GitHub Actions to a VPS behind nginx with TLS, vulnerability scanning and health-gated rollback
- Unit, component and e2e tests (Vitest, Testing Library, Cypress) behind a single `npm run verify` gate: typecheck, lint, WCAG contrast check, tests, build

**Result:** A real service with real users, an automated path from `git push` to production, and a rollback that has been tested rather than assumed.

🔗 **Live:** [brewlog.duckdns.org](https://brewlog.duckdns.org) · **Code:** [github.com/AlliumPro/brewlog](https://github.com/AlliumPro/brewlog)

### **[Stellar Burger](https://github.com/AlliumPro/stellar-burgers) - React + Redux Application**

Single Page Application with routing, global state management and authenticated user flows.

- Configured client-side routing with React Router (including protected and dynamic routes)
- Implemented global state management using Redux Toolkit and async thunks for API integration
- Built authentication flow with protected routes and token-based access
- Implemented real-time order feed (WebSocket-based updates)
- Developed modal routing for ingredients and order details
- Added form handling with validation and UX loaders

**Result:** Fully functional SPA with authentication, role-based access, real-time updates and structured Redux architecture.

### **[LibNet](https://github.com/IU-Capstone-Project-2025/libnet) - Multi-Library Aggregator**

Full-stack university capstone project for multi-library book search and reservation management.

- Designed full UI/UX in Figma and implemented React-based interface
- Deployed application to VPS using Docker and docker-compose
- Configured CI/CD pipeline with GitHub Actions for automated deployment
- Set up custom domain with HTTPS (SSL)

### **[WebLarёk](https://github.com/AlliumPro/weblarek) - TypeScript Architecture & Data Modeling Project**

Designed and implemented the data architecture of an online store using MVP pattern.

- Designed application architecture with clear separation of concerns
- Defined TypeScript interfaces for domain models (Product, Buyer, Order)
- Implemented data-layer classes (Catalog, Cart, Buyer) with isolated responsibility
- Built validation logic for buyer data with structured error reporting
- Developed communication layer for API integration (GET products / POST orders)

**Result:** Scalable, type-safe architecture with clear separation between data models and API layer.

### **[Smart Table](https://github.com/AlliumPro/smart-table) - API-Driven Data Table Refactoring**

Refactored a client-side smart table to work with a remote API using query-based filtering, sorting, searching and pagination.

- Replaced local data processing with server-driven query parameters
- Implemented async rendering pipeline with API integration (GET records)
- Implemented server-based filtering, searching, sorting and pagination via URLSearchParams
- Added request caching mechanism to prevent redundant API calls
- Removed legacy client-side comparator logic (300+ lines) while preserving functionality

**Result:** Server-side filtering, sorting and pagination with async rendering and clean query-driven architecture.

### Also worth a look

- **[Blog Customizer](https://github.com/AlliumPro/blog-customizer)** — interactive page customization through a sidebar panel: controlled forms with delayed state application, outside-click handling, dynamic styling via CSS variables, UI-kit composition with Storybook
- **[Closing Tag](https://github.com/AlliumPro/zakrivayuschiy-teg-f)** — advanced CSS: fluid typography with `clamp()`, variable fonts, multi-layer gradients, accessible `<dialog>` modal, SVG heart animation with keyframes, blend modes and filters

---

## Education

- [BSc in Information Systems Engineering](https://apply.innopolis.university/bachelors/information-systems-engineering/) - Innopolis University, 2023-2027
- [Frontend-developer](https://practicum.yandex.ru/frontend-developer/) - Yandex Practicum, 2025-2026

---

## Languages

- Russian — Native
- English — C1 (comfortable with documentation, technical discussions, and interviews)

```
     _    _ _ _                 ____
    / \  | | (_)_   _ _ __ ___ |  _ \ _ __ ___
   / _ \ | | | | | | | '_ ` _ \| |_) | '__/ _ \
  / ___ \| | | | |_| | | | | | |  __/| | | (_) |
 /_/   \_\_|_|_|\__,_|_| |_| |_|_|   |_|  \___/

```
