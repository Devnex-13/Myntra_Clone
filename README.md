# Myntra Clone Workspace

This repository contains multiple versions and components of a Myntra clone project, including a legacy static clone, backend APIs, and a React + Vite frontend.

## Workspace structure

- `1-pre-build-bundle/`
  - `node-backend/` – Express backend service that reads and stores item data from `items.json`
  - `old-clone/` – legacy static clone files with HTML, CSS, and client-side scripts
- `2-actual-backend/` – Express API backend for the Myntra clone app
- `3-myntra-clone/` – React + Vite frontend application with Redux, React Router, and Bootstrap

## Recommended setup

1. Install dependencies for each project before running it.
2. Start the backend server first so the frontend can fetch data from the API.
3. Use a modern Node.js version (Node 18+ recommended) for both backend and frontend projects.

## Getting started

### Run the frontend

```bash
cd 3-myntra-clone
npm install
npm run dev
```

### Run the backend

```bash
cd 2-actual-backend
npm install
npm start
```

### Pre-build bundle backend

```bash
cd 1-pre-build-bundle/node-backend
npm install
npm start
```

## Notes

- The frontend is designed to work with the backend API on port `8080`.
- The backend stores item data in `items.json` and exposes simple REST endpoints for listing and creating items.
