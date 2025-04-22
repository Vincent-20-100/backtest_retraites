# Analyse en "Backtest" d'un hypothétique système de retraites par capitalisation en France

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/Vincent-20-100/backtest_retraites)](https://github.com/Vincent-20-100/backtest_retraites/issues)
[![GitHub stars](https://img.shields.io/github/stars/Vincent-20-100/backtest_retraites?style=social&cacheBuster=1)](https://github.com/Vincent-20-100/backtest_retraites/stargazers)

---

## 📝 Description
**Backtest Retraite** est une étude comparative entre le **système de retraite par répartition** actuel et un **hypothétique modèle par capitalisation**, à l’aide d’une **analyse de données et d’un backtesting financier** sur la période **1985-2025**.

L’objectif est de démontrer, avec des **données concrètes** et une méthodologie sérieuse, qu'un **système capitalisé** aurait généré une retraite plus **durable** et **bénéfique** que le système actuel en France.

---

## 👀 Rapport final à lire en priorité

Avant d'explorer les notebooks ou de plonger dans le code, commencez par lire le **rapport final** qui résume les résultats, les implications et les grands enseignements de l'étude, **sans jargon technique** :

👉 [📘 Lire le rapport final](docs/Rapport.md)

Ce document constitue la **vue d'ensemble essentielle** du projet, pensée pour un public large ; citoyens curieux, économistes, décideurs ou journalistes et permet de comprendre les conclusions **avant de décortiquer la méthode** dans les notebooks.

---

## 🎯 Partis Pris & Hypothèses

Ce projet repose sur une série de **choix méthodologiques prudents** afin d’éviter toute surestimation des performances d’un modèle capitalisé. Il s’agit de montrer que **même dans un scénario conservateur**, la capitalisation aurait surperformé la répartition.

### Hypothèses retenues :
- Utilisation du CAC 40 TR comme proxy d’un fonds souverain français (scénario conservateur).
- Utilisation du S&P 500 TR comme proxy de performance haute — non pas pour idéaliser les rendements américains, mais pour représenter une trajectoire réaliste qu’aurait pu suivre un CAC 40 soutenu par des décennies de capitalisation massive. Ce choix permet d’estimer une fourchette haute crédible, dans l’hypothèse où un fonds souverain français aurait contribué à surcapitaliser durablement les entreprises nationales.
- Taux de cotisation historique appliqué : de 15 % en 1985 à 24 % en 2025 (part patronale + salariale ; source INCEE).
- Hypothèse de retrait : 9 %, calibrée sur une durée moyenne de retraite (25 ans) et pour assurer la pérennité du fond et maximiser les pensions.
- Prise en compte de 0,5% de frais de gestion.
- Backfill du CAC 40 TR entre 1985 et 1990 (données manquantes).
- Utilisation du WGBI comme proxy obligataire (faute de données françaises longues).

### Effets bénéfiques non modélisés (mais potentiellement favorables) :
- Surcapitalisation des entreprises françaises via le fond, une part est prise en compte dans la version optimiste (S&P 500 comme proxi), mais on peut aussi penser à une augmentation des salaires et de l'économie en général grâce à ce surplus d'investissements.
- Réduction potentielle des cotisations grâce à la performance, stimulant la consommation, l’épargne libre, ou l’emploi.

---

## 📊 Contenu du projet
Le projet inclut :
- 🔹 **Analyse des données financières** (actions, obligations, salaires)
- 🔹 **Backtesting de portefeuilles** avec différentes allocations (50/50, 75/25)
- 🔹 **Comparaison des pensions** perçues sous différents modèles
- 🔹 **Visualisations** en Python
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
│── 📂 docs/            # Documentation et rapport du projet (Markdown, PDF)  
│── 📄 README.md        # Présentation du projet  
│── 📄 LICENSE          # Licence MIT  
│── 📄 requirements.txt # Liste des dépendances Python  
│── 📄 .gitignore       # Exclusion des fichiers inutiles

---

## 🚀 Pour aller plus loin
Une version du whitepaper au format PDF et un notebook réplicable sont disponibles dans `/docs/` et `/notebooks/`.

📬 Pour toute question ou contribution : ouvrez une *issue* ou contactez l’auteur.
