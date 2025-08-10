# PrairieCare Now — Postgres Ready

Run locally:
1) API
   cd apps/api
   npm install
   $env:DATABASE_URL="postgres://..."
   $env:CORS_ORIGIN="http://localhost:3000"
   npm run dev

2) Web
   cd apps/web
   npm install
   npm run dev
   # http://localhost:3000
