# Project 1 — Job Application Management API

## Purpose
A multi-user API that lets a person track job applications. Use fictional data only.

## Minimum features
- Register and log in.
- Hash passwords; never store plain-text passwords.
- Create, read, update and delete a user's own applications.
- Fields: company, role, job_url (optional), location (optional), applied_date, status, notes.
- Status values: saved, applied, interview, offer, rejected, withdrawn.
- Filter by status; paginate results.
- Validate inputs and return sensible HTTP status codes.
- Prevent one user from reading or changing another user's records.

## Suggested tables
- users: id, email (unique), hashed_password, created_at
- applications: id, owner_id (foreign key), company, role, job_url, status, applied_date, notes, created_at, updated_at

## Required engineering
- FastAPI routers separated from business logic.
- Pydantic request/response schemas.
- SQLAlchemy 2 models and sessions.
- Alembic migrations.
- PostgreSQL.
- pytest tests for CRUD, validation, auth and ownership.
- Environment-based configuration; no secrets in Git.
- Docker setup and clear README.

## Suggested API routes
- POST /auth/register
- POST /auth/login
- GET /applications
- POST /applications
- GET /applications/{application_id}
- PATCH /applications/{application_id}
- DELETE /applications/{application_id}
- GET /health

## Acceptance checklist
- [ ] New user can register.
- [ ] Password is hashed.
- [ ] User can log in.
- [ ] User can create and list applications.
- [ ] User cannot access another user's application.
- [ ] Validation errors are understandable.
- [ ] Tests pass.
- [ ] Migrations work from a clean database.
- [ ] README explains setup and API examples.
