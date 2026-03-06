# Sherlock-docs — Sitio de Documentacion

Sitio estatico generado con MkDocs Material.
URL: https://docs.sherlock.sprintjudicial.com/

**Ultima actualizacion**: 2026-03-06 16:11:21

## Deploy

```bash
docker build -t sherlock-docs-site .
docker run -p 8080:80 sherlock-docs-site
```

> Generado por `sync-docs.ps1` desde el repo principal de Sherlock-docs.
