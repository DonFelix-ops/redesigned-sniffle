# Specialist Absence Revenue Impact Calculator

A browser-based financial risk tool for **HR Managers and Finance Directors** in healthcare settings. Quantifies the true revenue cost when a specialist goes on leave, extended absence, or resigns — turning an HR scheduling problem into a financial risk model.

---

## What It Does

Fill in a few inputs and instantly get:

- **Total financial exposure** with a risk rating (Low / Medium / High / Critical)
- **Gross revenue at risk** — OPD consultations lost + procedures lost + indirect downstream loss
- **Locum cost modelling** — offset revenue recovery based on locum efficiency
- **Resignation scenario** — adds recruitment cost, time-to-replace gap, and ramp-up productivity loss
- **Visual cost breakdown** — bar chart showing each cost component
- **Tailored recommendations** — flags if no locum is engaged, whether board escalation is warranted, and more

---

## How to Use

1. Download `specialist_absence_revenue_calculator.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. No installation, no server, no login required

---

## Inputs

| Input | Description |
|---|---|
| Specialist name & specialty | For report labelling |
| Absence type | Annual leave / Sick leave / Unpaid / Resignation |
| Working days absent | Excludes weekends and public holidays |
| OPD consultations per day | Average daily outpatient volume |
| Revenue per consultation | Fee per OPD visit |
| Procedures per day | Surgeries, interventions, etc. |
| Revenue per procedure | Average procedure fee |
| Indirect revenue loss % | Referral diversion, downstream service loss |
| Locum engaged? | Toggle on to add locum rate and efficiency % |
| Resignation fields | Recruitment cost, weeks to replace, ramp-up productivity |

---

## Who It Is For

- **HR Managers** — to build a financial case when approving or planning leave
- **Finance Directors** — to quantify risk before it hits the P&L
- **Hospital Administrators** — to support specialist succession planning and locum budgeting

---

## Tech Stack

- Pure HTML + CSS + JavaScript (single file, no framework)
- [Chart.js](https://www.chartjs.org/) via CDN for the bar chart
- Works offline once loaded

---

## Live Demo

Open `specialist_absence_revenue_calculator.html` directly in your browser — no build step required.

---

## License

MIT — free to use and adapt for any healthcare facility.
