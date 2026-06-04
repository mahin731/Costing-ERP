# SignERP v2 — Professional Soft Signage ERP

A zero-dependency, single-file ERP tool built for soft signage and LED sign fabrication businesses. Runs entirely in the browser — no server, no installation, no backend.

---

## What It Does

SignERP v2 helps signage fabricators estimate job costs accurately and manage their material masters — all from one HTML file.

### Estimation Engine
- Step-by-step estimator covering sign type, dimensions, profile selection, LED configuration, printing, and accessories
- Supports four sign categories: **Backlit SEG Indoor**, **Backlit Outdoor (Non-SEG)**, **Outdoor Illuminated**, and **Non-Lit**
- Auto-calculates LED module/bar count, driver requirements, sheet material consumption, print area, and frame cuts
- Generates a detailed **Cost Sheet** with per-item breakdown and a visual layout preview (SVG)
- Estimate history with job reference tracking

### Masters Management
Manage your full material library across six categories:
| Module | What It Covers |
|---|---|
| Profiles | Aluminium frame profiles (width, depth, stock length, cost/metre) |
| LED Modules | SMD/LGP modules (dimensions, wattage, IP rating, cost/module) |
| LED Bars | Rigid LED bars (length, wattage, IP rating, cost/bar) |
| Drivers | LED drivers (wattage, IP rating, cost) |
| Sheet Materials | Acrylic/Dibond sheets (size, thickness, cost/sheet, wastage %) |
| Printing Media | Flex, fabric, vinyl (cost/sq.ft, wastage %) |

### Dashboard & Reports
- Live KPI metrics: total estimates, average job value, most-used materials
- Filterable estimate history
- Printable cost sheet per job

---

## Tech Stack

- Pure **HTML + CSS + Vanilla JS** — no frameworks, no build step
- [Tabler Icons](https://tabler-icons.io/) via CDN (only external dependency)
- Light/dark mode via `prefers-color-scheme`
- All data stored in-memory (session-based); no localStorage or backend calls

---

## Usage

```bash
# Just open it
open SignERP_v2.html
```

Or host it on GitHub Pages — no configuration needed.

---

## 🔗 Live Demo
[Open SignERP v2](https://mahin731.github.io/Costing-ERP/SignERP_v2.html)

---

## Roadmap / Possible Extensions

- [ ] LocalStorage persistence for masters and estimate history
- [ ] Export cost sheet to PDF
- [ ] Multi-currency support
- [ ] CSV import/export for material masters
- [ ] Client and supplier contact management

---

## License

MIT — free to use, modify, and distribute.
