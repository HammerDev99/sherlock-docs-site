# Sherlock-docs — Sitio de Documentacion

Sitio estatico generado automaticamente con MkDocs Material.

**Ultima actualizacion**: 2026-03-25 16:08:05

## Deploy

Este directorio contiene el HTML compilado listo para servir con Nginx.

`ash
docker build -t sherlock-docs-site .
docker run -p 8080:80 sherlock-docs-site
`

> Generado por `scripts/sync_docs.ps1` desde el repositorio principal de Sherlock-docs.
