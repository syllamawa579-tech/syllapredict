# Déploiement public de Sylla Predict — Render

1. Mettre le dossier du projet dans un dépôt GitHub.
2. Dans Render : **New → Blueprint**.
3. Sélectionner le dépôt et laisser Render lire `render.yaml`.
4. Renseigner `SPORTMONKS_API_TOKEN` comme secret.
5. Attendre le déploiement du backend, du frontend et de PostgreSQL.
6. Ouvrir l'URL publique du service **sylla-predict**.

Le frontend utilise `/api/...` sur le même domaine : le téléphone n'a plus besoin de `127.0.0.1`.

Vérifications : `/api/health` puis `/api/leagues`.

Ne jamais mettre le token Sportmonks dans GitHub ou dans `index.html`.
