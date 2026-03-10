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



## Exécution de l’application:


<img width="905" height="428" alt="image" src="https://github.com/user-attachments/assets/051241c7-995d-4611-a9bb-eb174858a407" />

## Test les endpoints REST:


### TEST methode POST:


<img width="527" height="378" alt="image" src="https://github.com/user-attachments/assets/aff58851-970a-4799-afd9-c10986057232" />


<img width="523" height="410" alt="image" src="https://github.com/user-attachments/assets/69f6cb19-e44e-404d-91c0-199dbcc23d07" />

<img width="738" height="401" alt="image" src="https://github.com/user-attachments/assets/3336ccf4-3b37-4886-8d77-adcf1a24c8f4" />


### TEST methode GET:

<img width="509" height="437" alt="image" src="https://github.com/user-attachments/assets/d8ba1e14-db72-4532-928a-07ccbf4e54d8" />


<img width="514" height="415" alt="image" src="https://github.com/user-attachments/assets/c3b3ec23-5c79-4997-a9a9-a98f6daddec2" />

<img width="535" height="216" alt="image" src="https://github.com/user-attachments/assets/911287d6-354f-436b-a779-bcef9d50640d" />


<img width="518" height="441" alt="image" src="https://github.com/user-attachments/assets/05331387-8699-44c4-a2e3-9af5f5f464d5" />

### TEST methode DELETE:

On a supprimer students ayant id=1

<img width="532" height="211" alt="image" src="https://github.com/user-attachments/assets/c9157045-060b-4d38-9e4e-57be492c30de" />


<img width="780" height="372" alt="image" src="https://github.com/user-attachments/assets/e63d132b-f162-479c-85b1-33c64f2bb46f" />


## StudentController Resultat:

<img width="893" height="327" alt="image" src="https://github.com/user-attachments/assets/170f54bd-30aa-4361-9386-05f1c03c8045" />

 ## Accé à l’interface Swagger:

 <img width="959" height="465" alt="image" src="https://github.com/user-attachments/assets/36bd3a32-ca3f-4770-b74e-65d2b783215c" />
 

<img width="958" height="400" alt="image" src="https://github.com/user-attachments/assets/4f8744d0-4728-4948-9cb5-99a3abde7720" />


## Test dans Swagger UI:

### TEST methode GET ALL:



https://github.com/user-attachments/assets/7589adaa-f7ba-43e7-8884-8e8de3ccbe7e



### TEST methode GET COUNT:


https://github.com/user-attachments/assets/f65ab0d4-8d76-4bc4-8c65-8d0b47870803


### TEST methode BY YEAR:


https://github.com/user-attachments/assets/09caa398-f364-4257-9b9a-2b71a43906fd


### TEST methode DELETE:

On a supprimer student:

       id=6
    "nom": "EL AMRANI",
    "prenom": "Youssef",
    "dateNaissance": "1990-03-12"

  


https://github.com/user-attachments/assets/b7145373-c6b9-45a7-9cff-4a3049678e0b




### TEST methode POST SAVE:


https://github.com/user-attachments/assets/a141d0f7-c202-4fbc-b615-bbd4430823a9








