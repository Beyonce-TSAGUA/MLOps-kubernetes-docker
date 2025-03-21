Projet : Déploiement d'une Application Web avec Base de Données sur un Cluster Kubernetes

## 📖 Contexte
Dans un environnement de développement moderne, la conteneurisation et l'orchestration sont devenues indispensables pour assurer la flexibilité, 
la scalabilité et la portabilité des applications. Ce projet a pour objectif de déployer une application web interconnectée à une base de données sur un cluster Kubernetes,
tout en respectant les bonnes pratiques de sécurité et de persistance des données.

## 🎯 Objectifs du Projet
- **Déployer la Base de Données (PostgreSQL ou MySQL)** :
  - Création d’un Pod pour la base de données.
  - Gestion des paramètres sensibles via **Secrets** et **ConfigMaps**.
  - Mise en place d’un **volume persistant (PVC)** pour assurer la durabilité des données.

- **Déployer l’Application Web (Node.js ou Django)** :
  - Conteneurisation de l’application via **Docker**.
  - Déploiement dans un Pod Kubernetes.
  - Configuration des variables d’environnement nécessaires à la connexion à la base de données.

- **Interconnexion des services** :
  - Création d’un **Service de type ClusterIP** pour la base de données.
  - Mise en place de la connexion interne entre l’application et la base de données.

- **Exposition de l’Application Web** :
  - Utilisation d’un **Service de type NodePort ou LoadBalancer** pour rendre l’application accessible depuis l’extérieur du cluster.
  - Mise en place des règles de routage et de sécurité.

---

## 🗂️ Livrables
### ✅ Fichiers de Configuration Kubernetes (YAML)
- `deployment-db.yaml` : Déploiement de la base de données.
- `deployment-web.yaml` : Déploiement de l’application web.
- `service-db.yaml` : Service interne (ClusterIP) pour la base de données.
- `service-web.yaml` : Service externe (NodePort ou LoadBalancer) pour l’application.

### ✅ Documentation
- **Guide d'installation et de déploiement** : étapes complètes pour la mise en place de l’environnement.
- **Détails de configuration** : description des variables, Secrets et ConfigMaps.
- **Guide de maintenance et d’adaptation** pour d'autres environnements.

### ✅ Code Source et Scripts
- **Application Web (Node.js ou Django)**.
- **Dockerfile** pour la création de l’image de l’application.
- Scripts d’initialisation de la base de données si nécessaire.

---

## 🛠️ Étapes du Projet
### 🔎 Phase de Préparation
- Définition de l’architecture et des ressources nécessaires.
- Rédaction des Dockerfiles et configuration de l’environnement.

### 💻 Phase de Développement
- Développement et test de l’application web.
- Création et test des images Docker.

### 🚀 Phase de Déploiement
- Rédaction et application des fichiers YAML (Pods, Services, ConfigMaps, Secrets, PVC).
- Lancement des déploiements Kubernetes.

### ✅ Phase de Validation et Test
- Vérification de l’accessibilité de l’application depuis l’extérieur.
- Test des fonctionnalités et de la connexion à la base de données.
- Tests de résilience (redémarrage des Pods).

### 📝 Phase de Documentation et Livraison
- Rédaction finale de la documentation.
- Livraison des fichiers YAML et du code source.

---

## 🧠 Compétences Développées
- Maîtrise de **Docker** et de la conteneurisation.
- Compréhension et utilisation avancée de **Kubernetes**.
- Gestion sécurisée des informations sensibles avec **Secrets et ConfigMaps**.
- Mise en place de la **persistance des données** avec PVC.
- Déploiement d’applications **scalables et résilientes**.

---

## 📌 Conclusion
Ce projet représente un cas pratique complet d’orchestration d’une architecture **web + base de données** sur Kubernetes. Il permettra de renforcer vos compétences en **DevOps**, en **sécurité des déploiements**, ainsi qu’en **gestion de la persistance des données** dans un environnement cloud-native.

---

## 📚 Auteurs
- Beyonce TSAGUA - Étudiant en Big data et IA 
