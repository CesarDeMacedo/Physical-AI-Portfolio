# Unreal Simulation & Physical AI Portfolio

A 52-week learning and portfolio roadmap, from Unreal Engine C++ and infrastructure simulation to Python, OpenUSD, Omniverse, Isaac Sim and ROS 2.

**[Open the tracker](https://cesardemacedo.github.io/Physical-AI-Portfolio/)** · [Edit on GitHub](https://github.com/CesarDeMacedo/Physical-AI-Portfolio/edit/main/docs/tracker/Unreal_Simulation_Physical_AI_Tracker_v5.5_52_Semanas.html)

## Active roadmap

[Tracker v5.5](docs/tracker/Unreal_Simulation_Physical_AI_Tracker_v5.5_52_Semanas.html) covers October 12, 2026 to October 10, 2027, with approximately 8–10 hours per week.

- Weeks 1–12: Operations Mode and WSP case study.
- Weeks 13–16: Operator Training, including one 10–15 minute mission.
- Weeks 17–34: Python, OpenUSD and Omniverse.
- Weeks 35–52: Isaac Sim, ROS 2 and robotic inspection.

WSP applications proceed in parallel. The University of Colorado Python course remains light parallel study during weeks 1–16.

## Infrastructure Operations & Training Simulator

A local Windows application set in a fictional Canadian university building, with AHU-01, P-201 and MDB-01.

- **Asset Explorer:** navigation, asset selection, metadata and synthetic readings.
- **Fault Simulation:** a simulated pump fault, reduced chilled-water flow, AHU cooling impact, alarms, diagnosis and recovery.
- **Operator Training:** objectives, inspection, decisions, score, feedback and a local report.

Read the [scope](docs/projects/university-building-digital-twin/01-scope-v1.md), [telemetry vocabulary](docs/projects/university-building-digital-twin/02-asset-and-telemetry-model.md) and [architecture proposal](docs/projects/university-building-digital-twin/03-v5.5-architecture-decision.md).

All operational data and procedures are demonstrative. This is not a live equipment controller, certified training system, commissioning tool or engineering safety validation. SaaS, multiplayer and Pixel Streaming are outside the MVP.

## Updating the plan

Edit the active HTML through GitHub's pencil button and commit to main, or update it locally:

```sh
git pull --ff-only
# Edit and review the intended files.
git diff
git add docs/tracker/Unreal_Simulation_Physical_AI_Tracker_v5.5_52_Semanas.html
git commit -m "Update learning roadmap"
git push
```

GitHub Pages publishes main → /docs. Updates may take a few minutes. See the [official publishing guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

Checkbox progress is saved in the current browser, not in GitHub. Export progress JSON from the old local tracker and import it into the online tracker to transfer existing checkmarks. Export/import also provides a backup and transfers progress between devices. Keep those personal exports out of Git.

## Repository boundaries

This repository contains the current roadmap and selected planning documents. Historical trackers and machine-specific setup notes remain local and are excluded by .gitignore. The Unreal project is maintained separately; licensed assets and generated Unreal files are not included here.
