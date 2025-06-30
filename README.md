# 📘 MicroService-SGSE

Projet de fin de module Spring Boot – Microservices  
**Sujet :** Gestion des Stagiaires avec Architecture Microservices

---

## 👤 Réalisé par

- **Nom :** Souleymane BORE
- **Date de livraison :** 30/06/2025

---

## 🏗️ Architecture des Services

| Service              | Port   | Image Docker                         | Description                            |
|----------------------|--------|--------------------------------------|----------------------------------------|
| **MySQL**            | `3308` | `mysql:8.0`                          | Base de données relationnelle          |
| **Eureka Server**    | `8762` | `leweeskys/eureka-server`            | Service de découverte (naming server)  |
| **API Gateway**      | `9090` | `leweeskys/api-gateway`              | Point d’entrée des microservices       |
| **Stagiaire Service**| `9091` | `leweeskys/stagiaire-service`        | Microservice CRUD pour les stagiaires  |
| **Encadreur Service**| `9092` | `leweeskys/encadreur-service`        | Microservice CRUD pour les encadreurs  |

---

## 📦 Prérequis

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

---

## ▶️ Lancement du projet

### 1. 🔁 Clonage du projet

```bash
git clone <url-du-repo>
cd microservice


