# File upload for student photos

Add an endpoint to upload profile photos, store images under `static/images/students/` or object storage, and serve them from the static mount. Add validation on file type and size.

**Acceptance criteria**
- `POST /students/{id}/photo` accepts multipart file
- Stores image on disk at `static/images/students/{filename}` and updates student record with URL
- Reject non-image MIME types and excessive file sizes
