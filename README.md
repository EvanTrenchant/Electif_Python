https://www.youtube.com/watch?v=h1sAzPojKMg&ab_channel=VisualStudioCode

# Avancées dans le Notebook d'Analyse de Données de la NBA

## Importation des Données et noettoyage
- [x] Réalisation du scrapping des données depuis le site officiel de la NBA.
- [x] Définition des en-têtes nécessaires pour la requête HTTP.
- [x] Extraction des données pour les saisons régulières et les playoffs de 2013 à 2024.
- [x] Nettoyage et enregistrement des données dans un fichier CSV.
- [x] Création de DataFrames séparés pour les saisons régulières et les playoffs.

## Analyse des Données
- [x] Visualisation de la distribution des minutes jouées par match.
- [x] Calcul de différentes statistiques pour évaluer l'évolution du jeu au fil des années.
- [x] Visualisation de l'évolution des statistiques pour 48 minutes en saison régulière.

## Analyse des Tendances sur 10 ans
- [x] Estimation du nombre de possessions pour chaque année en utilisant une formule spécifique.
- [x] Calcul de différents pourcentages de réussite pour les tirs et d'autres ratios pertinents.
- [x] Ajustement des statistiques pour 48 minutes de jeu.
- [x] Visualisation de l'évolution des statistiques au fil des années, notamment pour les tirs à 3 points.

## Interprétation des Résultats
- [x] Analyse des tendances observées dans les données, en mettant en évidence les changements significatifs dans le jeu de la NBA au cours des 10 dernières années.
- [x] Mise en évidence des évolutions dans le style de jeu des équipes et des joueurs, notamment en ce qui concerne l'utilisation des tirs à longue distance.
---

# Signification en français de chacune des variables du `.csv` :

| Variable | Signification en français                                                                                       |
|----------|----------------------------------------------------------------------------------------------------------------|
| RANK     | Classement                                                                                                     |
| NAME     | Nom du joueur                                                                                                  |
| TEAM     | Équipe                                                                                                         |
| POS      | Poste du joueur                                                                                                |
| AGE      | Âge du joueur                                                                                                  |
| GP       | Nombre de matchs joués                                                                                         |
| MPG      | Minutes par match (Moyenne)                                                                                   |
| USG%     | Pourcentage d'utilisation (Usage Percentage)                                                                   |
| TO%      | Pourcentage de balles perdues (Turnover Percentage)                                                           |
| FTA      | Nombre de lancers francs tentés (Free Throw Attempts)                                                         |
| FT%      | Pourcentage de réussite aux lancers francs (Free Throw Percentage)                                             |
| 2PA      | Nombre de tentatives de panier à deux points (2-Point Field Goal Attempts)                                      |
| 2P%      | Pourcentage de réussite aux tirs à deux points (2-Point Field Goal Percentage)                                  |
| 3PA      | Nombre de tentatives de panier à trois points (3-Point Field Goal Attempts)                                     |
| 3P%      | Pourcentage de réussite aux tirs à trois points (3-Point Field Goal Percentage)                                 |
| eFG%     | Pourcentage de réussite au tir ajusté (Effective Field Goal Percentage)                                         |
| TS%      | Pourcentage de vrai tir (True Shooting Percentage)                                                             |
| PPG      | Points marqués par match (Points Per Game)                                                                     |
| RPG      | Rebonds par match (Rebounds Per Game)                                                                          |
| APG      | Passes décisives par match (Assists Per Game)                                                                  |
| SPG      | Interceptions par match (Steals Per Game)                                                                      |
| BPG      | Contres par match (Blocks Per Game)                                                                            |
| TPG      | Balles perdues par match (Turnovers Per Game)                                                                  |
| P+R      | Points et rebonds (Points plus Rebounds)                                                                       |
| P+A      | Points et passes décisives (Points plus Assists)                                                               |
| P+R+A    | Points, rebonds et passes décisives (Points, Rebounds, plus Assists)                                            |
| VI       | Valeur individuelle (Value Index)                                                                              |
| ORtg     | Offensive Rating (Cote offensive)                                                                              |
| DRtg     | Defensive Rating (Cote défensive)                                                                              |
