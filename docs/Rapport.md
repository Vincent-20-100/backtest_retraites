# 📊 Rapport d’étude — Retraite par capitalisation (1985–2025)

## 🧭 Pourquoi ce rapport ?

La question des retraites agite régulièrement le débat public en France. Les réformes se succèdent, souvent techniques, toujours conflictuelles. Pourtant, un angle reste systématiquement évité : celui d’un **changement de modèle structurel**.

Ce rapport ne propose pas une énième réforme des paramètres existants.  
Il explore **une alternative complète** :  
> *Et si, depuis 1985, les cotisations retraite avaient été capitalisées plutôt que redistribuées ?*

Autrement dit : que se serait-il passé si chaque salarié avait vu ses cotisations placées, mois après mois, dans un fonds commun investi dans l’économie réelle — plutôt que de financer directement les pensions actuelles ?

Pour répondre à cette question, une **simulation rigoureuse** a été conduite à partir de **40 années de données économiques réelles** (1985–2025), en comparant deux approches :  
- Le système **par répartition** actuellement en vigueur,  
- Et un système **par capitalisation**, tel qu’il aurait pu être mis en place dès 1985 sous la forme d'un fond souverain.

Ce rapport vise à fournir **des ordres de grandeur concrets**, lisibles et vérifiables, pour éclairer un débat trop souvent idéologique.

> Car comprendre ce qui aurait pu être, c’est déjà mieux choisir ce qui peut encore advenir.

---

## 1. 🎭 Le scénario simulé

### Cotisation :
- Basée sur le **salaire médian** français (source INSEE).
- Montant prélevé chaque mois selon les **taux de cotisation historiques.**

### Durée :
- **40 ans d’épargne continue**, de janvier 1985 à décembre 2024.

### Portefeuilles testés :
- **Profil prudent** : 50% actions / 50% obligations
- **Profil dynamique** : 75% actions / 25% obligations

### Retraite simulée :
- Conversion du capital en pension via un **taux de retrait annuel** de **9%** du capital, calculé pour assurer un fonds soutenable sur une durée moyenne de retraite de **25 ans** (moyenne actuelle).

### Redistribution :
- Hypothèse d’un **prélèvement de solidarité** pour financer une pension minimale universelle (basé sur les chiffre actuels de l'ASPA  et l'ASV).

---

## 2. 🎯 Partis pris & Hypothèses

Ce projet repose sur une série de choix méthodologiques prudents afin d’éviter toute surestimation des performances d’un modèle capitalisé. Il s’agit de montrer que même dans un scénario conservateur, la capitalisation aurait surperformé la répartition.

Hypothèses retenues :
- Utilisation du CAC 40 TR comme proxy d’un fonds souverain français (scénario conservateur).
- Utilisation du S&P 500 TR comme proxy de performance haute — non pas pour idéaliser les rendements américains, mais pour représenter une trajectoire réaliste qu’aurait pu suivre un CAC 40 soutenu par des décennies de capitalisation massive. Ce choix permet d’estimer une fourchette haute crédible, dans l’hypothèse où un fonds souverain français aurait contribué à surcapitaliser durablement les entreprises nationales.
- Taux de cotisation historiques (source INSEE).
- Hypothèse de retrait prudente : 9 %, calibrée sur une durée moyenne de retraite (25 ans).
- Prise en compte de 0,5% de frais de gestion.
- Backfill du CAC 40 TR entre 1985 et 1990 (données manquantes).
- Utilisation du WGBI comme proxy obligataire (faute de données françaises longues).

Effets bénéfiques non modélisés (mais potentiellement favorables) :
- Surcapitalisation des entreprises françaises via l’épargne retraite (effet macro positif absent du modèle, comme la hausse du salaire médian).
- Réduction potentielle des cotisations grâce à la performance, stimulant la consommation, l’épargne libre, ou l’emploi.

---

## 3. 📈 Résultats clés

### 📊 Performance des marchés (1985–2025)

| Indice simulé        | Multiplicateur de capital | Rendement annualisé |
|----------------------|---------------------------|----------------------|
| **S&P 500 TR**       | ×76                       | 11,47 %              |
| **CAC 40 TR**        | ×32                       | 9,06 %               |
| **WGBI (oblig.)**    | ×5                        | 4,44 %               |

### 💰 Capital et pensions estimées

