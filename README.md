# 📊 Analyse des Féminicides — Bases de Données & Sciences des Données 2

Projet de groupe réalisé par une équipe de 4 en **L2 MIASHS — Semestre 4**, dans le cadre des UE **Bases de Données** et **Sciences des Données 2**.

## Présentation

Ce projet analyse les féminicides à l'échelle mondiale en construisant une base de données relationnelle enrichie de plusieurs indicateurs socio-politiques, puis en réalisant des analyses statistiques et des visualisations en R.

## Contenu du repo

```
feminicides-bd/
├── sql/                              → Scripts SQL
│   ├── sql_bd_feminicide.sql         → Création de la base de données
│   ├── sql_table_pays.sql            → Table des pays
│   ├── insert_continent.sql          → Insertion des continents
│   └── insert_feminicide_cleaned.sql → Insertion des données féminicides
│
├── donnees/                          → Jeux de données sources (CSV)
│   ├── BD_FEMINICIDE_CSV.csv         → Données féminicides par pays
│   ├── BD_PAYS_CSV.csv               → Données pays
│   ├── BD_CONTINENT_CSV.csv          → Données continents
│   ├── drinks.csv                    → Consommation d'alcool par pays
│   ├── droit avortement.csv          → Droits à l'avortement par pays
│   ├── niveau_de_paix_interieur_sur_5.csv
│   ├── Niveau_de_terreur_politique.csv
│   ├── Niveau_du_nombres_d'homicide_pour_100k_habitants.csv
│   └── Niveau_du_nombre_de_policer_pour_100k_habtiant.csv
│
├── rapport/                          → Analyses R
│   ├── rapport_structure_projet.Rmd  → Rapport principal (R Markdown)
│   ├── rapport_structure_projet.pdf  → Rapport compilé
│   ├── r.Rmd                         → Analyses complémentaires
│   └── r.pdf                         → Résultats compilés
│
├── MOD.png                           → Modèle Objet des Données (schéma relationnel)
└── Requetes_SQL_Explication_Feminicides.pdf → Requêtes SQL commentées
```

## Stack technique

- **SQL** : MySQL — modélisation relationnelle, requêtes d'analyse
- **R** : ggplot2, dplyr, tidyr — visualisations et analyses statistiques

## Reproduire l'analyse

```sql
-- 1. Créer la base
source sql/sql_bd_feminicide.sql
source sql/sql_table_pays.sql
source sql/insert_continent.sql
source sql/insert_feminicide_cleaned.sql
```

```r
# 2. Ouvrir rapport/rapport_structure_projet.Rmd dans RStudio et knit
```

## Auteurs

Projet de groupe — L2 MIASHS, Semestre 4, 2023–2024
