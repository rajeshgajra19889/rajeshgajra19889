# Hi, I'm Rajesh

I'm a backend-focused developer building full-stack apps and shipping them live. Two stacks, two deployed projects.

## Projects

### 1. Sakila Store Manager — full-stack, deployed

A video-rental store admin panel, live end to end:

**Live demo:** [sakila-angular.onrender.com](https://sakila-angular.onrender.com) — login **Mike** / **Admin@123**

| Layer       | Tech                                           | Repo |
|-------------|------------------------------------------------|------|
| Frontend    | Angular 22 — standalone, signals, lazy routes  | [sakila-angular](https://github.com/rajeshgajra19889/sakila-angular) |
| Backend     | Node.js 24, Express 5, TypeScript (strict)     | [sales-api](https://github.com/rajeshgajra19889/sales-api) |
| Database    | PostgreSQL, Drizzle ORM                        | (same API repo) |
| Deploy      | Render + Neon, GitHub Actions CI               | — |

JWT auth, full CRUD across 8+ modules, search/sort/pagination everywhere, dashboard analytics, type-shared contract between frontend and backend.

### 2. Expense Tracker — .NET backend

A secure, production-shaped REST API in **ASP.NET Core (.NET 10)** + EF Core + SQL Server:

[ExpenseTracker](https://github.com/rajeshgajra19889/ExpenseTracker)

- JWT auth with rotating refresh tokens + role-based auth (`User`/`Admin`)
- CRUD for expenses, categories, budgets; soft deletes via global query filter
- LINQ reporting: spend by category, monthly trend, budget vs. actual
- API versioning, output caching, Serilog logging, health checks
- Dockerized (API + SQL Server via Compose)

## Skills

- **Backend:** C# / .NET (ASP.NET Core, EF Core), Node.js, Express, REST APIs, JWT + refresh tokens, role-based auth
- **Frontend:** Angular (standalone, signals, lazy loading), TypeScript (strict)
- **Data:** PostgreSQL, Drizzle ORM, SQL Server, SQL, LINQ
- **DevOps:** Git, GitHub Actions (CI), Docker, Docker Compose, cloud deploys (Render, Neon)

## Currently learning

Automated testing (xUnit), deeper SQL (window functions, CTEs), Azure deployments.

### 3. Northwind Admin Panel — full-stack, live

A B2B admin panel over the classic Northwind dataset (830 orders, 10+ modules), deployed end to end:

**Live demo:** https://northwind-app-wjjo.onrender.com

| Layer | Tech | Repo |
|---|---|---|
| Frontend | Angular 22 — standalone, signals, lazy routes | [northwind-app](https://github.com/rajeshgajra19889/northwind-app) |
| Backend | NestJS, TypeORM | [northwind-backend](https://github.com/rajeshgajra19889/northwind-backend) |
| Database | PostgreSQL (Neon, SSL) — auto-seeded from a SQL dump | (in backend repo) |
| Deploy | Render + Neon, GitHub Actions CI | — |

CRUD across customers, products, orders, employees, suppliers, shippers + a dashboard with CSS-only charts, search/sort/pagination on every list, detail pages (supplier products, employee orders, customer orders), and first-boot auto-seeding.

## Contact

LinkedIn: linkedin.com/in/rajesh-gajra-0a5b9620/