| Type de portefeuille  | Capital final            | Pension estimée       | Multiplicateur (vs retraite actuelle) |
|-----------------------|--------------------------|-----------------------|---------------------------------------|
| CAC 40 / WGBI (50/50) | 484 000 €                | ~3600                 | **~x2.2**                             |
| CAC 40 / WGBI (75/25) | 591 000 €                | ~4700                 | **~x2.9**                             |
| S&P 500 / WGBI (50/50)| 692 000 €                | ~6200€                | **~x3.9**                             |
| S&P 500 / WGBI (75/25)| 1 049 000 €              | ~10000€               | **~x6.2**                             |

Ces résultats tiennent compte de l’augmentation des salaire et des taux de prélèvements historiques et sont simulés avec une grande prudence : pas de levier, pas d’investissement exotique, pas de stock-picking.

### 👑 Taille du fond souverain estimée
Le système français actuel repose sur une logique de redistribution immédiate : les cotisations des actifs servent directement à payer les pensions des retraités.  \
Ce modèle ne constitue aucune réserve, et ne laisse aucune marge de manœuvre en cas de choc démographique ou économique.

À l’inverse, un système par capitalisation permettrait aux cotisations de s’accumuler dans un fonds souverain, générant des rendements sur le long terme et assurant une vraie stabilité. \
📊 En projetant notre simulation sur l’ensemble des retraités actuels, **le capital total** qui aurait été constitué varie entre :
- **8 228 milliards** d’euros (profil prudent),
- **17 833 milliards** d’euros (profil dynamique).

Ce sont des ordres de grandeur comparables à plusieurs années de PIB français.
Un tel stock de capital permettrait d’assurer une soutenabilité structurelle, une autonomie stratégique, et une capacité de redistribution renforcée, sans dépendre du bon vouloir des générations futures.

---

## 4. 📊 Visualisations clés

### Performance des différents portefeuilles
![SP500](../charts/perf_portefeuilles.png)

### Comparaison des pensions versées selon les modèles
![SP500](../charts/comparaison_pensions_2.png)

---

## 5. 🧠 Interprétation des résultats

### ✔️ Ce que démontre la simulation
- La capitalisation **crée un stock de richesse** au fil du temps, grâce aux intérêts composés et à la croissance des actifs.
- Ce stock constitue un **véritable fonds retraite** : mobilisable en cas de crise, transmissible, et générateur de revenus stables.
- Même en portefeuille prudent, **les rendements dépassent de très loin** ceux du système par répartition.
- Une **redistribution ciblée** reste possible sans compromettre la viabilité du système, en prélevant une fraction minime des performances.

### ❌ Ce que le système actuel ne permet plus
- Il **ne constitue aucun fond** : chaque euro collecté est immédiatement redistribué. Aucune réserve, aucune capitalisation.
- Il est donc **sans aucune marge de manœuvre** : en cas de ralentissement économique, de baisse des naissances ou de choc démographique, il n’a **aucun amortisseur**.
- Il **ne laisse rien au cotisant** : pas d’héritage, pas de souplesse, pas de visibilité.
- Il repose sur une **logique de flux** ultra-sensible aux aléas économiques et politiques, rendant chaque réforme potentiellement explosive.

### ⚠️ Le fond du problème : stock vs flux
Un système **capitalisé** repose sur un **stock d’actifs**, qui produit des revenus.  
Un système **par répartition** repose sur un **flux de cotisations**, qui doit être constant et croissant pour ne pas s’effondrer.

> ✅ La capitalisation fonctionne même en cas de stagnation.  
> ❌ La répartition s'effondre dès que la croissance ou la natalité faiblit.

### 🏗️ Un effet secondaire vertueux : financer l’économie réelle

Au-delà de la performance individuelle, un système de retraite capitalisé **transforme chaque cotisation en levier économique**.

Pourquoi ? Parce qu’un fonds souverain bien géré investit dans **des entreprises, des infrastructures, des obligations publiques ou privées**, et donc **alimente directement l’économie réelle**.

Dans notre simulation, nous avons volontairement choisi des indices représentatifs :  
- Le **CAC 40 TR**, proxy d’un portefeuille français diversifié,  
- Le **S&P 500 TR**, comme projection d’un marché international mature,  
- Le **WGBI TR**, représentant les obligations souveraines mondiales.

Ces choix ne sont pas anodins : ils montrent qu’un tel fonds aurait **boosté l’investissement productif**, **soutenu les entreprises** et **offert des capitaux stables** à long terme.

