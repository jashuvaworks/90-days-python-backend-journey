# 90-Day Python Backend Roadmap

**Day 1:** 19 November 2026  
**Day 90:** 16 February 2027  
**Daily target:** 5 focused hours. This is a target, not a reason to sacrifice sleep.

## Rules
- One stack only: Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic, pytest, Git, Docker.
- Learn a small concept, practise it, use it, explain it.
- No tutorial copying. You may consult docs, but close the example and recreate it.
- Commit meaningful work regularly.
- Begin job research in Week 3 and applications as soon as you have a credible project foundation.

## Phase 1 — Python and SQL foundations (Days 1–14)
**Learn:** variables, types, input/output, operators, conditionals, loops, functions, strings, lists, tuples, sets, dictionaries, basic exceptions, basic files; SQL SELECT, WHERE, ORDER BY, INSERT, UPDATE, DELETE.

**Deliverables:** 20–30 small Python exercises; 20 SQL queries; a command-line expense or contact manager.

**Gate:** independently write a program using functions, collections, input and validation; explain basic SQL CRUD.

## Phase 2 — Python programming and problem solving (Days 15–28)
**Learn:** modules, imports, virtual environments, pip, exceptions, file handling, OOP basics, comprehensions, basic debugging, Git basics, SQL joins, grouping, primary/foreign keys, HTTP request/response, JSON, status codes.

**Deliverables:** a small multi-file Python application; SQL practice file; explain GET/POST/PUT/PATCH/DELETE and common status codes.

**Gate:** build a small program split into modules; write SQL joins without copying.

## Phase 3 — FastAPI and REST APIs (Days 29–42)
**Learn:** FastAPI app, routes, path/query parameters, request bodies, Pydantic schemas, response models, status codes, validation, error handling, OpenAPI docs, routers, dependency injection basics.

**Deliverables:** first working API with in-memory data, then persist data if ready; test endpoints using Swagger UI or an API client.

**Job-search action:** prepare a one-page draft resume and identify 20 eligible internships/trainee/junior roles. Start applying when you can explain your first API honestly.

**Gate:** create CRUD endpoints and explain request → validation → route → response.

## Phase 4 — PostgreSQL and SQLAlchemy (Days 43–56)
**Learn:** PostgreSQL setup, tables, constraints, relationships, joins, indexes basics, SQLAlchemy 2 models and sessions, CRUD, Alembic migrations, transactions and rollback.

**Deliverables:** Project 1 backed by PostgreSQL; migrations; documented schema; tests for important CRUD paths.

**Gate:** explain your database relationships and demonstrate a migration and transaction.

## Phase 5 — Professional backend engineering (Days 57–70)
**Learn:** password hashing, authentication vs authorization, JWT concepts, protected routes, ownership checks, configuration/environment variables, pytest, API tests, fixtures, logging, CORS basics, Docker and Docker Compose basics, safe error handling.

**Deliverables:** authentication and authorization in Project 1; tests; Docker setup; clean README and setup instructions.

**Gate:** a second user cannot access another user's private records; tests pass; app can start from documented instructions.

## Phase 6 — Project 2 and production fundamentals (Days 71–77)
**Build:** Inventory and Order Management API. Products, stock, customers, orders, order items, stock validation, transaction-safe order creation, order status and history.

**Deliverables:** working core flows, tests for insufficient stock and failed order transactions, API docs.

**Gate:** explain what happens when an order fails halfway through and how the database remains consistent.

## Phase 7 — Deployment, portfolio and job search (Days 78–90)
**Do:** deploy at least one project; finish both READMEs; add architecture diagram or clear architecture explanation; clean GitHub; resume; LinkedIn; mock interviews; Python/SQL/backend revision; targeted applications and follow-ups.

**Deliverables:** two presentable repositories, one deployed API (ideally both), application tracker, interview notes, resume.

**Gate:** demonstrate a live API or reproducible local setup; explain design decisions, trade-offs, bugs and tests.

---

## Weekly breakdown

| Week | Days | Main outcome |
|---|---:|---|
| 1 | 1–7 | Python basics, types, input/output, operators |
| 2 | 8–14 | Conditions, loops, functions, collections, basic SQL |
| 3 | 15–21 | Modules, exceptions, files, OOP introduction |
| 4 | 22–28 | OOP practice, SQL joins, HTTP, Git |
| 5 | 29–35 | FastAPI routes, parameters, request/response |
| 6 | 36–42 | Pydantic, CRUD, validation, API docs |
| 7 | 43–49 | PostgreSQL schema, SQLAlchemy models/sessions |
| 8 | 50–56 | Relationships, CRUD persistence, Alembic, transactions |
| 9 | 57–63 | Password hashing, authentication, authorization |
| 10 | 64–70 | pytest, API testing, logging, Docker |
| 11 | 71–77 | Inventory/order project and business rules |
| 12 | 78–84 | Deployment, documentation, resume, mock interviews |
| 13 | 85–90 | Applications, interview practice, portfolio polish |

## Weekly review questions
1. What can I now do without help?
2. What did I build that runs?
3. Which bugs did I diagnose and fix?
4. What can I not yet explain?
5. What is the next week's most important deliverable?
6. How many focused hours did I actually complete?
