# Implement role-based access control (Admin / Faculty / Student)

Add a `role` field to the user model and enforce RBAC in endpoints. Admins can create/edit/delete students and activities; Faculty can view/modify assigned students; Students can view and manage their own enrollments.

**Acceptance criteria**
- `role` enum on user model
- Dependency in FastAPI to check roles on endpoints
- Tests or manual steps documenting role behavior
