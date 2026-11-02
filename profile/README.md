<div align="center">

# TRUSCOR

**Where intelligence meets accountability.**

The independent record of how far autonomous AI can be trusted.

[truscor.org](https://truscor.org) · [SOVA OSS](https://github.com/TRUSCOR/SOVA-OSS)

</div>

---

TRUSCOR builds no models, no agents and no applications. We test what AI systems do, record it as signed evidence, and rate how far they can be trusted.

CIBIL scores borrowers and never lends a rupee, which is why every bank trusts it. **We are the bureau, not the bank.**

## The SOVA stack

| | What it does | Access |
|---|---|---|
| **[SOVA OSS](https://github.com/TRUSCOR/SOVA-OSS)** | Free toolkit to map, test, record, replay and investigate AI agents | Open source · Apache-2.0 |
| **.sova format** | A signed, tamper-evident record of what an AI was shown, what it did and what changed | Open |
| **[SOVA Engine](https://github.com/TRUSCOR/SOVA-Engine)** | Attacks, UI-tests and stress-tests AI products and writes `.sova` evidence | Rating team and licensed security firms |
| **[SOVA Black Box](https://github.com/TRUSCOR/SOVA-Blackbox)** | A 24x7 recorder for AI in production, signed and checked against effect | Production deployments and OEM partners |
| **[O.W.L](https://github.com/TRUSCOR/O.W.L)** | The measurement instrument: checks what an AI claimed against what really happened | SOVA Engine, Black Box and licensed measurers |
| **[TAFAAR](https://github.com/TRUSCOR/TAFAAR)** | Grades evidence into the TRUSCOR Rating (300–900) and an Estimated Financial Exposure | TRUSCOR only, never licensed |

## Try it in one minute

No model, API key or network needed:

```bash
git clone https://github.com/TRUSCOR/SOVA-OSS
cd SOVA-OSS
uv sync --locked
uv run sova demo sleeper
```

## How we stay neutral

- No product in any category we rate
- No referral economics
- No certification today
- No insurance on our balance sheet

## Contribute

SOVA OSS is open to contributions: start with the issues at [TRUSCOR/SOVA-OSS](https://github.com/TRUSCOR/SOVA-OSS).
