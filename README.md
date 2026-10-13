# GreenGrade MVP

GreenGrade is a local, rule-based building sustainability prototype. The 200 building records and neighbourhood measurements are fictional demo data; this project is not connected to live government data.

## Requirements

Install Node.js 20 or newer.

## Run locally

Open a terminal in this folder and run:

```bash
npm install
npm run install:all
npm run dev
```

Open http://localhost:5173. The API health check is at http://localhost:3001/api/health.

If you need to run the parts separately, open two terminals:

```bash
cd server
npm install
npm run dev
```

```bash
cd client
npm install
npm run dev
```

## Demo logins

- Citizen: `citizen@greengrade.local` / `demo123`
- Municipal inspector: `inspector@greengrade.local` / `demo123`
- Admin: `admin@greengrade.local` / `demo123`

## Included

- 200 fictional buildings, with residential buildings making up the majority
- 20 fictional neighbourhoods
- Building search and category/area filters
- Building score breakdown and neighbourhood context
- Waste inspection form and audit trail
- Admin electricity and water inputs
- Admin area reference inputs for green cover and AQI
- SQLite persistence and rule-based scoring

## Admin utility inputs

Choose a building, enter annual electricity use in kWh, ground-floor footprint in square metres and number of floors. The app calculates built-up area and EPI, then suggests a reference EPI based on building type. For water, enter monthly litres and an occupancy count/unit; the app calculates daily water use per occupancy unit and compares it with the suggested reference. These suggested values are examples, not official benchmarks, and can be edited.

Saving utility inputs recalculates the building score. Missing or unassessed categories are not treated as perfect scores.

## Important

All sample values and scoring thresholds are for demonstration only. Validate the benchmarks and replace fictional area and building data with verified local data before using the results for real decisions. The demo login is not production-secure. A real deployment needs password hashing, secure sessions, server-side role authorization, backups, input validation and verified data integrations. Do not put real personal or sensitive data in this prototype.
