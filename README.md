# Analyse en "Backtest" d'un hypothétique système de retraites par capitalisation en France

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/Vincent-20-100/backtest_retraites)](https://github.com/Vincent-20-100/backtest_retraites/issues)
[![GitHub stars](https://img.shields.io/github/stars/Vincent-20-100/backtest_retraites?style=social)](https://github.com/Vincent-20-100/backtest_retraites/stargazers)

---

## 📝 Description
**Backtest Retraite** est une étude comparative entre le **système de retraite par répartition** actuel et un **hypothétique modèle par capitalisation**, à l’aide d’une **analyse de données et d’un backtesting financier** sur la période **1985-2025**.

L’objectif est de démontrer, avec des **données concrètes** et une méthodologie sérieuse, qu'un **système capitalisé** aurait généré une retraite plus **durable** et **bénéfique** que le système actuel en France.

---

## 🎯 Partis Pris & Hypothèses Conservatrices

Ce projet repose sur une série de **choix méthodologiques prudents** afin d’éviter toute surestimation des performances d’un modèle capitalisé. Il s’agit de montrer que **même dans un scénario conservateur**, la capitalisation aurait surperformé la répartition.

### Hypothèses retenues :
- ✅ Utilisation du **CAC 40 TR** comme proxy d’un fonds souverain français (scénario conservateur).
- ✅ Utilisation du **S&P 500 TR** comme scénario optimiste, pour illustrer les effets d’un modèle capitalisé performant.
- ✅ Taux de cotisation fixe sur 40 ans, sans optimisation.
- ✅ Hypothèse de retrait prudente : **4 % par défaut**, jusqu’à 7 % max.
- ✅ Aucune prise en compte des **frais de gestion** ni de **l’inflation**.
- ✅ **Backfill du CAC 40 TR** entre 1985 et 1990 par régression multivariée (S&P500 + FTSE100).
- ✅ Utilisation du **WGBI** comme proxy obligataire (faute de données françaises longues).

### Effets bénéfiques non modélisés (mais potentiellement favorables) :
- 📈 Surcapitalisation des entreprises françaises (effet macroéconomique positif non modélisé).
- 📉 Réduction possible des cotisations grâce à la performance, pouvant stimuler la croissance et l’emploi.

---

## 📊 Contenu du projet
Le projet inclut :
- 🔹 **Analyse des données financières** (actions, obligations, salaires)
- 🔹 **Backtesting de portefeuilles** avec différentes allocations (50/50, 75/25)
- 🔹 **Comparaison des pensions** perçues sous différents modèles
- 🔹 **Visualisations** en Python (Matplotlib, Seaborn, Plotly)
- 🔹 **Rapport détaillé** au format Markdown

---

## 📂 Structure du repository
📂 backtest_retraites  
│── 📂 data/            # Contient les fichiers CSV (sources et transformés)  
│   │── 📂 raw/         # Données brutes non modifiées (sources externes)  
│   │── 📂 processed/   # Données transformées prêtes pour l'analyse  
│   │── 📂 final/       # Données finales utilisées pour les résultats  
│── 📂 notebooks/       # Contient les Jupyter Notebooks (analyses et visualisations)  
│── 📂 scripts/         # Contient les scripts Python utilisés pour l’analyse  
│── 📂 docs/            # Documentation et rapport du projet (Markdown)  
│── 📄 README.md        # Présentation du projet  
│── 📄 LICENSE          # Licence MIT  
│── 📄 requirements.txt # Liste des dépendances Python  
│── 📄 .gitignore       # Exclusion des fichiers inutiles

---

## 🚀 Pour aller plus loin
Une version du whitepaper au format PDF et un notebook réplicable sont disponibles dans `/docs/` et `/notebooks/`.

📬 Pour toute question ou contribution : ouvrez une *issue* ou contactez l’auteur.
