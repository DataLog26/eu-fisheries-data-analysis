# 🎣 Analyse économique du secteur de la pêche dans l’Union européenne

## 🧭 Vision du projet

Le secteur de la pêche européenne est au cœur de tensions majeures : performance économique, dépendance énergétique, durabilité des ressources et cohérence des politiques publiques.

Ce projet vise à transformer des données complexes du STECF (Scientific, Technical and Economic Committee for Fisheries) en un outil d’analyse clair, interactif et exploitable, permettant d’éclairer les décisions publiques et stratégiques.

---

## 🎯 Problématique

Comment analyser la performance économique du secteur de la pêche dans l’Union européenne tout en intégrant :

* la dépendance aux ressources naturelles
* l’impact des politiques publiques
* les enjeux de durabilité

---

## 🧠 Approche analytique

Le projet repose sur une approche en trois dimensions :

### 1. Production

* Volumes et valeurs des captures
* Analyse par espèce, zone géographique et type de flottille

### 2. Performance économique

* Structure du chiffre d’affaires
* Analyse des coûts (fixes et variables)
* Rentabilité et marges opérationnelles

### 3. Analyse politique

* Étude des subventions publiques
* Focus sur la détaxe carburant
* Impact économique et environnemental

---

## 📊 Résultats clés

### 🔹 Un secteur rentable mais fragile

* Rentabilité globale positive (2008–2022)
* Forte sensibilité aux coûts énergétiques
* Dépendance structurelle aux conditions de marché

### 🔹 Un modèle basé sur un nombre limité d’espèces

* ~70 % du chiffre d’affaires concentré sur 5 espèces
* Vulnérabilité face aux chocs environnementaux et réglementaires

### 🔹 Un paradoxe économique majeur

* Les espèces les plus pêchées ne sont pas les plus rentables
* La création de valeur repose davantage sur les prix que sur les volumes

### 🔹 Le rôle déterminant des subventions

* ~0,9 milliard € de subventions indirectes par an
* Jusqu’à 15 % du chiffre d’affaires du secteur
* Les flottilles les plus énergivores sont les plus dépendantes aux aides

### 🔹 Un désalignement économique et environnemental

* Les activités les plus impactantes écologiquement sont souvent les plus subventionnées
* Question centrale pour les politiques publiques européennes

---

## 🗂️ Données

### Sources

* Données officielles du STECF (Commission européenne) : https://stecf.ec.europa.eu/document/b9b795d9-d6c5-4a27-b977-2b73afb645d2_en?prefLang=en
* Données sur les droits d’accises (Bulletin pétrolier)

### Datasets construits

* `FS.csv` : données économiques des flottilles
* `Landings.csv` : données de captures (volume et valeur)

Période analysée : **2008–2022**

---

## 🛠️ Méthodologie

### 🔹 Data Processing (Python)

* Nettoyage des valeurs manquantes
* Suppression des flottes inactives
* Réagrégation des données (confidentialité < 10 navires)
* Feature engineering (catégories de flottilles et espèces)

### 🔹 Transformation

* Pivot des tables
* Structuration des variables économiques
* Réduction de la dimension des espèces (13 000 → 16 catégories)

### 🔹 Modélisation (Power BI)

* Modèle en constellation
* 2 tables de faits (économie / captures)
* 9 tables de dimensions
* Mesures DAX pour indicateurs clés

---

## 📈 Data Visualization

Un tableau de bord interactif permet :

* Exploration multi-dimensionnelle (pays, années, flottilles)
* Analyse des performances économiques
* Visualisation des captures par zone et espèce
* Évaluation des subventions et de leur impact

👉 Dashboard Power BI : [Ajouter le lien]

---

## 🌍 Impact & enjeux

Ce projet met en évidence des enjeux structurants :

* Dépendance du secteur aux subventions publiques
* Sensibilité forte aux prix de l’énergie
* Nécessité d’arbitrer entre performance économique et durabilité environnementale

Il contribue à :

* améliorer la lisibilité des données publiques
* objectiver les débats sur la pêche européenne
* soutenir la prise de décision basée sur la donnée

---

## ⚠️ Limites

* Données agrégées pour des raisons de confidentialité
* Approximations liées au retraitement des clusters
* Absence de certaines variables environnementales

---

## 🔮 Perspectives

* Intégration d’indicateurs environnementaux (CO₂, état des stocks)
* Analyse de rentabilité par zone de pêche
* Suivi dynamique des indicateurs dans le temps
* Enrichissement avec des données externes (climat, biodiversité)

---

## 📄 Rapport

Le rapport complet est disponible dans le dossier `/report`.

---

## 👤 Auteur

Julien Grapin
Data Analyst

📬 [LinkedIn / Contact à ajouter]

---

## 💡 À retenir

Ce projet illustre comment la data peut révéler les mécanismes profonds d’un secteur stratégique, à l’intersection de l’économie, de la politique et de l’environnement.
