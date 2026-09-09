# Documentation Technique

## Table des matières

1. [Aperçu du projet](#1-aperçu-du-projet)
   - 1.1 [Contexte du projet](#11-contexte-du-projet)
   - 1.2 [Objectifs](#12-objectifs)
2. [Exigences](#2-exigences)
   - 2.1 [Exigences fonctionnelles](#21-exigences-fonctionnelles)
   - 2.2 [Exigences non fonctionnelles](#22-exigences-non-fonctionnelles)
   - 2.3 [Utilisateurs et rôles](#23-utilisateurs-et-rôles)
3. [Cas d'utilisation](#3-cas-dutilisation)
   - 3.1 [Diagramme de cas d'utilisation](#31-diagramme-de-cas-dutilisation)
   - 3.2 [Description des cas d'utilisation](#32-description-des-cas-dutilisation)
4. [User Stories et Backlog](#4-user-stories-et-backlog)
   - 4.1 [User Stories](#41-user-stories)
   - 4.2 [Product Backlog](#42-product-backlog)
   - 4.3 [Planification des sprints](#43-planification-des-sprints)
5. [Conception du système](#5-conception-du-système)
   - 5.1 [Architecture](#51-architecture)
   - 5.2 [Conception de la base de données](#52-conception-de-la-base-de-données)
   - 5.3 [API](#53-api)
6. [Technologies](#6-technologies)
   - 6.1 [Frontend](#61-frontend)
   - 6.2 [Backend](#62-backend)
   - 6.3 [Base de données](#63-base-de-données)
7. [Tests](#7-tests)
   - 7.1 [Stratégie de test](#71-stratégie-de-test)
   - 7.2 [Tests](#72-tests)
8. [Déploiement](#8-déploiement)
9. [Améliorations futures](#9-améliorations-futures)

---

## 1. Aperçu du projet

### 1.1 Contexte du projet

Le club de parapente Parapente Pays de Sault (PPS), situé dans l'Aude, organisera à l'été 2027 le Championnat de France Pompiers de Parapente.
Actuellement, l'organisation de cette compétition repose principalement sur l'utilisation de documents papier et de fichiers Excel. Les informations et les résultats sont collectés et traités manuellement, notamment afin de réaliser les classements provisoires à la fin de chaque journée.
Afin de moderniser et de simplifier ce processus, le club souhaite mettre en place une solution numérique permettant de centraliser les différentes informations liées à la compétition et de faciliter leur gestion.

### 1.2 Objectifs

L'objectif du projet est de concevoir et de développer une application web dédiée à la gestion d'une compétition de parapente.
Cette application devra être accessible depuis différents types d'appareils, notamment les ordinateurs et les smartphones, afin de faciliter son utilisation par les organisateurs et les différents utilisateurs de la plateforme.
Les principales fonctionnalités envisagées concernent notamment la gestion des inscriptions, des participants, des différentes épreuves, des résultats et des classements. L'application devra également permettre de faciliter l'accès aux informations et, selon les besoins du client, de proposer une mise à jour des données en quasi temps réel.

---

## 2. Exigences

### 2.1 Exigences fonctionnelles

Les exigences fonctionnelles seront précisées et validées progressivement avec le client.
À ce stade, les principales fonctionnalités envisagées sont les suivantes :
Gestion des inscriptions des participants.
Gestion des participants.
Gestion de différentes épreuves.
Gestion et saisie des résultats.
Calcul et affichage des classements.
Mise à jour des informations et des classements en quasi temps réel.


### 2.2 Exigences non fonctionnelles

- **Multiplateforme** : l'application doit être disponible et pleinement fonctionnelle à la fois sur PC (web/desktop) et sur mobile (responsive ou application mobile dédiée).

Multiplateforme
L'application doit être accessible et pleinement fonctionnelle depuis un ordinateur et un smartphone.
L'interface devra s'adapter aux différents formats d'écran afin de garantir une utilisation confortable sur les différents appareils.
Ergonomie et simplicité d'utilisation
L'application devra être conçue de manière à être facilement utilisable par des personnes non informaticiennes.
Les différentes fonctionnalités devront être accessibles de manière claire et intuitive, sans nécessiter de connaissances techniques particulières.
Autres exigences
Les autres exigences non fonctionnelles, notamment concernant la sécurité, les performances, l'accessibilité et le déploiement, seront précisées avec le client au cours du projet.

### 2.3 Utilisateurs et rôles

*À compléter.*

---

## 3. Cas d'utilisation

### 3.1 Diagramme de cas d'utilisation

*À compléter.*

### 3.2 Description des cas d'utilisation

*À compléter.*

---

## 4. User Stories et Backlog

### 4.1 User Stories

*À compléter.*

### 4.2 Product Backlog

*À compléter.*

### 4.3 Planification des sprints

*À compléter.*

---

## 5. Conception du système

### 5.1 Architecture

*À compléter.*

### 5.2 Conception de la base de données

*À compléter.*

### 5.3 API

- **Format d'échange** : JSON, utilisé pour les échanges entre le frontend, le backend et la base de données.
- L'API est **auto-générée par Supabase** à partir du schéma PostgreSQL (pas de développement manuel d'API REST côté serveur).

*Détails supplémentaires (endpoints spécifiques, règles de sécurité/RLS, authentification, etc.) à compléter.*

---

## 6. Technologies

### 6.1 Frontend

- **Framework** : React (ou Node.js).
- **Style** : Tailwind CSS, pour un rendu responsive sur **PC** et **mobile**.
- **Librairie de bracket** : utilisation d'une librairie existante (ex. `@g-loot/react-tournament-brackets`) plutôt que du développement custom.

### 6.2 Backend

- **Supabase** : backend-as-a-service incluant base de données PostgreSQL, API auto-générée, authentification et temps réel.
- Expose une **API au format JSON** pour communiquer avec le frontend.

### 6.3 Base de données

- **PostgreSQL** (fourni par Supabase), avec échanges de données au **format JSON**.
- Fonctionnalités temps réel et authentification incluses nativement dans Supabase.

---

## 7. Tests

### 7.1 Stratégie de test

*À compléter.*

### 7.2 Tests

*À compléter.*

---

## 8. Déploiement

- **Frontend** : hébergé sur **Vercel** (gratuit).
- **Backend/Base de données** : hébergés sur **Supabase** (gratuit pour l'usage prévu).
- Les deux plateformes gèrent le déploiement continu à partir du dépôt de code source.

---

## 9. Améliorations futures

*À compléter.*
