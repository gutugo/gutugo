# Sergey Kravtsov

**QA Engineer | Manual & Automated Testing | Agentic Engineering**

I test web applications, APIs, and mobile products and develop software using AI coding agents. My experience includes a QA internship at a US healthcare SaaS company and hands-on development and testing of applications for an operating lumber business.

I’m seeking **remote QA Engineer, Software QA Analyst, and QA Automation Engineer opportunities with North American teams** and am open to relocation.

[LinkedIn](https://www.linkedin.com/in/serg-kravtsov/) · [Telegram](https://t.me/gutugo) · [Email](mailto:skravtsov@gmail.com)

## QA and engineering approach

- Translate requirements and business rules into test cases and reproducible automated checks.
- Combine functional, regression, exploratory, API, and database testing with unit, component, integration, and end-to-end tests.
- Use equivalence partitioning, boundary value analysis, decision tables, and pairwise testing.
- Investigate failures and check financial calculations, permissions, state transitions, validation, and fallback behavior.
- Use Claude Code and Cursor for implementation, test development, debugging, and review, with explicit requirements and human verification.

**Tools:** Python, TypeScript, SQL, pytest, Playwright, Vitest, Jest, React Testing Library, Postman, Swagger, Git, Jira, PostgreSQL, and Docker.

## Selected business projects

### BigHouse ERP

ERP for a lumber business, covering quotes, orders, inventory allocation, production, shipping, and business documents. This is my main project for connecting business requirements with software quality.

Selected automated checks cover:

- Financial calculations, rounding, and consistency across orders, invoices, and shipping documents.
- Role-based permissions for pages, APIs, and server actions.
- Document state transitions, including rejected operations.
- Inventory, reservation, and production workflows.
- Integration behavior against a real PostgreSQL database.

The repository includes unit, component, architecture, security, and database integration tests, with coverage gates and isolated test environments.

**Stack:** TypeScript, Next.js, React, Prisma, PostgreSQL, Vitest, React Testing Library, Docker.  
**Source code:** private.

### BigHouse — Product Catalog & Quote Requests

Product catalog and quote-request website for the same lumber business. Visitors browse products and variants and submit quote requests.

API and component tests use Vitest and React Testing Library. Playwright scenarios cover product selection and quote submission. CI includes lint, TypeScript checks, and tests with coverage gates.

**Stack:** TypeScript, Next.js, React, Prisma, PostgreSQL, Playwright, Vitest.  
**Website:** [bighouse.ru](https://bighouse.ru) · **Source code:** private.

### BigHouse CRM Agent

CRM automation that processes email, Telegram messages, and calls with LLM classification, maintains client and order records, and delivers reports through YouGile.

Python test suites cover message-processing rules, contact and order deduplication, API behavior, and cloud-to-local LLM fallback, using unit, API, integration, and end-to-end checks.

**Stack:** Python, FastAPI, SQLAlchemy, PostgreSQL, Redis, pytest, cloud LLMs, Ollama.  
**Source code:** private.

### Tion Filter Sales Bot

B2B Telegram ordering workflow for a ventilation filter dealer: catalog, cart, company lookup, manager review, editable orders, PDF invoices, and delivery by email and chat.

**Stack:** Python, aiogram, SQLite, ReportLab, Dadata.  
**Source code:** private.

## QA internship and public code

### base86 — QA Engineering Intern

**December 2025 – May 2026 · Remote · US healthcare SaaS**

Performed manual functional, regression, and exploratory testing across procurement, catalog management, and analytics. Designed and maintained **100+ test cases**, tracked defects in Jira, and worked in a Scrum team.

#### [Catalog Data Extractor](https://github.com/gutugo/catalog-data-extractor)

Built during the internship on a direct assignment from the CEO to extract structured product data from supplier PDF catalogs. Includes local GLM-OCR inference through Ollama, table parsing, validation, confidence indicators, fallback behavior, and a Flask interface for human review and CSV export.

Public QA examples include pytest fixtures and mocks, Flask API tests, validation and CSRF checks, missing-record handling, and OCR connection and malformed-response failures.

**Core stack:** Python, Flask, pytest, GLM-OCR, Ollama.

## Personal side project

### [Tropy — Android Hiking App](https://tropy.app)

My personal hiking app, **released as a beta in RuStore**. Features include route browsing, offline maps, GPS track recording, and GPX/KML import.

The project includes mobile tests with Jest and React Native Testing Library, backend tests with Vitest, PostgreSQL/PostGIS integration tests, Detox E2E scenarios, and Stryker mutation testing.

**Stack:** TypeScript, React Native, Expo, Fastify, PostgreSQL/PostGIS, MapLibre.  
[RuStore](https://www.rustore.ru/catalog/app/app.tropy) · [Public builds](https://github.com/gutugo/tropy) · [Website](https://tropy.app)  
Application source code is private; the public repository hosts builds.

## Background

Before moving into software, I worked in engineering and operations leadership across manufacturing, mining, and hospitality. That experience helps me understand business workflows, prioritize risks, and communicate with technical and business stakeholders.

- **Mentorpiece:** QA coursework completed in March 2026; certificate earned. The associated base86 internship continued through May 2026.
- **Siberian Federal University:** Diploma of Specialist in Engineering, Industrial Thermal Power Engineering, 2006–2012.
- **Languages:** Russian — native; English — C1.

