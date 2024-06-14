# Segmentation Clients Olist

## Description

Ce projet utilise des techniques de clustering non supervisé pour segmenter les clients d'une plateforme e-commerce en appliquant la méthode RFM (Récence, Fréquence, Montant).

## Techniques Utilisées

- **Transformation des Variables Catégorielles** :
  - OneHotEncoder
  - TargetEncoder

- **Création de Nouvelles Variables** :
  - Feature engineering à partir de données existantes
  - Intégration de nouvelles variables

- **Transformations Mathématiques** :
  - Ajustement des distributions des variables

- **Normalisation des Variables** :
  - StandardScaler
  - MinMaxScaler

- **Clustering Non Supervisé** :
  - K-Means
  - DBSCAN

- **Évaluation des Modèles** :
  - Coefficient de silhouette
  - Méthode du coude (Elbow Method)
  - Analyse de la forme et stabilité des clusters

- **Optimisation des Hyperparamètres** :
  - GridSearchCV

- **Maintenance de la Segmentation** :
  - Stratégie de mise à jour régulière


