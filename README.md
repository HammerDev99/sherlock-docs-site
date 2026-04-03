# Sherlock-docs — Sitio de Documentacion

Sitio estatico generado automaticamente con MkDocs Material.

**Ultima actualizacion**: 2026-04-02 19:00:24

## Deploy

Este directorio contiene el HTML compilado listo para servir con Nginx.

`ash
docker build -t sherlock-docs-site .
docker run -p 8080:80 sherlock-docs-site
`

> Generado por `scripts/sync_docs.ps1` desde el repositorio principal de Sherlock-docs.
