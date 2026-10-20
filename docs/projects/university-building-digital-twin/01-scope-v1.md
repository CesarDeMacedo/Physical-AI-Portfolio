# Infrastructure Operations & Training Simulator — Scope v1

**Status:** draft for Week 01 review

**Scenario:** fictional Canadian university building; synthetic and non-operational

## Intended audience

Portfolio reviewers and technical interviewers evaluating Unreal Engine C++, simulation thinking, digital-twin information modeling, diagnostics and training-oriented interaction.

## Initial views / screens

1. Building overview and current operating state.
2. Mechanical room overview with selectable assets.
3. Asset detail view for AHU-01, P-201 or MDB-01.
4. Operations event and diagnostic timeline.
5. Training scenario, instructions and assessment result.

## Assets

- `AHU-01` — Air Handling Unit.
- `P-201` — Chilled Water Circulation Pump.
- `MDB-01` — Main Distribution Board.

## MVP boundaries

Operations Mode covers simulated monitoring, telemetry, events, diagnosis and failure recovery. Training Mode covers familiarization, simulated procedures and assessment. There are no real equipment commands, live BAS/BMS connections, certified procedures, CFD claims, electrical safety validation or commissioning workflows.

Operations Mode combines Asset Explorer and Fault Simulation. Operator Training adds one 10–15 minute mission during weeks 13–16, with objectives, inspection, diagnosis, decisions, score, feedback and a local report. Operations Mode and the WSP case study are due by week 12; applications proceed in parallel.

The MVP is a local Windows single-player application. SaaS, multiplayer and Pixel Streaming are excluded. B2B commercialization is considered only after a functional demonstration and demand validation.

## Limitations to preserve

1. The readings and failures are synthetic and demonstrate software behavior, not validated building performance.
2. A visualization of equipment and a simulation of operational logic do not establish real engineering safety or maintenance authorization.
