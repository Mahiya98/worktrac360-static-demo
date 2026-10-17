# WorkTrac360 — Static Demo

A fully static local version of WorkTrac360. There is **no login, no server API,
and no database**.

- The app opens directly on the dashboard as the demo Super Admin
- All users, roles, dictionary entries, tasks and notifications are generated in
  the browser on first load
- Data is kept in `localStorage` under `worktrac360_static_v1` (browser only)
- `server.js` is a simple static file server — it serves `public/` and nothing else

## Run

```bash
npm start
```

Open http://localhost:3100
