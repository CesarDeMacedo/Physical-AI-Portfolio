# Physical AI Portfolio — Codex project instructions

## Mission

Build a Canadian career-transition portfolio from Unreal Engine / cinematic 3D visualization toward Digital Twins, engineering simulation, OpenUSD, NVIDIA Omniverse, Isaac Sim and Physical AI. The professional direction is: WSP (Unreal Engine C++, Digital Twins and engineering simulation), Eclipse Automation (Python, OpenUSD, Omniverse and industrial simulation), and General Robotics (Isaac Sim, ROS 2 and Physical AI).

Use Brazilian Portuguese for collaboration. Use English for production code, identifiers, README files and portfolio-facing copy when appropriate.

## Source of truth

The planning source is `docs/tracker/Unreal_Simulation_Physical_AI_Tracker_v5.9_52_Semanas.html`. Preserve its 52-week sequence and task IDs unless the user explicitly requests a planning change:

- Weeks 1–12: Infrastructure Operations & Training Simulator — Operations Mode.
- Weeks 13–16: Training Mode.
- Weeks 17–34: Python, OpenUSD and Omniverse.
- Weeks 35–52: Isaac Sim, ROS 2 and robotic inspection.

`Simulation_Physical_AI_Tracker_v3.5.html` is historical reference only. Do not treat it as the active roadmap.

The v5.9 update keeps Data Center Operations & Maintenance Simulator as portfolio project #2 after the university-building MVP and Training Mode, not a parallel 52-week deliverable. Outcome-driven services and EPI CDCP are future/optional; NCP-OpenUSD remains the technical certification priority. Python and Unreal C++ remain active; Verse/Scene Graph is monitor-only and Rust is optional.

## First portfolio project

The primary project is a fictional Canadian university building with a mechanical room and three assets: `AHU-01`, `P-201` and `MDB-01`. Operations Mode covers monitoring, synthetic telemetry, events, diagnosis and simulated fault recovery. Training Mode covers equipment familiarization, simulated procedures and assessment.

The project is not a real facility model, live BAS/BMS integration, equipment controller, certified maintenance training, commissioning system, CFD study or electrical-safety validation. Label synthetic readings, assumptions and limitations clearly.

## Working rules

- Before edits, inspect the repository, all applicable `AGENTS.md` files, the active tracker and any Unreal project structure.
- Do not modify an existing Unreal project until its `.uproject`, plugins, source modules, config and current status have been inspected.
- Do not create a large Digital Twin implementation all at once. Prefer short, understandable learning tasks.
- Prioritize genuine C++ learning. Generated code must stay small enough to review line by line.
- Prefer Python for scripting, telemetry, data modeling and tests; use C++ where Unreal integration or learning objectives justify it.
- Keep the weekly commitment near 8–10 hours. The University of Colorado Python course remains light parallel study during Weeks 1–16; current progress is module 2.
- Keep residential-condominium and equipment-manufacturer opportunities as optional future possibilities, not required deliverables.
- Do not expose employer, client, confidential, licensed or proprietary assets in portfolio artifacts.
- Use official documentation when promising version-specific Unreal, NVIDIA, OpenUSD, Omniverse, Isaac Sim or ROS 2 workflows. Record hardware/version assumptions and provide fallbacks when practical.
- Test what can actually be tested. Report exact commands and meaningful outputs; never claim a test ran when it did not.
- Preserve existing data and roadmap decisions. Avoid destructive commands and broad rewrites without explicit approval.

## Documentation layout

Project planning and evidence belong under `docs/projects/university-building-digital-twin/`. Keep scope, telemetry vocabulary, decisions and evidence separate. The root README should remain a concise orientation document; the v5.9 HTML tracker remains the detailed schedule.

## First task on opening the project

Audit the repository and summarize the smallest achievable next task. Do not implement until the user requests implementation. When implementation is requested, make scoped changes, validate them, and explain changed files, tests and limitations.

## Context limitation

This file is curated project context, not live synchronization with other conversations. Ask for an updated tracker or decision note when a required decision is missing.
