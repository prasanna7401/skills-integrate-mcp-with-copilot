# Migrate to SQLModel/SQLAlchemy + add migrations

Replace simple in-memory dicts with SQLModel/SQLAlchemy models, add Alembic migrations, and update code to use DB sessions and transactions.

**Acceptance criteria**
- SQLModel models in `src/models.py`
- Alembic config and initial migration
- DB session dependency used across endpoints
