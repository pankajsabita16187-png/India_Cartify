# IndiaKartify (Minimal runnable example)

This repository is a compact, runnable **Flipkart-inspired** clone skeleton containing:
- frontend (plain HTML/CSS/JS) in `public/`
- backend (Node.js + Express + MongoDB schema examples) in `backend/`
- uploads/ with sample SVG product images
- seed script to populate sample JSON data
- `.env.example` and README instructions

## Quick start (local)
1. Copy `.env.example` to `.env` and edit if needed.
2. Install dependencies:
   - `npm install`
   - `cd backend && npm install`
3. Start MongoDB locally (or use Docker).
4. Seed example data: `npm run seed`
5. Run app: `npm start`
6. Open http://localhost:4000

This package includes seeded sample products and SVG images for quick testing.

