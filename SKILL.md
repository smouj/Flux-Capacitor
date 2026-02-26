---
name: flux-capacitor
description: "⚡ Optimización de compute/tokens."
metadata:
  {
    "openclaw": {
      "emoji": "⚡",
      "version": "0.2.0",
      "author": "smouj",
      "lang_default": "en"
    }
  }
---

# ⚡ Flux Capacitor

## Purpose
Optimizador de consumo que estima coste/token antes de ejecutar, aplica caching semántico, truncado inteligente y compresión de contexto para ahorrar 30-60% en workloads recurrentes.

## Tags
- security
- reliability
- automation
- openclaw-skill

## Execution contract
1. Validate request and constraints.
2. Generate minimal safe plan.
3. Execute in reversible steps.
4. Verify with explicit checks.
5. Return concise summary + next actions.

## Inputs expected
- Goal
- Constraints (time/cost/privacy)
- Optional files/URLs

## Outputs
- Plan
- Actions executed
- Verification results
- Rollback notes

## Guardrails
- Never expose secrets.
- No destructive operation without explicit confirmation.
- Fail safe with actionable diagnostics.

## Commands
```bash
# Placeholder entrypoint
printf "flux-capacitor: validate -> execute -> verify\n"
```

## Test checklist
- [ ] Happy path
- [ ] Error handling
- [ ] Idempotency
- [ ] Guardrails respected
