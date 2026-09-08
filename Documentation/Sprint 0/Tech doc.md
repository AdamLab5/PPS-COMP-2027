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

*À compléter.*

### 1.2 Objectifs

*À compléter.*

---

## 2. Exigences

### 2.1 Exigences fonctionnelles

*À compléter.*

### 2.2 Exigences non fonctionnelles

- **Multiplateforme** : l'application doit être disponible et pleinement fonctionnelle à la fois sur PC (web/desktop) et sur mobile (responsive ou application mobile dédiée).

*Autres exigences à compléter.*

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

- **Framework** : React (ou Next.js).
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
