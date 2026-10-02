# Lab 26 — Profile Purposes

| Profile | Purpose |
| --- | --- |
| dev | Local CRM smoke; relaxed logging; H2‑friendly |
| test | Surefire / BootTest isolation |
| prod | Deployed settings; secrets via env; fail fast |

## One risk if prod uses dev YAML
Debug logging, in‑memory DB settings, or relaxed guards could leak internals or break production stability.

## Scope
Pre-lab only.
