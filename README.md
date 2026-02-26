# ⚡ Flux Capacitor

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Flux%20Capacitor-111827?style=for-the-badge&logo=github" alt="Flux Capacitor banner" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

## Overview
Token/time optimizer with pre-run estimation and adaptive cost controls.

## Purpose
Optimizador de compute: predice costo tokens/tiempo antes de ejecutar chains largas, propone shortcuts y pausa si excede presupuesto.

## Installation
```bash
git clone https://github.com/smouj/Flux-Capacitor.git
cd Flux-Capacitor
cat SKILL.md
```

## Architecture (understanding)
```mermaid
flowchart LR
  A[Input] --> B[Validate scope]
  B --> C[Plan safe steps]
  C --> D[Execute]
  D --> E[Verify]
  E --> F[Report]
```

## Status
Initiating

## Difficulty
Media-Alta
