# Project Compass 🧭

**Project Compass** is a privacy-first, single-file offline delivery intelligence dashboard designed to aggregate, parse, and analyze multi-channel project notes—such as Slack messages, emails, Jira tickets, meeting transcripts, and call summaries.

## ✨ Key Features

* **100% Client-Side & Offline:** Runs entirely in your browser via React, Tailwind CSS, and Babel (via CDN). No external database, server, or API keys required.
* **Multi-Channel Log Parsing:** Automatically categorizes messy raw inputs by channel prefixes (`SLACK:`, `EMAIL:`, `MEETING:`, `JIRA:`, `DISCORD:`, `CALL:`, etc.).
* **Built-in PII Scrubber:** Automatically detects and masks sensitive data (emails, phone numbers, Turkish TCKN, IBANs, IP addresses, and `@mentions`) locally to ensure privacy compliance.
* **Risk Radar & Action Matrix:** Scans inputs for critical blockers, warnings, and action items, dynamically evaluating project health with a traffic light indicator (Green / Yellow / Red).
* **Export & Data Control:** Allows exporting structured audit reports as JSON or completely wiping local browser storage via the "Nuke All" feature.

## 🚀 How to Use

1. Download or copy the `index.html` file.
2. Open it directly in any modern web browser.
3. Enter your project details and paste your multi-channel notes into the raw text area to instantly view structured delivery insights.
