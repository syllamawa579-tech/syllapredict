# Sylla Predict V23 — prêt pour mise en ligne

Version téléphone + backend réel + PostgreSQL + Sportmonks + moteur Poisson/Elo/ML.

## 6 compétitions
- Premier League
- La Liga
- Serie A
- Bundesliga
- Ligue 1
- UEFA Champions League

## Architecture
Téléphone/Web → Nginx → FastAPI → PostgreSQL → Sportmonks → moteur de prédiction.

Voir `DEPLOIEMENT.md` pour le lancement avec Docker Compose.
