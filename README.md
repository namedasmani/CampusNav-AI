# CampusNav AI — Ask. Navigate. Arrive.

Campus navigation and facility finder: ask in natural language (English, Tamil or Tanglish), get step-by-step walking directions on an interactive campus map.

## Run locally

You need Node.js 20+ (or Bun). From the folder where you unzipped this project:

```sh
npm install
npm run dev
```

Then open http://localhost:5173 (the port is printed in the terminal).

Other useful commands:

```sh
npm run build      # production build
npm run preview    # serve the production build locally
npm run test       # run unit tests
```

Note: the campus map, buildings and routes are sample data defined in `src/data/campus.ts`.

## Built with

- TanStack Start (React 19, TypeScript)
- Tailwind CSS v4
- Vite

