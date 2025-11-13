# Add user accounts and authentication (JWT)

Implement user registration and login with secure password hashing (bcrypt). Add JWT-based auth for the API (FastAPI OAuth2 password flow). Store users in the DB and return tokens for authenticated requests.

**Acceptance criteria**
- User model with hashed passwords
- `/auth/register` and `/auth/token` endpoints
- Protected endpoints require Bearer token
- README notes on how to create an initial admin user
