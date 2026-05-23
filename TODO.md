# Task: Fix MongoDB warnings and CORS errors in backend

## Steps:
1. [x] Edit backend/config/db.js: Remove deprecated MongoDB options (useNewUrlParser, useUnifiedTopology).
2. [x] Edit backend/app.js: Add logging to corsOrigin and allow localhost:* origins in development.
3. [ ] Restart backend server: cd backend && Ctrl+C to stop current, then npm start
4. [ ] Verify: No Mongo warnings, no CORS errors (check logs for [CORS] messages), frontend connects.

All code fixes complete.
