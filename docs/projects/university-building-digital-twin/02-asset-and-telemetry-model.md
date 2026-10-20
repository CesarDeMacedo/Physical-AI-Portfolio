# Asset and telemetry model — initial draft

Use stable IDs so the same concepts can later be represented in Unreal, OpenUSD and Isaac Sim. Values are synthetic unless explicitly marked otherwise.

| Asset ID | Asset | Initial telemetry | Unit / type |
|---|---|---|---|
| `AHU-01` | Air Handling Unit | supply air temperature, return air temperature, airflow, fan state, alarm state | °C, °C, m³/s, enum, enum |
| `P-201` | Chilled Water Circulation Pump | flow, discharge pressure, motor state, vibration, alarm state | L/s, kPa, enum, mm/s, enum |
| `MDB-01` | Main Distribution Board | voltage, current, breaker state, power, alarm state | V, A, enum, kW, enum |

## Shared conventions

- `asset_id`: stable identifier shown above.
- `timestamp`: ISO 8601 timestamp for the simulation clock.
- `quality`: `good`, `suspect` or `unavailable`.
- `mode`: `operations` or `training`.
- `source`: `synthetic_simulation` for the portfolio prototype.
- `alarm_state`: `normal`, `warning` or `fault`.

Do not add a live data schema, protocol or vendor model until the MVP needs it and the assumptions are documented.
