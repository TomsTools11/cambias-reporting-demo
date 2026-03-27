# Cambias Reporting Demo

A collection of static HTML report pages built for **Cambias Insurance Agency**, demonstrating campaign analysis and performance reporting for an LA Home insurance lead-generation campaign.

## Overview

This repository contains a self-contained reporting suite with four HTML pages — a landing page and three detailed reports. Every page is a standalone file with no external dependencies (all styles are inlined), so the reports can be opened directly in any browser or hosted on any static file server.

## Reports

### Campaign Analysis + Right-Pricing
`cambias-final-campaign-analysis.html` — An internal, multi-section diagnostic covering executive summary, key 30-day metrics, schedule suppression analysis, right-pricing calibration, market positioning, source performance, ad group impact analysis, phased recommendations, monitoring cadence, modifier & targeting audit, and methodology notes.

### Client Performance Dashboard
`cambias-client-dashboard.html` — A client-facing dashboard presenting KPI tracking, lead volume trends, cost metrics, schedule optimization opportunities, audience and device breakdowns, property type targeting, traffic source performance, and recommended actions.

### Internal Volume Growth Roadmap
`cambias-final-internal-roadmap.html` — An internal action plan that diagnoses compounding spend problems, maps a spend waterfall to a $1,000/day target, provides a right-pricing quick reference, visualizes market positioning, lays out a phased implementation plan, and includes a modifier & targeting audit.

### Landing Page
`index.html` — A card-based index page that links to each of the three reports above.

## Tech Stack

- **HTML** — 100% of the codebase
- **CSS** — All styles are inlined within each file (no external stylesheets)
- **No JavaScript** — The reports are purely static markup and CSS
- **No build step** — Open any `.html` file directly in a browser

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/TomsTools11/cambias-reporting-demo.git
   ```
2. Open `index.html` in your browser to view the landing page, or open any individual report file directly.

## Project Structure

```
cambias-reporting-demo/
├── index.html                           # Landing page with report cards
├── cambias-final-campaign-analysis.html  # Internal campaign analysis & right-pricing
├── cambias-client-dashboard.html         # Client-facing performance dashboard
└── cambias-final-internal-roadmap.html   # Internal volume growth roadmap
```

## License

This project does not currently include a license. All rights are reserved by the repository owner.
