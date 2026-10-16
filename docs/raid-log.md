# RAID Log — Project Apex (2026 Power Unit)

**R**isks · **A**ssumptions · **I**ssues · **D**ependencies.
Scored **Impact × Likelihood** (1–5 each); score ≥ 15 escalates to the PU Steering Board.

_Reviewed weekly at the dyno & reliability review._

## Risks

| ID | Risk | Impact | Likelihood | Score | Owner | Mitigation |
|---|---|:--:|:--:|:--:|---|---|
| R-01 | Reliability target not met before homologation lock → race the season compromised | 5 | 4 | **20** 🔴 | Chief Dyno Engineer | Front-load mileage; parallel single-cylinder + full-PU rigs; weekly gap-to-target tracking; reliability-first design reviews |
| R-02 | Cost-cap pressure forces a performance/spec compromise | 4 | 4 | **16** 🔴 | Cost Cap Lead | Rolling cost forecast vs cap; ring-fenced contingency; decision log for every cap trade-off; board owns cap calls |
| R-03 | Dyno capacity can't serve all workstreams in time | 4 | 4 | **16** 🔴 | Chief Dyno Engineer | Single prioritised dyno schedule owned by PgM; night shifts for critical runs; third-party dyno option costed |
| R-04 | Sustainable-fuel supplier slips on race-ready delivery | 4 | 3 | 12 🟡 | ICE Lead | Milestone contract with supplier; fallback blend qualified; weekly joint review |
| R-05 | Late FIA regulation clarification forces rework near the gate | 5 | 2 | 10 🟡 | Compliance Lead | Keep control strategy configurable; FIA technical liaison; early draft-dossier review |
| R-06 | Battery thermal limits cap ERS deployment at target power | 3 | 3 | 9 🟢 | ERS Lead | Thermal model validated early; cooling redesign spike held in plan |

## Assumptions

| ID | Assumption | Validated? | Owner | If wrong… |
|---|---|:--:|---|---|
| A-01 | Current dyno hours are sufficient for the validation plan | ❌ Open | Dyno Engineer | +6–8 weeks or third-party dyno cost (links R-03) |
| A-02 | Sustainable fuel behaves on full-PU as modelled in the lab | 🟡 Testing | ICE Lead | Recalibrate; may affect M3/M4 |
| A-03 | Homologation accepted on first submission | ❌ Open | Compliance Lead | Resubmission cycle risks the testing window |

## Issues

| ID | Issue (happening now) | Severity | Owner | Action |
|---|---|:--:|---|---|
| I-01 | First-fire on full-PU dyno slipped 2 weeks (sensor harness rework) | High | ICE Lead | Recovery plan agreed; borrowed dyno slot to claw back time |
| I-02 | Cost forecast trending at 99.2% of cap — above 98% target | High | Cost Cap Lead | Two spec options prepared for board; contingency review |
| I-03 | Dyno booking clash between ICE and ERS integration runs | Medium | PgM / Dyno Eng | Single schedule enforced; ERS moved to night shift this week |

## Dependencies

| ID | We need… | From | By | Status |
|---|---|---|---|---|
| D-01 | Race-ready sustainable fuel batch | Fuel supplier | M9 | 🟡 In progress |
| D-02 | Gearbox interface spec freeze | Chassis/Transmission | M7 | 🟢 On track |
| D-03 | FIA confirmation on control-strategy clause | FIA | M8 | 🟡 Awaiting |
| D-04 | Trackside telemetry integration window | Race Team Ops | M14 | ⚪ Not yet booked |

---

### How I use this log
- **Weekly re-score** at the dyno & reliability review; close what's resolved.
- **Three reds right now (R-01/02/03)** all trace to the same squeeze: reliability mileage
  vs cost cap vs dyno capacity. That cluster is the programme's real story — I manage it as
  one connected problem, not three separate flags.
- **Every red goes to the board with a recommended decision**, not just a colour.
