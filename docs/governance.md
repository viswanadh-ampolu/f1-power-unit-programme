# Governance Model — Project Apex (2026 Power Unit)

Governance here has one job: get the right decision made fast enough to protect the
**homologation gate** and the **race calendar**.

## Cadence

| Forum | Frequency | Who | Purpose | Output |
|---|---|---|---|---|
| **PU Steering Board** | Monthly | Tech Director, PgM, Cost Cap Lead, workstream leads | Cost-cap calls, reds, homologation readiness, go/no-go | Decisions log, approved board pack |
| **Dyno & Reliability review** | Weekly | PgM, Dyno Eng, ICE, ERS, Reliability | Dyno schedule, mileage vs target, failure analysis | Updated RAID, dyno plan |
| **Cost-cap review** | Weekly | PgM, Cost Cap Lead | Spend vs cap, forecast, trade-offs | Rolling forecast |
| **Trackside sync** (in-season) | Daily | PgM, Race Ops, duty engineers | Element allocation, deployment, issues | Action list |

## The homologation gate (the one that matters)

Homologation **locks the design for the season** — so the gate is strict. It asks:

1. **Reliability** — has the PU banked the validated mileage target with no open critical failures?
2. **Performance** — is it at or above the performance target on validated runs?
3. **Compliance** — is the dossier complete and the fuel race-ready?
4. **Cost** — is the programme inside the cost cap with the dossier audit-ready?

A "no" on reliability is a **stop** — racing an unvalidated PU trades championship points
for grid penalties later. Better to escalate early than discover it at the gate.

## Escalation path

```
Issue at bench/dyno level
      │  resolved in < 24h?  ── yes ──▶ log & move on
      │ no
      ▼
Workstream lead ── affects dyno plan or another stream? ──▶ Dyno & reliability review (weekly)
      │ no / urgent
      ▼
Programme Manager ── cost-cap / reliability / homologation risk? ──▶ PU Steering Board
      │ time-critical to the gate or the calendar
      ▼
Technical Director (out-of-cycle decision)
```

## Reporting principles
- **One source of truth:** roadmap + RAID + cost forecast are master; board packs derive from them.
- **One dyno schedule:** capacity is the bottleneck, so the PgM owns a single prioritised plan.
- **RAG with reasons:** red comes with the recovery plan and the decision needed — never a bare colour.
- **No surprises at the gate:** reliability trend is visible weekly, so the gate confirms what's already known.
- **Decisions, not updates:** every red reaches the board with a recommended option.
