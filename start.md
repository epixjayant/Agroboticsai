# AgroboticsAI Platform

Welcome to the AgroboticsAI Platform. This is a full-stack, AI-powered agricultural intelligence application equipped with **Google Earth Engine** tracking and machine-vision crop analysis natively.

## 🚀 Local Quick-Start Guide

To start the whole application, you need to run the two individual sub-systems in two separate terminal windows/panes concurrently.

### 1. Database & Backend API `(Port: 4000)`

The Express.js robustly manages user architecture and Google Cloud integrations.

```bash
cd backend
npm install
npx prisma generate
npx prisma db push
npm run dev
```

_Creates a local SQLite file (`dev.db`). It intercepts requests cleanly at `http://localhost:4000`._

### 2. Next.js Frontend `(Port: 3000)`

The presentation interface securely rendering dynamic graphs and React-Leaflet maps.

```bash
cd frontend
npm install
npm run dev
```

_Application heavily bounds to `http://localhost:3000` locally._

---
