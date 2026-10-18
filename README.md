# Donut Client (Fork by SparkyzUsesArch)

Frontend application for managing a donut shop, forked from jun1rox/donut-client and maintained at SparkyzUsesArch/donut-client. Built with React, TypeScript, and Vite, this SPA provides a lightweight dashboard to manage branches, flavors, employees, customers, and purchases for a donut business.


## Features

- Manage Branches (Filiais), Flavors (Sabores), Employees (Funcionários), Customers (Clientes), and Purchases (Compras)
- Create and edit records through modal forms
- List views for browsing data
- Client-side routing with React Router
- SCSS modules for component-scoped styles
- Configured for Netlify with SPA redirect rules


## Tech Stack

- TypeScript (~86% of the codebase)
- SCSS
- React 18
- Vite
- Axios
- React Router


## Repository Structure

```
.
├── index.html
├── netlify.toml
├── package.json
├── package-lock.json
├── tsconfig.json
├── tsconfig.node.json
├── vite.config.ts
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   ├── types/
│   ├── granulado.png
│   ├── index.css
│   ├── index.tsx
│   ├── routes.tsx
│   └── vite-env.d.ts
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 16+ recommended
- npm

### Install

```bash
npm install
```

### Development

```bash
npm run dev
```

Open http://localhost:5173 (or the URL Vite outputs) to view the app.

### Build & Preview

```bash
npm run build
npm run preview
```


## Configuration

The app uses Axios calls to `https://donut-factory.herokuapp.com` for its backend API. If you run a local backend or change the API host, update the endpoints within `src/pages/*` accordingly.

Netlify is supported via `netlify.toml` which contains a redirect to `index.html` so client-side routing works on refresh.


## Notes

- UI labels are in Portuguese.
- This fork preserves the original project's structure and behavior.
- No license is included; add one if you plan to distribute this publicly.


## Contributing

If you'd like to contribute, open an issue or submit a pull request against this fork.


---

README generated and added to SparkyzUsesArch/donut-client.
