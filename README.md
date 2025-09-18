# 🏊 CiblOrgaSport – Championnats d’Europe de Natation 2026

CiblOrgaSport est une application de gestion des **Championnats d’Europe de Natation – Paris 2026**.  
Elle permet de centraliser la gestion des compétitions, des athlètes, des commissaires, des volontaires et des spectateurs, à travers un **back-office sécurisé** et un **front moderne** accessible en web et mobile.

---

##  Fonctionnalités principales

- **Athlètes** : inscription, consultation des épreuves, suivi des performances, notifications.
- **Volontaires** : accès à leur planning, notifications des incidents.
- **Commissaires** : gestion des résultats, arbitrage, publication des classements.
- **Spectateurs** : achat de billets, accès aux programmes, résultats et alertes.
- **Organisateurs** : supervision en temps réel, suivi des statistiques (KPI).

---

##  Technologies utilisées

### Backend
- [Spring Boot](https://spring.io/projects/spring-boot) – API REST
- [Spring Security](https://spring.io/projects/spring-security) – Authentification & rôles
- [Spring Data JPA / Hibernate](https://spring.io/projects/spring-data-jpa) – ORM
- [PostgreSQL](https://www.postgresql.org/) – Base de données
- [Gradle](https://gradle.org/) – Gestion des dépendances
- [JUnit / Mockito](https://junit.org/) – Tests unitaires

### Frontend
- [React.js](https://react.dev/) – Interface utilisateur
- [Vite](https://vitejs.dev/) – Build et Dev Server rapide
- [Axios](https://axios-http.com/) – Requêtes HTTP
- [Nginx](https://www.nginx.com/) – Serveur web

### DevOps & Qualité
- [Docker](https://www.docker.com/) / [Docker Compose](https://docs.docker.com/compose/) – Conteneurisation
- [GitHub Actions](https://github.com/features/actions) – CI/CD

---

## Installation et exécution

### 1. Prérequis
- [Docker](https://docs.docker.com/get-docker/) 
- [Docker Compose](https://docs.docker.com/compose/install/) 
- Accès au repo `backend/` et `frontend/`

### 2. Cloner le projet
```git clone https://github.com/votre-org/ciblor-sport.git
cd ciblor-sport
3. Lancer avec Docker Compose

Copier le code
docker-compose up --build -d```
4. Accéder aux services

Frontend React : http://localhost:3000

Backend Spring Boot : http://localhost:8080

Base PostgreSQL : port 5432

4. Accéder aux services

Frontend React : http://localhost:3000

Backend Spring Boot : http://localhost:8080

Base PostgreSQL : port 5432