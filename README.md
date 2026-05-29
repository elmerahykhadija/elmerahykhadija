# 📊 Portfolio - Data Engineering & AI

Bienvenue dans mon portfolio ! Découvrez mes projets, compétences et réalisations dans le domaine du Data Engineering, Cloud Computing et Intelligence Artificielle.

---

## 👋 Me Présenter

### Qui suis-je ?

Je suis **Khadija El Merahy**, étudiant en 4e année d'Ingénierie à **l'ENSA Berrechid**, spécialisé en **Systèmes d'Information et Big Data**. 

Passionné par le **Data Engineering**, le **Cloud Computing** et l'**IA**, j'aime concevoir et déployer des **pipelines de données scalables** et des **systèmes de production robustes**.

### Expérience Professionnelle

**Data & AI Intern** | Residences Dar Saada | Juillet 2025
- Conception d'un **système multi-agent** pour l'analyse automatisée de données
- Développement de **dashboards BI alimentés par l'IA** pour la prise de décision
- **Technologies** : Python, MySQL, LLMs, Agno Framework, Power BI

---



# 🛠️ Technical Skills

## 📈 Data Engineering

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge\&logo=apacheairflow\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000000?style=for-the-badge\&logo=apachekafka\&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge\&logo=dbt\&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge\&logo=snowflake\&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-FFCC00?style=for-the-badge\&logo=apachehadoop\&logoColor=black)
![Prefect](https://img.shields.io/badge/Prefect-070E10?style=for-the-badge\&logo=prefect\&logoColor=white)

---

## ☁️ Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)

---

## 💻 Programming

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash_Scripting-121011?style=for-the-badge\&logo=gnubash\&logoColor=white)

---

## 🤖 AI & Machine Learning

![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge\&logo=mlflow\&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great%20Expectations-5A2CA0?style=for-the-badge\&logo=great-expectations\&logoColor=white)
![Evidently AI](https://img.shields.io/badge/Evidently%20AI-6C63FF?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LLMs](https://img.shields.io/badge/LLMs-AI-blueviolet?style=for-the-badge)

---

## 📊 Business Intelligence

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-4285F4?style=for-the-badge)


# 🚀 Mes Projets

# 1️⃣ 🎟️ End-to-End ELT Pipeline – Ticketmaster

## 📌 Vue d’ensemble

Pipeline ELT scalable end-to-end qui collecte et traite les données d’événements mondiaux provenant de la **Ticketmaster Discovery API** pour les années 2026–2027.

Architecture moderne combinant :

* orchestration avec **Apache Airflow**,
* ingestion temps réel avec **Apache Kafka**,
* stockage dans **Snowflake**,
* transformations analytiques avec **dbt**.

---

## 🏗️ Architecture Technique

### Flux de données

1. **Extraction** → Scripts Python collectent les données JSON depuis l’API Ticketmaster
2. **Streaming** → Apache Kafka assure le découplage entre producteurs et consommateurs
3. **Loading** → Kafka Consumer charge les données brutes dans Snowflake (`EVENTS_RAW`)
4. **Transformation** → dbt nettoie, transforme et modélise les données en Star Schema

---

## 🛠️ Stack Technologique

| Composant           | Technologie                |
| ------------------- | -------------------------- |
| Langage             | Python 3.12                |
| Orchestration       | Apache Airflow             |
| Message Broker      | Apache Kafka               |
| Data Warehouse      | Snowflake                  |
| Transformations     | dbt                        |
| Containerisation    | Docker & Docker Compose    |
| Cloud / Déploiement | AWS EC2                    |
| CI/CD               | GitHub Actions             |
| Source de données   | Ticketmaster Discovery API |

---

## 🖼️ Architecture

![Ticketmaster ELT Pipeline](./images/elt.png)

---

# 2️⃣ 🧠 Production-Ready MLOps Pipeline – HR Attrition Analytics

## 📌 Contexte

Le turnover des employés représente un enjeu majeur pour les entreprises.
Perdre des talents impacte directement :

* la productivité,
* les coûts de recrutement,
* et la stabilité des équipes.

L’objectif de ce projet est de passer d’une approche RH réactive → à une stratégie proactive basée sur les données.

---

## 🎯 Objectifs du Projet

Développement d’un pipeline MLOps complet permettant de :

* prédire les employés à risque de départ,
* automatiser le cycle de vie du Machine Learning,
* garantir la qualité des données,
* surveiller le data drift,
* simuler des stratégies RH grâce à des scénarios “what-if”.

---

## 📊 Dataset Utilisé

