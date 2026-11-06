#  Analyse des séries temporelles – AirPassengers

##  Présentation du projet

Ce projet porte sur l'analyse des séries temporelles (*Time Series Analysis*) à travers le célèbre jeu de données **AirPassengers**, qui représente le nombre mensuel de passagers du transport aérien international entre 1949 et 1960.

L'objectif principal est d'étudier l'évolution du trafic aérien au cours du temps, d'identifier les tendances et les variations saisonnières, d'analyser les propriétés statistiques de la série et d'explorer les techniques de prévision.

Ce projet permet de mettre en pratique les principales méthodes d'analyse des séries temporelles à l'aide de Python.

##  Objectifs du projet

- Comprendre les concepts fondamentaux des séries temporelles.
- Explorer et visualiser les données temporelles.
- Identifier les tendances à long terme.
- Détecter les variations saisonnières.
- Étudier la stationnarité de la série temporelle.
- Appliquer des transformations statistiques si nécessaire.
- Décomposer la série en composantes tendance, saisonnalité et résidus.
- Explorer les méthodes de prévision afin d'estimer les valeurs futures.

##  Présentation du jeu de données

**Nom du dataset :** AirPassengers

Le jeu de données AirPassengers contient le nombre mensuel de passagers du transport aérien international sur la période allant de janvier 1949 à décembre 1960.

| Caractéristique | Description |
|---|---|
| Période étudiée | 1949 – 1960 |
| Fréquence | Mensuelle |
| Nombre d'observations | 144 |
| Variable étudiée | Nombre de passagers |
| Unité | Milliers de passagers |

Ce dataset est couramment utilisé pour l'apprentissage et l'expérimentation des techniques d'analyse et de prévision des séries temporelles.

##  Technologies et bibliothèques utilisées

Le projet repose sur les outils et bibliothèques Python suivants :

- **Python :** langage de programmation.
- **Jupyter Notebook :** environnement de développement interactif.
- **Pandas :** manipulation et analyse des données.
- **NumPy :** calcul scientifique et opérations numériques.
- **Matplotlib :** création de visualisations graphiques.
- **Seaborn :** visualisation statistique.
- **Statsmodels :** analyse statistique et décomposition des séries temporelles.
- **Scikit-learn :** outils de machine learning (si utilisés).

##  Méthodologie et étapes de réalisation

Le projet est organisé autour des étapes suivantes :

### 1. Chargement et préparation des données

- Importation des bibliothèques nécessaires.
- Chargement du jeu de données AirPassengers.
- Conversion des dates au format datetime.
- Définition de la date comme index temporel.
- Vérification des valeurs manquantes et des types de données.

### 2. Analyse exploratoire des données (EDA)

- Exploration des premières et dernières observations.
- Analyse des statistiques descriptives.
- Visualisation de l'évolution du nombre de passagers.
- Identification des premières tendances et variations saisonnières.

### 3. Visualisation de la série temporelle

- Représentation graphique de la série originale.
- Analyse de l'évolution du trafic aérien.
- Observation des variations mensuelles et annuelles.
- Identification des éventuelles tendances et saisonnalités.

### 4. Décomposition de la série temporelle

La série temporelle est étudiée à travers ses trois principales composantes :

- **Tendance (Trend) :** évolution générale du nombre de passagers au cours du temps.
- **Saisonnalité (Seasonality) :** variations qui se répètent régulièrement, notamment chaque année.
- **Résidus (Residuals) :** variations restantes qui ne sont pas expliquées par la tendance et la saisonnalité.

### 5. Étude de la stationnarité

- Compréhension du concept de stationnarité.
- Analyse des caractéristiques statistiques de la série.
- Application du test de Dickey-Fuller augmenté (ADF), si utilisé.
- Exploration des transformations et différenciations pour rendre la série stationnaire.

### 6. Prévision des séries temporelles

Exploration des techniques de prévision permettant d'estimer l'évolution future du nombre de passagers à partir des observations historiques.

Les méthodes de prévision et les métriques d'évaluation dépendent des modèles effectivement implémentés dans le notebook.

## 📈 Principales observations

L'analyse du dataset AirPassengers permet notamment de constater :

- Une tendance générale à la hausse du nombre de passagers au fil des années.
- Une saisonnalité marquée avec des variations qui se répètent chaque année.
- Une augmentation de l'amplitude des fluctuations saisonnières lorsque le trafic aérien augmente.
- Une série temporelle présentant des caractéristiques de non-stationnarité.

Ces observations illustrent l'importance de l'analyse de la tendance et de la saisonnalité avant de construire un modèle de prévision.

##  Structure du projet

```text
time-series-analysis/
│
├── time_series_analysis.ipynb
│
├── data/
│   └── AirPassengers.csv
│
├── images/
│   └── visualisations.png
│
└── README.md
```

*La structure doit être adaptée aux fichiers réellement présents dans le repository.*

##  Installation et exécution du projet

### 1. Cloner le repository

```bash
git clone https://github.com/VOTRE_USERNAME/time-series-analysis.git
```

### 2. Accéder au dossier du projet

```bash
cd time-series-analysis
```

### 3. Installer les bibliothèques nécessaires

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn jupyter
```

### 4. Lancer Jupyter Notebook

```bash
jupyter notebook
```

### 5. Exécuter le notebook

Ouvrir le fichier `time_series_analysis.ipynb` et exécuter les cellules dans l'ordre pour reproduire l'analyse.

##  Compétences développées

À travers ce projet, les compétences suivantes sont mises en pratique :

- Programmation Python.
- Prétraitement et manipulation des données.
- Analyse exploratoire des données (EDA).
- Visualisation des données.
- Analyse des séries temporelles.
- Identification des tendances et de la saisonnalité.
- Analyse statistique.
- Décomposition des séries temporelles.
- Initiation aux techniques de prévision.



 Merci de consulter ce projet !
