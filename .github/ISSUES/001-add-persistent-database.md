# Add persistent database (SQLite -> Postgres/MySQL)

Replace the in-memory store with a persistent relational database. Start with SQLite for development and add SQLAlchemy/SQLModel models for Activities, Students, Signups, and Users. Add Alembic migrations and a simple seed script to populate example activities.

**Acceptance criteria**
- Add SQLModel/SQLAlchemy models for Activities, Students, Signups, Users
- Add Alembic migrations and a `scripts/seed.py` that inserts example activities
- Update `src/app.py` to use the database instead of the in-memory dict
- Tests or manual verification steps in README
