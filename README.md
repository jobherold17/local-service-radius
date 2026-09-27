[README.md](https://github.com/user-attachments/files/32695123/README.md)
# Radius App

A starter monorepo for a location-based services app with an Express + Socket.IO API and a Vite-served frontend.

## Requirements

- Node.js 20 or newer
- npm 10 or newer

## Setup

```sh
npm install
npm install --prefix backend
npm install --prefix frontend
npm run dev
```

The frontend runs at <http://localhost:5173> and proxies `/api` and `/socket.io` to the backend at <http://localhost:3000>.

Set a unique `JWT_SECRET` in `.env` before using authentication outside local development. SQLite is created automatically at the path in `DATABASE_PATH`.
