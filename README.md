# Jules Courné

**Ingénieur Data — Data Analyst & Data Engineer**
SQL · Python · ETL · Modélisation dimensionnelle · Power BI · Machine learning appliqué

Basé à Rouen, en Normandie. Je recherche un **premier CDI** en Data Analyst,
Business Intelligence ou Data Engineering.

**Portfolio et démos → [juleescourne.github.io/portfolio-data-analyst](https://juleescourne.github.io/portfolio-data-analyst/)**
· [jules.courne@gmail.com](mailto:jules.courne@gmail.com)

---

## Ce que je sais faire, et où c'est vérifiable

| Compétence | Projet qui la démontre |
| --- | --- |
| Pipeline ETL, schéma en étoile, chargement incrémental | [goodreads-analytics-etl](https://github.com/juleescourne/goodreads-analytics-etl) — 278 tests automatisés |
| SQL analytique, fonctions fenêtres, cohortes | [hospital-sql-analytics](https://github.com/juleescourne/hospital-sql-analytics) — 7 160 passages, 18 contrôles qualité |
| Modélisation relationnelle, ACP, aide à la décision | [cutting-tool-recommender](https://github.com/juleescourne/cutting-tool-recommender) — 12 entités, démo interactive |
| Classification, arbitrage métier d'un seuil | [customer-churn-prediction](https://github.com/juleescourne/customer-churn-prediction) — fuite de données détectée et retirée |
| Régression, feature engineering géographique | [california-housing-price-prediction](https://github.com/juleescourne/california-housing-price-prediction) — validation croisée |
| Visualisation, ingestion CSV côté client | [qvt-analysis](https://github.com/juleescourne/qvt-analysis) — traitement 100 % local |

Chaque dépôt s'exécute après un simple clone : les jeux de données sous licence ne
sont pas redistribués, mais un générateur de données synthétiques les remplace.

---

## Trois choses sur ma façon de travailler

**Les projets tournent.** Pas de « il faudrait télécharger tel dataset » : chaque
dépôt embarque un générateur, une commande de démarrage et sa documentation.

**Les contrôles qualité sont démontrés, pas affirmés.** Mes jeux de démonstration
contiennent des doublons, des dates impossibles et des valeurs hors bornes — pour
que les traitements aient quelque chose à corriger, et que ça se voie dans les logs.

**Les limites sont écrites.** Sur le projet de churn, le résultat dont je suis le
plus satisfait est d'avoir retiré une variable corrélée à 1,00 avec la cible : elle
donnait 99 % de justesse et zéro valeur opérationnelle.

---

## Stack

**Données** SQL · MySQL · SQLite · PostgreSQL · modélisation dimensionnelle et relationnelle · qualité des données
**Python** pandas · NumPy · scikit-learn · XGBoost · Pydantic · SQLAlchemy
**BI** Power BI · Plotly · Vega-Lite · Matplotlib
**Ingénierie** Git · pytest · GitHub Actions · Docker · Flask

---

## Documentation

Chaque projet est documenté en quatre volets : présentation, installation,
utilisation, et spécifications techniques — y compris les algorithmes.

Exemple : [le brassage des couloirs BMX](https://github.com/juleescourne/bmx-competition-manager/blob/main/ARCHITECTURE.md#3-algorithme-de-brassage-des-couloirs),
un carré latin 8 × 5 dont les trois propriétés se vérifient en une commande.
