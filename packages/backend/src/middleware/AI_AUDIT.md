## Auth manual-only proof

### Files

1. src/routes/auth.js
- Hand-written: YES
- Purpose: Handles signup and login endpoints using bcrypt and JWT.

2. src/middleware/requireAuth.js
- Hand-written: YES
- Purpose: Verifies JWT access tokens and protects private routes.

3. src/middleware/requireRole.js
- Hand-written: YES
- Purpose: Restricts route access based on user role.

4. server/index.js
- Hand-written auth changes: YES
- Purpose: Mounts auth routes and applies auth middleware to leads routes.

### Manual-only checklist

- [x] Typed all auth code manually
- [x] Did not paste AI-generated auth code directly
- [x] Reviewed every line personally
- [x] Tested signup flow manually
- [x] Tested login flow manually
- [x] Tested protected routes manually