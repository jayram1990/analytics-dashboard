# Analytics Dashboard

A self-contained single-page analytics dashboard built with React 18, Chart.js 4, and Tailwind CSS — all via CDN. No build step required.

## Features

### User Analytics View
- KPI cards: total users, active users, churn rate, avg session time
- Monthly signups trend chart
- Active users by day of week
- Device breakdown donut chart
- Users by region donut chart
- Users by industry and solution area horizontal bar charts
- Filterable user table with search, status tabs, and pagination

### Market Analytics View
- Market size KPIs: 2025 actuals, 2030 forecast, historic CAGR, forecast CAGR
- Historic (2019–2025) vs forecast (2026–2030) revenue trend chart
- Revenue by type: Cloud / License / Maintenance stacked bar
- Regional market share donut chart
- Market size by industry and solution area
- Full data table with per-year values and CAGR per solution area

### Filters (both views)
- Solution Area → Sub-Solution Area (cascading)
- Industry
- Region
- Revenue Type (Market Analytics only)

### Chatbot Assistant
- Data Query tab: answers natural language questions about the currently visible data
- Feedback tab: star rating + category + message form

## Usage

Open `index.html` directly in any modern browser — no server needed.

## Tech Stack

- React 18 (UMD CDN)
- Chart.js 4 (UMD CDN)
- Tailwind CSS (Play CDN)
- Babel Standalone (JSX transpilation)
