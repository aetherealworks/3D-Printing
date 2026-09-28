# Siraya Tech Roamr TPU Air HR

**[Æthereal Works - 3D-printing resources](../../)**

Standalone Bambu Studio filament profiles for **[Siraya Tech Roamr TPU Air HR](https://siraya.tech/products/roamr-tpu-air-hr-85a-filament)** on a **Bambu Lab H2C** with a **0.6 mm nozzle**.

Ten profiles, no inheritance (`inherits` is empty). Pick a speed tier, then a Shore estimate.

Profile files: [`h2c-0.6-nozzle/`](h2c-0.6-nozzle/)

## Example project

Download this Bambu Studio **85A test project** (`.3mf`) and open it in Studio:

- [Siraya Tech - Roamer TPU Air HR 85a.3mf](h2c-0.6-nozzle/examples/Siraya%20Tech%20-%20Roamer%20TPU%20Air%20HR%2085a.3mf)

## Speed tiers

Two volumetric-flow (VFR) caps. Approximate linear speed is for **0.62 mm line width × 0.3 mm layer height**.

| Tier | Max volumetric | Approx. speed at 0.62×0.3 | Feel |
| --- | --- | --- | --- |
| Quality / firm | 3.2 mm³/s | ~17 mm/s | Firmer |
| Faster / softer | 9.3 mm³/s | ~50 mm/s | Softer (more foaming) |

## Shore, temperature, and flow

Same Shore set on both tiers. Higher nozzle temp increases foaming and lowers the flow ratio.

| Shore (estimate) | Nozzle | Flow ratio |
| --- | --- | --- |
| 85A | 230°C | 0.98 |
| 78A | 240°C | 0.88 |
| 72A | 250°C | 0.68 |
| 70A | 260°C | 0.58 |
| 68A | 270°C | 0.50 |

## Notes

- Siraya recommends roughly **30–60 mm/s**. They do not publish a volumetric flow rate. **3.2 mm³/s** came from an older Bambu TPU base and is kept here as the firmer, slower tier.
- The same Shore print **softer at 9.3 VFR than at 3.2** because of extra foaming / less dwell in the melt zone.
- Tuned around **0.62 mm line width × 0.3 mm layer height**.
- File names use `mm-s`, not `mm/s`, so the paths are valid on Windows.

Each preset is a `.json` + `.info` pair. Install both; see the [repo README](../../README.md#how-to-install-bambu-studio) for drop-in and import steps.

[← Filament index](../)
