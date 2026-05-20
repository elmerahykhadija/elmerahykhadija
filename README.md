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



### 📈 Data Engineering
```
Apache Airflow • Apache Spark • Apache Kafka • dbt • Snowflake • RabbitMQ 
Hadoop • Prefect • ETL/ELT Pipelines • Data Modeling • Star Schema
```

### ☁️ Cloud & Infrastructure
```
AWS (S3, EC2) • Docker • Docker Compose • CI/CD • GitHub Actions • Linux • Bash
```

### 💻 Programmation
```
Python (Expert) • SQL (Avancé) • Java (Algorithmes) • Git • Bash Scripting
```

### 🤖 AI & Machine Learning
```
Scikit-learn • LLMs • LangChain • MLflow • Agentic AI • Multi-Agent Systems
```

### 📊 Business Intelligence
```
Power BI • Data Visualization • Analytics • Reporting • Snowflake Analytics
```

---

## 🚀 Mes Projets

### 1️⃣ 🎟️ End-to-End ELT Pipeline - Ticketmaster

#### 📌 Vue d'ensemble
Pipeline ELT scalable end-to-end qui collecte et traite les données d'événements mondiaux de la **Ticketmaster Discovery API** pour les années 2026–2027.

Architecture moderne combinant **orchestration Airflow**, **ingestion asynchrone RabbitMQ**, **stockage Snowflake** et **transformations dbt**.

#### 🏗️ Architecture Technique

**Flux de données :**
1. **Extraction** → Scripts Python collectent les données JSON de l'API Ticketmaster
2. **Transit** → Files d'attente RabbitMQ pour découpler extraction et ingestion
3. **Loading** → Consumer insère les données brutes dans `EVENTS_RAW` (Snowflake)
4. **Transformation** → dbt nettoie et modélise en Star Schema

#### 🛠️ Stack Technologique

| Composant | Technologie |
|-----------|------------|
| **Langage** | Python 3.12 |
| **Orchestration** | Apache Airflow |
| **Message Broker** | RabbitMQ |
| **Data Warehouse** | Snowflake |
| **Transformations** | dbt (Data Build Tool) |
| **Containerisation** | Docker & Docker Compose |
| **Cloud/Déploiement** | AWS EC2 |
| **CI/CD** | GitHub Actions |
| **Source Données** | Ticketmaster Discovery API |

#### �️ Architecture

![Ticketmaster ELT Pipeline](./images/elt.png)  

---

### 2️⃣ 🛒 E-Commerce Data ETL Pipeline

#### 📌 Objectif
Transformer les données transactionnelles d'e-commerce brutes (100k+ commandes) en datasets analytiques optimisés selon l'architecture **Medallion (Bronze/Silver/Gold)**.

#### 🛠️ Technologies & Rôles

| Technologie | Rôle |
|-------------|------|
| **Python** | Développement des jobs ETL |
| **Apache Spark** | Processing distribué et transformations big data |
| **Apache Airflow** | Orchestration et planification des tâches |
| **AWS S3** | Data Lake (stockage des couches raw, silver, gold) |
| **Snowflake** | Data Warehouse pour les analyses BI |
| **Docker** | Conteneurisation de l'infrastructure |

#### 🖼️ Architecture

![E-Commerce ETL Medallion](./images/etl.png)

---

### 3️⃣ 🎯 Projet Annonces - Real-Time Streaming Pipeline

####  Description
Application de **collecte et traitement d'annonces en temps réel** provenant de plusieurs plateformes marocaines (**Avito**, **MarocAnnonces**).

Les utilisateurs peuvent **filtrer les offres** selon le budget, la catégorie et la ville via une interface **Streamlit** intuitive.


#### 🛠️ Stack Technologique

| Composant | Détails |
|-----------|---------|
| **Langage** | Python 3.9+ |
| **Message Broker** | Apache Kafka |
| **Stream Processing** | Apache Spark 3.5.0 |
| **Base Données** | MySQL 8.0 (Port 3307) |
| **Scraping** | Requests + BeautifulSoup4 |
| **Frontend** | Streamlit |
| **Environnement** | WSL Ubuntu |
| **Conteneurisation** | Docker |

![streaming](./images/streaming.png)
## 🎓 Formation & Certifications

### Éducation

**ENSA Berrechid** – Cycle Ingénieur, Systèmes d'Information et Big Data | 2022 – 2027
- École Nationale des Sciences Appliquées

### Certifications

- 🎓 Data Science & ML MasterClass (Udemy)
- 🎓 Introduction to Apache Airflow (DataCamp)
- 🎓 Introduction to dbt (DataCamp)

### Langues

- 🇬🇧 **English** : B2
- 🇫🇷 **Français** : B2
- 🇸🇦 **Arabe** : Natif

