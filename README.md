# F1 Power Unit Programme — Demo Artifact

A worked example of running a **Formula 1 power unit development programme** end to end,
built to show how I'd apply Programme Management in a high-performance motorsport setting.

> **Author:** Viswanadham Ampolu
> **Purpose:** A capability demonstration for **Programme Management (F1)** roles —
> showing how I'd set up governance, manage reliability and cost-cap risk, and keep
> multiple engineering workstreams aligned to the race calendar.

> ⚠️ **Entirely fictional.** The programme, numbers, suppliers and risks are invented
> for demonstration. Nothing here is real or confidential performance data from any
> team. It shows **method**, not secrets.

---

## The sample programme

**Project Apex — 2026 Power Unit Development Programme**
Design, validate and deploy a new F1 power unit compliant with the **2026 technical
and financial regulations** — ~50% electrical power (ERS), 100% sustainable fuel,
delivered within the Power Unit Cost Cap — and reliable enough to complete a full
season inside the permitted element allocation.

| | |
|---|---|
| **Horizon** | 18 months: concept → homologation → race season |
| **Governance** | Monthly PU Steering Board · weekly dyno/reliability review · daily trackside sync in-season |
| **Workstreams** | ICE & Combustion · ERS & Battery · Reliability & Dyno · Cost Cap & FIA Compliance · Trackside Integration |
| **Headline constraints** | FIA homologation deadline · Power Unit Cost Cap · element allocation per driver |

---

## Why this programme is *hard* to manage (and why that's the point)

F1 power unit delivery is a genuine programme-management challenge:

- **Fixed, immovable deadlines** — the race calendar and FIA homologation dates do not move.
- **Competing objectives** — performance vs reliability vs cost cap, all at once.
- **Regulatory gates** — homologation locks the design; you get it right or you race compromised.
- **Scarce shared resources** — dyno hours are the bottleneck everything queues for.
- **Zero-tolerance failure modes** — an unreliable PU means grid penalties that cost championship points.

Managing that is exactly what the artifacts below demonstrate.

---

## What's in here

| Artifact | What it shows | File |
|---|---|---|
| **Programme Charter** | Objectives, scope, constraints, success measures | [docs/charter.md](docs/charter.md) |
| **Roadmap** | Concept → dyno → homologation → testing → race, with gates | [docs/roadmap.md](docs/roadmap.md) |
| **RAID log** | Reliability, cost-cap, supplier & regulatory risk | [docs/raid-log.md](docs/raid-log.md) |
| **Stakeholders & RACI** | Technical Director, FIA, drivers, suppliers, trackside | [docs/stakeholders-raci.md](docs/stakeholders-raci.md) |
| **Status report** | Board-style RAG update against the calendar | [docs/status-report.md](docs/status-report.md) |
| **Governance model** | Cadence, homologation gate, in-season escalation | [docs/governance.md](docs/governance.md) |
| **Dashboard** | One-page visual summary (open in a browser) | [index.html](index.html) |

---

## How to read it

1. Start with the **[Charter](docs/charter.md)** for the objectives and the three hard constraints.
2. Open **[index.html](index.html)** for the one-page dashboard.
3. Read the **[RAID log](docs/raid-log.md)** and **[Status report](docs/status-report.md)** —
   they show how reliability, cost-cap and dyno-capacity pressure get controlled week to week.

### Live dashboard
If published with GitHub Pages (Settings → Pages → `main` / root), the dashboard is live at
`https://<username>.github.io/f1-power-unit-programme/`.

---

_Companion to my general [programme-management-portfolio](https://github.com/viswanadh-ampolu/programme-management-portfolio).
This one applies the same discipline to the motorsport domain. All content illustrative._
