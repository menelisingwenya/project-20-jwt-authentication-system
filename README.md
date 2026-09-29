# Project 20: JWT Authentication System

**Emganwini Nedbank Hub | Master Project Portfolio**  
*Phase 2: Backend Development*

---

## 📌 Deliverable Overview
- **Routes File**: [`../backend/src/routes/auth.js`](../backend/src/routes/auth.js)
- **Middleware File**: [`../backend/src/middleware/auth.js`](../backend/src/middleware/auth.js)
- **Controller File**: [`../backend/src/controllers/authController.js`](../backend/src/controllers/authController.js)
- **Security Features**:
  - `bcrypt` password hashing with 10 salt rounds
  - Cryptographic HMAC-SHA256 token signing
  - 24-hour expiration lifecycle
  - Role-based authorization middleware (`CLIENT`, `ADVISOR`, `ADMIN`)
