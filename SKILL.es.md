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

## Propósito
Optimizador de consumo que estima coste/token antes de ejecutar, aplica caching semántico, truncado inteligente y compresión de contexto para ahorrar 30-60% en workloads recurrentes.

## Tags
- security
- reliability
- automation
- openclaw-skill

## Contrato de ejecución
1. Validar solicitud y restricciones.
2. Generar plan mínimo seguro.
3. Ejecutar en pasos reversibles.
4. Verificar con checks explícitos.
5. Resumir resultado + siguientes acciones.

## Inputs esperados
- Objetivo
- Restricciones (tiempo/coste/privacidad)
- Archivos/URLs opcionales

## Outputs
- Plan
- Acciones ejecutadas
- Verificación
- Notas de rollback

## Guardrails
- Nunca exponer secretos.
- Sin acciones destructivas sin confirmación explícita.
- Fallar de forma segura con diagnóstico accionable.

## Comandos
```bash
printf "flux-capacitor: validar -> ejecutar -> verificar\n"
```

## Checklist de test
- [ ] Happy path
- [ ] Manejo de errores
- [ ] Idempotencia
- [ ] Guardrails respetados
