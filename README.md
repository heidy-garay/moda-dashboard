# Moda Dashboard — Refresh Repo

Este repo guarda `dashboard.html`, el dashboard de categoría Moda (marketplace Addi) construido como un Artifact de Claude autocontenido (HTML + JS embebido, sin dependencias externas).

Una rutina programada (Claude Code en la nube, de lunes a viernes) actualiza `dashboard.html` cada mañana con datos al día hábil anterior, y hace commit + push de los cambios a este repo.

**Importante: la rutina NO publica el Artifact en vivo.** Solo deja el HTML actualizado commiteado aquí. Publicar la nueva versión en `https://claude.ai/artifact/UZZ7gpLjezLtHSn1g18zgE` es un paso manual: alguien (Heidy, o una sesión local de Claude Code) debe tomar `dashboard.html` de este repo y republicarlo con la herramienta Artifact.

## Flujo manual de publicación

1. Clonar o hacer pull de este repo.
2. Pedirle a Claude Code (sesión local, con acceso a la herramienta Artifact) que lea `dashboard.html` y lo publique a la URL del Artifact existente.