Contrairement aux politiques de relance monétaire (QE, dettes publiques, taux bas artificiels), ce modèle **n’injecte pas d’argent magique** : il transforme **l’épargne réelle** en **investissement pérenne**.

> 📌 Un système de retraite capitalisé n’est pas qu’un filet social.  
> C’est un **vecteur puissant de développement économique**, piloté par la réalité et non par la dette.

---

## 6. 📣 À qui s’adresse ce rapport ?

Ce rapport s’adresse avant tout :

- À celles et ceux qui **préfèrent les faits aux slogans**, les chiffres aux idées reçues.
- Aux curieux qui veulent **comprendre comment fonctionne vraiment notre système de retraite**, au-delà des débats partisans.
- Aux citoyens soucieux d’évaluer **les alternatives possibles**, de manière rigoureuse et documentée.
- Aux professionnels de la finance, de la donnée, de l’économie ou de la gestion publique qui souhaitent **tester un scénario systémique, chiffré et transparent**.
- Aux responsables politiques en quête de **solutions pérennes**, fondées sur la réalité, et non sur des hypothèses déconnectées du terrain.

> Ce rapport ne cherche pas à convaincre par l’idéologie,  
> mais à **éclairer par les faits**.

---

## 7. 🔍 Pour aller plus loin

### 📂 Le code, les données, les visualisations et les hypothèses sont 100% open-source :

👉 GitHub : [github.com/Vincent-20-100/backtest_retraites](https://github.com/Vincent-20-100/backtest_retraites)


> « Ce qui est investi, fructifie. Ce qui est redistribué, disparaît. »

Face aux impasses comptables du système actuel, la capitalisation offre une **alternative concrète, mesurable, et juste**.

Il est temps de remettre les faits au cœur du débat.

---

## 8. 🔧 Pistes d'amélioration du modèle

Ce rapport se veut une première exploration rigoureuse, mais perfectible. Plusieurs pistes pourraient enrichir ou affiner la simulation actuelle :

1. **Diversification des profils simulés**  
   Le modèle repose actuellement sur un profil médian unique. Il serait pertinent d’introduire :
   - Un **salarié au SMIC**, pour estimer les effets redistributifs nécessaires.
   - Un **profil du dernier quartile**, afin d’évaluer la contribution et la pension attendue des salaires plus élevés.
   - Un **travailleur indépendant** ou un **agent public**, dont les régimes et trajectoires de cotisation diffèrent.

2. **Alignement avec une estimation réelle de retraite**  
   La comparaison repose sur une pension médiane, qui ne reflète pas nécessairement la pension d’un profil ayant exactement le parcours simulé (salaire médian, carrière complète). Une estimation plus fine pourrait être obtenue via :
   - Le **simulateur officiel** (ex. [info-retraite.fr](https://www.info-retraite.fr/)).
   - Une **modélisation interne des trimestres et règles de calcul du régime actuel**.

3. **Optimisation des allocations**  
   Les portefeuilles testés (50/50 et 75/25) sont fixes dans le temps. Des alternatives dynamiques pourraient être testées :
   - **Allocations évolutives avec l’âge** (plus agressives en début de carrière, plus prudentes à l’approche de la retraite).
   - **Rééquilibrage annuel**, pour refléter une gestion pilotée type fonds souverain.

4. **Intégration du risque de change**  
   Les indices S&P 500 et WGBI sont exprimés en dollars. Une approche plus réaliste pour un cotisant en euros pourrait inclure :
   - La **conversion des rendements historiques en euros** via le taux de change EUR/USD.
   - L’utilisation d’indices comparables européens exprimés en euros.

5. **Simulation de la volatilité individuelle**  
   Les rendements moyens sont utilisés, mais un retraité individuel peut connaître un parcours très différent selon l’année de départ. On pourrait intégrer :
   - Des **simulations de scénarios de marché aléatoires** (type Monte Carlo).
   - L’impact de **crises majeures** (2008, COVID, etc.) sur les pensions.

6. **Effets macroéconomiques indirects**  
   Par prudence, le modèle n’intègre pas les effets positifs que pourrait engendrer un système capitalisé massif. Mais on pourrait estimer :
   - Les **externalités économiques** d’une surcapitalisation (hausse de l’investissement, de l’emploi, du PIB).
   - Les **effets budgétaires indirects** (baisse des cotisations nécessaires, hausse de l’épargne libre, etc.).

Ces améliorations pourraient faire l’objet d’un second volet ou d’un projet collaboratif open-source visant à affiner ce modèle de retraite capitalisée.