### IBM HR Analytics Attrition Dataset

* ~1400 employés
* Variables RH : satisfaction, revenu, overtime, déplacements, rôle, ancienneté, etc.

Source :
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

## ⚙️ Architecture MLOps
![MLOPS](./images/mlops.png)
### 1️⃣ Data Ingestion

* Chargement CSV → Snowflake RAW layer
* Validation et nettoyage initial des données

### 2️⃣ Data Transformation

* Pipeline dbt (approche ELT)
* Feature engineering
* Encodage et création des features analytiques
* Construction de la couche GOLD pour le ML

### 3️⃣ Data Quality

Mise en place de contrôles avec **Great Expectations** :

* valeurs manquantes,
* validation du schéma,
* contraintes métier,
* cohérence des variables encodées.

### 4️⃣ Data Drift Monitoring

Surveillance continue avec **Evidently AI** :

* comparaison entre données de référence et données courantes,
* détection des changements de distribution,
* déclenchement du retraining uniquement lorsque nécessaire.

### 5️⃣ ML Training & Registry

* Modèle : RandomForestClassifier
* Hyperparameter tuning avec GridSearchCV
* Optimisation du F1-score
* Tracking & Registry avec MLflow
* Promotion automatique du meilleur modèle

### 6️⃣ Orchestration

Automatisation complète avec **Prefect** :

* scheduling quotidien,
* retry logic,
* monitoring du pipeline.

---

## 🔄 Data Flow

```txt
CSV Data
   ↓
Snowflake RAW
   ↓
dbt Transformations (GOLD)
   ↓
Great Expectations
   ↓
Evidently AI Drift Detection
   ↓
ML Training (Scikit-learn + MLflow)
   ↓
Model Registry
   ↓
Dash Dashboard (HR Simulation)
```

---

## 📈 Résultats

* Pipeline ML entièrement automatisé
* Architecture orientée production
* Validation robuste des données
* Stratégie intelligente de retraining
* Dashboard RH interactif pour la simulation d’attrition
* Recommandations de rétention basées sur les données

---

## 💡 Ce que j’ai appris

* Conception d’architectures MLOps réelles
* Construction de pipelines ETL/ELT scalables
* Importance de la qualité des données en ML
* Monitoring et gestion du data drift
* Industrialisation des modèles ML
* Intégration du Data Engineering avec l’impact métier

---

# 3️⃣ 🛒 E-Commerce Data ETL Pipeline

## 📌 Objectif

Transformer des données transactionnelles e-commerce brutes (100k+ commandes) en datasets analytiques optimisés selon une architecture **Medallion (Bronze / Silver / Gold)**.

---

## 🛠️ Technologies & Rôles

| Technologie    | Rôle                       |
| -------------- | -------------------------- |
| Python         | Développement des jobs ETL |
| Apache Spark   | Traitement distribué       |
| Apache Airflow | Orchestration              |
| AWS S3         | Data Lake                  |
| Snowflake      | Data Warehouse             |
| Docker         | Containerisation           |

---

## 🖼️ Architecture

![E-Commerce ETL Medallion](./images/etl.png)

---

# 4️⃣ 🎯 Real-Time Streaming Pipeline – Annonces Marocaines

## 📌 Description

Application de collecte et traitement d’annonces en temps réel provenant de plusieurs plateformes marocaines :

* Avito
* MarocAnnonces

Les utilisateurs peuvent filtrer les annonces selon :

* le budget,
* la catégorie,
* la ville,

via une interface Streamlit interactive.

---

## 🛠️ Stack Technologique

| Composant         | Détails                  |
| ----------------- | ------------------------ |
| Langage           | Python 3.9+              |
| Message Broker    | Apache Kafka             |
| Stream Processing | Apache Spark 3.5         |
| Base de données   | MySQL 8                  |
| Scraping          | Requests + BeautifulSoup |
| Frontend          | Streamlit                |
| Environnement     | WSL Ubuntu               |
| Containerisation  | Docker                   |

---

## 🖼️ Architecture

![streaming](./images/streaming.png)

---

# 🎓 Formation & Certifications

## 🎓 Éducation

### ENSA Berrechid – Cycle Ingénieur

**Systèmes d’Information & Big Data** | 2022 – 2027

---

## 📜 Certifications

* Data Science & Machine Learning MasterClass – Udemy
* Introduction to Apache Airflow – DataCamp
* Introduction to dbt – DataCamp

---

# 🌍 Langues

* 🇬🇧 English : B2
* 🇫🇷 Français : B2
* 🇸🇦 Arabe : Natif
