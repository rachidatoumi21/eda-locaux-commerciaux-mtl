# 📊 Analyse des locaux commerciaux — Montréal (EDA Python)

Projet de **data analysis** visant à analyser l’occupation des locaux commerciaux à Montréal afin d’identifier :

- les zones avec le plus de vacance  
- les tendances d’occupation  
- les opportunités économiques  
- les signaux de risque commercial  

 Objectif : démontrer une capacité complète en **data cleaning, analyse exploratoire et visualisation**.

---

##  Objectifs du projet

- Analyser la répartition des locaux commerciaux  
- Identifier les zones avec forte vacance  
- Comprendre les types de commerces dominants  
- Détecter les tendances par arrondissement / quartier  
- Produire des **visualisations claires et exploitables**



## 📁 Données

 Source : Données ouvertes — Ville de Montréal  

### Contenu :
- Arrondissement  
- Quartier  
- Type de commerce  
- Statut (occupé / vacant)  
- Date de création  
- Origine des données  


##  Préparation des données

### Nettoyage
- Suppression des doublons  
- Nettoyage des chaînes (`strip`)  
- Gestion des valeurs manquantes  
- Conversion des dates  

###  Feature engineering
- Création de variables utiles  
- Standardisation des catégories  

###  Validation
- Vérification cohérence des données  
- Contrôle des valeurs aberrantes  


##  Analyse exploratoire (EDA)

###  Répartition des statuts (occupé vs vacant)

![Répartition des statuts](reports/figures/status_distribution.png)

 **Insight :**
- La majorité des locaux sont occupés  
- Une proportion non négligeable reste vacante  


###  Vacance par arrondissement

![Vacance par arrondissement](reports/figures/vacancy_by_arrondissement.png)

 **Insight :**
- Certains arrondissements concentrent plus de locaux vacants  
- Indicateur important pour les investisseurs  


### 🏢 Types de commerces les plus fréquents

![Types de commerces](reports/figures/top_commerce_types.png)

 **Insight :**
- Forte concentration sur certains secteurs  
- Possibilité de saturation du marché  


### 📈 Évolution dans le temps

![Évolution temporelle](reports/figures/time_evolution.png)

 **Insight :**
- Permet d’identifier des tendances économiques  
- Impact possible de facteurs externes  


###  Analyse par quartier

![Analyse par quartier](reports/figures/quartier_analysis.png)

 **Insight :**
- Forte disparité entre quartiers  
- Opportunités ciblées selon localisation  


##  Insights clés

**1. Vacance non négligeable**  
→ Indique des difficultés économiques dans certaines zones  

**2. Concentration commerciale**  
→ Certains secteurs sont saturés  

**3. Inégalités géographiques**  
→ Certains arrondissements performent mieux  

**4. Opportunités d’investissement**  
→ Zones avec vacance élevée = potentiel  


##  Recommandations

- Réduire les locaux vacants (incitations économiques)  
- Diversifier les types de commerce  
- Cibler les zones faibles  
- Suivre les tendances dans le temps  


##  Outils utilisés

- Python (pandas, matplotlib, seaborn)  
- Jupyter Notebook  
- VS Code  


## 🔁 Reproduire le projet

```bash
# Lancer le notebook
notebooks/EDA_locaux_commerciaux.ipynb
