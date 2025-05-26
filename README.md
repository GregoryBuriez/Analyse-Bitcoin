# 📈 Analyse de l'évolution du Bitcoin (2012 - 2025)

## 🧠 Objectif du projet

Ce projet a pour but de **mener une analyse complète de l'évolution du Bitcoin depuis 2012**, en s’appuyant sur des **outils statistiques, des visualisations interactives**, ainsi qu’un **modèle de prévision**. L’étude est accompagnée d’un tableau de bord Power BI visant à **synthétiser les indicateurs clés (KPI)** pour une lecture simple et visuelle.

---

## 🗂️ Contenu du projet

### 🔍 1. Analyse exploratoire des données

- Chargement et nettoyage des données historiques (`Close`, `Timestamp`, etc.)
- Transformation des dates (Unix time → Datetime)
- Resampling par jour, mois, trimestre et année pour observer les tendances
- Visualisations des tendances longues et des pics de volatilité

### 📊 2. Statistiques descriptives

- Moyenne, médiane, écart-type, min, max
- Skewness (asymétrie) & kurtosis (aplatissement)
- Tests de normalité (Shapiro-Wilk, Jarque-Bera)
- Analyse des rendements journaliers

### 🔄 3. Analyse temporelle

- Tendance linéaire (régression linéaire)
- Tests d’autocorrélation (ACF, lag 1)
- Décomposition STL des séries temporelles
- Transformation Box-Cox pour stationnariser la série

### 🤖 4. Modélisation prédictive

- Sélection automatique du meilleur modèle SARIMA
- Optimisation des paramètres via l'AIC
- Vérification de la stationnarité des résidus
- Prévision des valeurs futures (non utilisées à des fins financières)

---

## 📌 Tableau de bord Power BI (à venir)

Un **dashboard interactif sous Power BI** est en cours de développement pour permettre une **visualisation dynamique** des résultats :

- 📅 Évolution annuelle du prix moyen, min et max
- ⚖️ Variation % d’une année sur l’autre
- 📈 Affichage des prévisions (avec avertissement)
- 🧾 KPI clés :
  - Moyenne annuelle
  - Rendement moyen
  - Écart-type des rendements
  - Années les plus volatiles
  - Valeurs extrêmes (min/max)

---

## 📝 Conclusion

Ce projet a permis :

- Une **étude complète de l’évolution du Bitcoin** sur plus d'une décennie.
- La mise en lumière d’une **forte croissance après 2016**, précédée d’une longue période de stagnation.
- La confirmation d’une **volatilité extrême** à travers des tests statistiques rigoureux.
- L’expérimentation de **modèles de prévision** SARIMA sur séries temporelles transformées.

> ⚠️ **Avertissement** : Ce projet est une **démonstration d’analyse de données**. Il **ne constitue en aucun cas une recommandation d’investissement ou une prévision fiable du marché**. Les résultats doivent être interprétés à des fins pédagogiques uniquement.

---

## 🚀 Technologies utilisées

- Python (Pandas, Numpy, Matplotlib, Statsmodels, Scipy)
- Power BI (pour la dataviz interactive)
- Jupyter Notebook / Visual Studio Code
