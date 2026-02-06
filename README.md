# 🔐 Machine Learning Distribué pour la Détection d’Intrusions avec Apache Spark

## 📌 Présentation du Projet

Ce projet s’inscrit dans le cadre de l’apprentissage du **Machine Learning distribué** en utilisant **Apache Spark** pour l’analyse de **données réseau massives** dans un contexte de **cybersécurité**.

L’objectif principal est de **mettre en œuvre et comparer deux algorithmes de clustering non supervisé** :

- **K-Means** (Spark MLlib)
- **DBSCAN** (implémentation personnalisée)

Le projet exploite le **dataset KDD Cup 99**, largement utilisé dans le domaine de la **détection d’intrusions réseau (IDS)**, stocké et traité sur **HDFS**.

---

## 🎯 Objectifs du Projet

- Manipuler des **données volumineuses** avec **HDFS**
- Réaliser l’**ingestion, le nettoyage et le prétraitement** des données avec Apache Spark
- Effectuer du **Feature Engineering** via les pipelines Spark ML
- Appliquer des **algorithmes de clustering non supervisé**
- Comparer **K-Means et DBSCAN** en termes de :
  - Principe de fonctionnement
  - Performances et scalabilité
  - Robustesse face au bruit et aux outliers
  - Résultats obtenus

---

## 🏗️ Architecture & Technologies

- **Framework Big Data :** Apache Spark (mode YARN)
- **Stockage :** HDFS
- **Langage :** Scala
- **Machine Learning :** Spark MLlib
- **Dataset :** KDD Cup 99
- **Formats de sortie :** Parquet, CSV

---

## 📂 Structure du Projet

```bash
.
├── 01_ingest_kdd.scala          # Ingestion et nettoyage des données
├── 02_features_kdd.scala        # Feature Engineering & pipeline ML
├── 03_kmeans_kdd.scala          # Clustering K-Means
├── 04_dbscan_sample_kdd.scala   # DBSCAN (implémentation personnalisée)
└── README.md
