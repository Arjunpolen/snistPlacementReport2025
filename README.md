# SNIST Placement Report 2024-25

## Overview
This repository contains an interactive placement report for Sreenidhi Institute of Science and Technology (SNIST), prepared for the Training and Placement Cell. The report is delivered as a single HTML file and can be opened directly in a browser.

## Repository Contents
- `SNIST_Placement_Report_2024_25.html`: Main report file with layout, styling, analytics logic, and charts.
- `index.html`: Default entry page used by static hosts such as Netlify.
- `netlify.toml`: Netlify build configuration (publish from repository root).
- `_redirects`: Netlify redirect rules.
- `README.md`: Project documentation.

## Key Metrics Included in the Report
- Total students placed: `782`
- Departments covered: `9`
- Average CTC: `INR 5.87 LPA`
- Highest package: `INR 27 LPA`
- Students above `10 LPA`: `78`
- Recruiters represented: `60+`

## Technology Stack
- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- Chart.js `4.4.1` (loaded via CDN)
- Google Fonts (Playfair Display, Source Sans 3)

## How to View the Report
Open the file below in any modern browser:

- `SNIST_Placement_Report_2024_25.html`

Example on macOS:

```bash
open SNIST_Placement_Report_2024_25.html
```

## Deploy on Netlify
Use these settings when creating the Netlify site:

- Base directory: *(leave empty)*
- Build command: *(leave empty)*
- Publish directory: `.`

This repository already includes `index.html`, `netlify.toml`, and `_redirects`, so no build step is required.

## Data and Annual Update Guide
The report data is currently embedded in the HTML file. For future academic years, update the following sections in `SNIST_Placement_Report_2024_25.html`:

- KPI values in the hero and KPI strip
- `TOTAL`
- `BUCKETS`
- `depts`
- `avgData`
- `recruiters`
- Key insight summary text

## Operational Notes
- Internet access is required to load external dependencies (Chart.js and Google Fonts) from CDN links.
- If the report must run fully offline, host these dependencies locally and update the asset references.
