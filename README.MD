# Practica sesion 4 - equipo IngBlckbeast
Repositorio de mi equipo (de manera individual) para prácticas de Git y flujo de trabajo.
---
## Flujo de Trabajo y Convenciones

### Flujo elegido: GitHub Flow
- `main` protegido (solo merges por PR).
- ramas: `feature/<tema-kebab-case>`
- proceso: crear rama → commit/push → PR → review → merge (squash).

### Convención de Commits
- Formato: `<type>(<scope>): <mensaje en imperativo>`
- Ej: `feat(api): añade endpoint /health`
- Tipos: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`.

### Diagrama de Flujo (GitHub Flow)
main ──●──────────●──────────●───────────▶ \ \

\ \ \── PR ── merge \ \── PR ── merge \── PR ── merge feature/* branches