# FlowX

**Cross-border payment liquidity optimization platform** for the India ↔ UAE corridor.

## Problem
Cross-border payment providers keep money pre-funded in accounts on both sides of a corridor. Too much idle balance ties up capital, while too little causes failed or delayed payments. Managing these balances across currencies (INR and AED) is usually done manually or with static rules, which leads to inefficient liquidity allocation and higher costs.

## Our Solution
FlowX helps optimize liquidity for cross-border payments, starting with the India ↔ UAE corridor. It analyzes payment flows in both directions, forecasts liquidity needs, and scores routes to recommend how funds should be allocated so payments settle smoothly while idle capital stays low. A dashboard presents these insights visually.

## Key Features
- **Liquidity Forecasting:** predicts upcoming liquidity requirements on the corridor
- **Two-Way Flow Analysis:** analyzes payment flows in both directions (India → UAE and UAE → India)
- **Route Scoring:** ranks payment routes to support better allocation decisions
- **Interactive Dashboard:** charts and visual insights built with Chart.js
- **REST API:** FastAPI backend serving forecasts, scores and analytics

## Tech Stack
| Layer | Technologies |
|---|---|
| Frontend | React.js, JavaScript, HTML/CSS, Chart.js |
| Backend | Python, FastAPI, REST APIs |
| Data & Analytics | Pandas, NumPy, Scikit-learn |
| Database | MySQL |
| Decision Engine | Liquidity Forecasting, Two-Way Flow Analysis, Route Scoring |
| Dev & Version Control | Git, GitHub, VS Code |
| Data | Synthetic / Sandbox Data |

## Project Structure
```
FlowX/
├── frontend/   # UI (components, pages, charts, services, utils)
├── backend/    # API, models, schemas, services, algorithms, database, tests
├── data/       # raw, processed and sample datasets
├── ml/         # preprocessing, models, training, evaluation
├── docs/       # project documentation
└── scripts/    # helper scripts
```

## Team
- Mansvi Mor
- Dhanashri Keskar
