# Myntra Clone Backend

This folder contains the Express backend API for the Myntra clone application.

## Install

```bash
cd 2-actual-backend
npm install
```

## Run

```bash
npm start
```

## API Endpoints

- `GET /items` – returns all stored items
- `GET /items/:id` – returns a single item by ID
- `POST /items` – adds a new item to storage

## Notes

- The backend listens on port `8080`.
- Data is stored in `items.json`.
- CORS is enabled for all origins.
