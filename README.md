# Student Management API - Spring Boot

![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)
![Licence](https://img.shields.io/badge/License-MIT-green)

---

# 📖 Plan

[📝 Objectif](#-objectif)  
[📚 Contexte](#-contexte)  
[🏗 Structure du projet](#-structure-du-projet)  
[⚙️ Configuration de la base de données](#️-configuration-de-la-base-de-données)  
[💻 Explication des composants](#-explication-des-composants)  
[🚀 Lancer l'application](#-lancer-lapplication)  
[🌐 Endpoints REST](#-endpoints-rest)  
[🧪 Tests unitaires](#-tests-unitaires)  
[📄 Documentation API avec Swagger](#-documentation-api-avec-swagger)  
[💡 Concepts clés](#-concepts-clés)  

---

# 📝 Objectif

Ce TP a pour objectif de développer une **API REST complète avec Spring Boot** permettant de gérer des étudiants.

Les objectifs pédagogiques sont :

- Comprendre la structure d’un **projet Spring Boot**
- Configurer **Spring Data JPA avec MySQL**
- Créer une **API REST**
- Implémenter les opérations **CRUD**
- Ajouter des **tests unitaires avec JUnit et Mockito**
- Documenter l’API avec **Swagger**

---

# 📚 Contexte

L'application permet de gérer des étudiants à travers une **architecture en couches** :

- **Entity** → représente les données stockées en base  
- **Repository** → accès aux données via Spring Data JPA  
- **Service** → logique métier  
- **Controller REST** → expose les endpoints HTTP  

Technologies utilisées :

- **Spring Boot**
- **Spring Data JPA**
- **MySQL**
- **JUnit 5**
- **Mockito**
- **Swagger (springdoc-openapi)**

  
Cette structure suit l’architecture **MVC adaptée aux API REST**.

---

# ⚙️ Configuration de la base de données

Cration d'une base MySQL :

<img width="759" height="208" alt="image" src="https://github.com/user-attachments/assets/aa432efd-c306-423b-8f60-fdbab76cdd14" />

---

# 🏗 Structure du projet


<img width="438" height="464" alt="image" src="https://github.com/user-attachments/assets/cf6100db-f6df-4808-be82-827f92a6b3f7" />


## StudentController Resultat:



<img width="893" height="327" alt="image" src="https://github.com/user-attachments/assets/170f54bd-30aa-4361-9386-05f1c03c8045" />

## Exécution de l’application:


<img width="905" height="428" alt="image" src="https://github.com/user-attachments/assets/051241c7-995d-4611-a9bb-eb174858a407" />

## Teste les endpoints REST:


### TEST methode POST:


<img width="527" height="378" alt="image" src="https://github.com/user-attachments/assets/aff58851-970a-4799-afd9-c10986057232" />


<img width="523" height="410" alt="image" src="https://github.com/user-attachments/assets/69f6cb19-e44e-404d-91c0-199dbcc23d07" />

<img width="738" height="401" alt="image" src="https://github.com/user-attachments/assets/3336ccf4-3b37-4886-8d77-adcf1a24c8f4" />










