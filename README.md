# Actual Docker Install

Installation perso de Actual Budget sur un VPS avec Docker.

## Objectif

Mettre en place une instance simple, maintenable et accessible depuis un domaine.

## Contenu du projet

- `docker-compose.yml` : orchestration des services.
- `Caddyfile` : configuration Caddy (reverse proxy + HTTPS automatique).
- `README.md` : documentation du setup.

## TODO

- [x] Demande d'un hostname.
- [x] Remplacer Nginx par Caddy pour gérer automatiquement les certificats Let's Encrypt.
