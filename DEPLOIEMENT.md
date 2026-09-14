# Mise en ligne de Sylla Predict V23

## Test sur un PC ou serveur
1. Installer Docker + Docker Compose.
2. Copier `.env.example` vers `.env`.
3. Mettre le vrai `SPORTMONKS_API_TOKEN` dans `.env`.
4. Lancer : `docker compose up -d --build`
5. Ouvrir `http://IP_DU_SERVEUR:8080`.
6. Dans l'application, l'API n'a plus besoin de `127.0.0.1` : le frontend passe par `/api`.
7. Cliquer sur « Synchroniser Sportmonks ».

## Important
Cette version est prête à être déployée, mais je ne peux pas créer à ta place un compte d'hébergement, un domaine ou un token Sportmonks. Une fois un hébergeur choisi et les variables renseignées, le site peut être publié.

## Production
Utiliser HTTPS (reverse proxy/Caddy/Traefik ou service cloud), un mot de passe PostgreSQL fort et sauvegarder le volume `postgres_data`.
