📌 Présentation du projet

Ce projet consiste à développer un dashboard décisionnel de reporting des données de santé avec Power BI.

L'objectif est de transformer un ensemble de données de santé en indicateurs et visualisations interactives permettant d'explorer les caractéristiques des patients, les informations médicales et les aspects financiers associés aux prestations de santé.

🎯 Objectifs

Le projet vise à :

Explorer et comprendre les données de santé.
Nettoyer et préparer les données.
Analyser les caractéristiques des patients.
Étudier la répartition des patients par âge et sexe.
Analyser les informations médicales.
Étudier les établissements et prestataires de santé.
Analyser les montants de facturation.
Construire des KPI de suivi.
Créer un dashboard interactif avec Power BI.
Faciliter l'interprétation des données pour la prise de décision.

🗂️ Données
Le dataset contient différentes informations relatives aux patients et à leurs prises en charge.

Les principales variables comprennent notamment :

Patient
Âge
Sexe
Groupe d'âge
Condition médicale
Médecin
Hôpital
Type d'admission
Date d'admission
Date de sortie
Assurance
Montant de facturation
Médicaments
Résultats des examens

🔄 Méthodologie
1. Exploration des données

Une première exploration a permis d'identifier :

La structure du dataset
Le nombre de lignes et de colonnes
Les types de données
Les valeurs manquantes
Les doublons
Les valeurs aberrantes
Les variables numériques et catégorielles
2. Nettoyage et transformation

Les données ont été préparées à l'aide de Power Query.

Les opérations comprennent :

Vérification des valeurs manquantes
Vérification des doublons
Transformation des types de données
Conversion des variables numériques
Nettoyage des variables textuelles
Création de catégories d'âge
Préparation des données pour le modèle Power BI

Une attention particulière a été portée à la variable Billing Amount, afin de garantir son utilisation correcte dans les calculs et visualisations.

👥 Analyse démographique

L'analyse permet d'étudier la population selon :

Sexe
Âge
Tranches d'âge
Répartition des patients
Conditions médicales

Les tranches d'âge permettent notamment de comparer les différents groupes de patients.

Exemple :

18–30 ans
31–45 ans
46–60 ans
61–75 ans
76 ans et plus

🏥 Analyse médicale
Le dashboard permet d'explorer :

Les principales conditions médicales.
La fréquence des pathologies.
La répartition des patients par condition.
Les types d'admission.
Les résultats des examens.
Les traitements et médicaments.
💰 Analyse financière

Une partie du reporting est consacrée à l'analyse des coûts de santé.

Les indicateurs permettent notamment d'étudier :

Montant total de facturation
Facturation moyenne
Facturation par condition médicale
Facturation par établissement
Facturation par assurance
Facturation par groupe d'âge

📊 KPI du dashboard
Les principaux KPI peuvent inclure :

👥 Nombre total de patients
🏥 Nombre d'hôpitaux
🩺 Nombre de médecins
💰 Facturation totale
💵 Facturation moyenne
📋 Nombre d'admissions
📊 Nombre de conditions médicales

📈 Visualisations Power BI
Le dashboard utilise différents types de visualisations :

Cartes KPI
Graphiques en barres
Graphiques en colonnes
Donut charts
Graphiques temporels
Matrices
Tableaux
Segmenteurs (Slicers)
Indicateurs de performance

Les filtres permettent d'explorer les données selon plusieurs dimensions.

🧮 DAX
Des mesures DAX sont utilisées pour calculer les principaux indicateurs du reporting.

Exemples :

Total Patients =
COUNTROWS(healthcare)
Total Billing =
SUM(healthcare[Billing Amount])
Average Billing =
AVERAGE(healthcare[Billing Amount])

Ces mesures permettent de créer des KPI dynamiques et interactifs.

🛠️ Technologies utilisées
Technologie	Utilisation
📊 Power BI	Reporting et visualisation
🔄 Power Query	Nettoyage et transformation
🔢 DAX	Calcul des indicateurs
🐍 Python	Analyse exploratoire
🐼 Pandas	Manipulation des données
📈 Matplotlib / Plotly	Visualisation exploratoire
📗 Excel / CSV	Données sources
🔧 Git / GitHub	Versionnement

📁 Structure du projet
Healthcare_Analysis/
│
├── data/
│   ├── healthcare.csv
│   
│
├── notebooks/
│   └── healthcare_eda.ipynb
│
├── powerbi/
│   └── healthcare_dashboard.pbix
│
├── images/
│   └── healthcare_dashboard.png
│
├── README.md
└── requirements.txt

📌 Résultats du projet
Le dashboard permet de disposer d'une vision synthétique des données de santé à travers :

Une analyse démographique des patients.
Une analyse des conditions médicales.
Une analyse des admissions.
Une analyse des établissements.
Une analyse des coûts de santé.
Des KPI interactifs.
Des filtres permettant une exploration dynamique.

💡 Compétences démontrées
Ce projet met en évidence mes compétences en :

Data Analysis
Exploratory Data Analysis
Data Cleaning
Power BI
Power Query
DAX
Data Visualization
KPI Development
Business Intelligence
Data Storytelling
Python
Pandas
Analyse décisionnelle

🚀 Perspectives d'amélioration
Le projet pourrait être enrichi avec :

Prévision du nombre d'admissions.
Analyse prédictive des coûts.
Détection des anomalies de facturation.
Segmentation des patients.
Analyse de la durée de séjour.
Modèles Machine Learning.
Automatisation de l'actualisation des données.
Mise en place d'un pipeline ETL.

👤 Auteur
Sallah DIA
Data Analyst | BI Analyst | Power BI Specialist

Stack : Power BI · SQL · Python · DAX · Power Query · Data Analysis · IA

⭐ Ce projet fait partie de mon portfolio Data Analyst.
