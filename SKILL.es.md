---
name: Flux Capacitor
description: "⚡ Token/time optimizer with pre-run estimation and adaptive cost controls."
when: "When a user request matches flux-capacitor capabilities or requires this domain-specific workflow."
examples:
  - "Run Flux Capacitor for this task"
  - "Apply Flux Capacitor to solve this workflow"
metadata:
  openclaw:
    requires: ["fs_read", "fs_write", "shell_exec", "memory_search"]
  safety_level: high
  version: "1.0.0"
  author: "smouj"
  tags: ["flux-capacitor", "automation", "openclaw-skill"]
---

# ⚡ Flux Capacitor

## Propósito
Optimizador de compute: predice costo tokens/tiempo antes de ejecutar chains largas, propone shortcuts y pausa si excede presupuesto.

## Cómo usar / Instrucciones núcleo
1. Primero piensa en alcance, riesgo y coste.
2. Luego valida inputs y dependencias mínimas.
3. Ejecuta en pasos pequeños y reversibles.
4. Verifica resultado con checks explícitos.
5. Si hay error, falla seguro y reporta causa + próximo paso.

## Security & Safety Guidelines
Nunca ejecutes código sospechoso sin sandbox. Reporta riesgos al usuario. No envíes datos sensibles fuera del entorno local.

## Herramientas requeridas
- fs_read
- fs_write
- shell_exec
- memory_search

## Flujos de ejemplo
- Entrada -> validación -> plan -> ejecución -> verificación -> reporte.
- Reintento controlado con rollback si falla.

## Casos límite y manejo de errores
- Input incompleto: pedir datos mínimos.
- Dependencia ausente: degradar en modo seguro.
- Error persistente: detener, registrar y escalar.
