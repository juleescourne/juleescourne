# Jules Courné

**Data Analyst / BI junior · SQL, Python, qualité des données et Power BI**

Diplômé ingénieur de **Polytech Tours en 2024 — Systèmes d’information & Data**.
Basé à Rouen, je recherche un **CDI en Data Analyst ou BI**, avec une ouverture aux postes de Data Engineer junior orientés Python / SQL.

Je pars d’une question métier, je contrôle les données et je construis des indicateurs dont j’explique les limites. Mes projets personnels accompagnent ma montée en compétences et ma recherche d’emploi.

[Portfolio et CV](https://juleescourne.github.io/portfolio-data-analyst/) · [LinkedIn](https://www.linkedin.com/in/jules-courn%C3%A9/) · [Me contacter](mailto:jules.courne@gmail.com)

## Analyses métier & Power BI

| Projet | Question étudiée | Travail et livrables |
| --- | --- | --- |
| [Assurance automobile](https://github.com/juleescourne/assurance-auto-analytics) | Quels segments concentrent les sinistres, et lesquels ont une fréquence élevée ? | 678 013 contrats ; contrôle des rapprochements, fréquence rapportée à l’exposition, analyse globale et approfondie, trois notebooks et projet Power BI |
| [Goodreads — du catalogue à la sélection](https://github.com/juleescourne/goodreads-analytics-etl) | Comment proposer une sélection de livres en français à partir d’un catalogue imparfait ? | 1,85 million de fiches ; qualité, critères et sensibilité de la sélection, 20 fiches à vérifier, trois notebooks et projet Power BI |
| [Hospital SQL Analytics](https://github.com/juleescourne/hospital-sql-analytics) | Comment analyser les parcours patients et la couverture assureur avec des KPI cohérents ? | 7 160 passages synthétiques ; CTE, fonctions fenêtres, contrôles qualité, résultats MySQL et synthèse |

Les études Assurance et Goodreads suivent le même parcours : **cadrage → dictionnaire des KPI → qualité → analyse globale → analyse approfondie → Power BI**. Les notebooks conservent leurs résultats et les sources sont documentées pour reproduire les traitements.

Quelques enseignements :

- **Assurance :** un grand volume de sinistres ne signifie pas une fréquence élevée. Les montants manquants et les six contrats orphelins restent visibles dans l’analyse.
- **Goodreads :** une bonne note sur peu d’avis ne suffit pas à recommander un livre. La liste proposée reste à vérifier ; aucun gain de ventes n’est revendiqué.

Les rapports Power BI sont fournis au format source **PBIP**. Leurs README précisent les contrôles réalisés et ceux restant à faire dans Desktop : pour Goodreads, les mesures DAX ont été rapprochées de Pandas ; pour l’assurance, les calculs et le rendu Desktop restent à confirmer.

## Modélisation & aide à la décision

| Projet | Approche et limites |
| --- | --- |
| [Aide au choix d’outil coupant](https://github.com/juleescourne/cutting-tool-recommender) | Projet de fin d’études : base MySQL à 12 entités, ACP et recherche d’essais d’usinage similaires ; démonstration sur données synthétiques |
| [Résiliation client](https://github.com/juleescourne/customer-churn-prediction) | Baseline logistique, choix du modèle et du seuil sur validation, rapport de test et coût des fausses alertes. Des départs détectés ne sont pas des départs évités |
| [California Housing](https://github.com/juleescourne/california-housing-price-prediction) | Baseline constante et séparation par blocs géographiques. Données de 1990, inadaptées à une estimation immobilière actuelle |

Les dépôts ML indiquent les données publiques nécessaires. Les modèles historiques des démonstrations navigateur sont distingués des évaluations de référence.

## Applications & visualisation

- [QVTi](https://github.com/juleescourne/qvt-analysis) : exploration d’enquêtes et distributions de réponses, avec traitement local dans le navigateur.
- [BMX Competition Manager](https://github.com/juleescourne/bmx-competition-manager) : application Flask et algorithme de rotation des couloirs dont les propriétés sont vérifiables.

## Parcours

- **SOLUTEC — CDI, septembre 2025 à janvier 2026** : intercontrat sans mission client ; montée en compétences SQL, Python et Power BI, notamment avec la première version du projet personnel Goodreads.
- **SOLUTEC — stage de fin d’études, avril à août 2024** : application interne de gestion des notes de frais ; contrôle des données, agrégations et modélisation PostgreSQL.
- **Projet de fin d’études, 2023–2024** : aide au choix d’outil coupant avec le département Génie mécanique de l’université de Tours.
- **LIFAT — stage Data Scientist R&D, mai à septembre 2023** : préparation de données multimédias et traitement du langage.

## Outils utilisés

SQL · MySQL · PostgreSQL · Python · pandas · Matplotlib · Power Query · Power BI · DAX · Plotly · scikit-learn · XGBoost · Git · GitHub Actions
