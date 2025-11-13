# Security hardening: password hashing, input validation, CSRF, file checks

Ensure secure password storage, validate and sanitize all inputs, add CSRF protections where applicable, and enforce strict checks on uploaded files.

**Acceptance criteria**
- Passwords hashed with bcrypt/argon2
- Input validation for all endpoints
- CSRF protections for server-rendered forms
- File upload validation (type, size) and safe storage
