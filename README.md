# NEXUS SCM — Self-Healing Pharma Cold Chain Recovery Engine

A React + Vite frontend prototype for a pharmaceutical cold-chain supply chain across East Africa.

## Features in this demo
- Executive control tower with simulated KPIs and disruption feed
- East Africa logistics network illustration
- Disruption intelligence, dependency network, scenario planning, recovery optimization
- Logistics, cold-chain monitoring, inventory, AI Agent Center, audit and reports views
- Interactive navigation, search, filters, scenario simulation, recovery approval workflow, and demo disruption injection
- Clearly labelled sample/simulated data

> This is a frontend demonstration only. It does not connect to live SAP systems, GPS devices, temperature sensors, or real AI agents. Approval and recovery actions update local demo state only.

## Requirements
- Node.js 18 or newer
- npm

## Run locally
1. Extract the ZIP.
2. Open a terminal in the `nexus-scm` folder.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the local URL printed by Vite, usually `http://localhost:5173`.

## Build for production
```bash
npm run build
npm run preview
```

## Upload to GitHub using the website
1. Sign in to GitHub and create a new repository named `nexus-scm`.
2. Keep it Public or Private as you prefer. Do not add a README if you are uploading this project with its existing README.
3. On the repository page, choose **Add file → Upload files**.
4. Extract the downloaded ZIP on your computer.
5. Upload the *contents* of the `nexus-scm` folder (including `src`, `package.json`, `index.html`, and `README.md`), not the ZIP file itself.
6. Enter a commit message such as `Add NEXUS SCM frontend prototype`.
7. Click **Commit changes**.

## Upload with Git (optional)
From a terminal opened in the project folder:
```bash
git init
git add .
git commit -m "Add NEXUS SCM frontend prototype"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/nexus-scm.git
git push -u origin main
```
Replace `YOUR-USERNAME` with your GitHub username. If Git asks you to sign in, follow the GitHub authentication prompt.

## Main structure
```text
nexus-scm/
├── index.html
├── package.json
├── README.md
├── .gitignore
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── data.js
    └── styles.css
```

## Next development steps
- Add a backend API (for example, FastAPI) and database.
- Connect real shipment, inventory, and temperature data sources.
- Implement optimization algorithms and auditable decision rules.
- Integrate approved SAP APIs only if access and credentials are available.
