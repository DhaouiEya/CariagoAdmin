# Cariago Admin

## Description
**Cariago** est une plateforme de mise en relation entre **locataires** et **propriétaires de véhicules**.  
Le module **Cariago Admin** est une application web conçue pour les administrateurs afin d’assurer une **gestion centralisée, sécurisée et performante** de la plateforme.  
Elle permet d’analyser, contrôler et superviser l’ensemble des données (utilisateurs, véhicules, réservations, contenu, etc.) à travers une interface moderne, intuitive et riche en fonctionnalités.

## Fonctionnalités principales

### 1. Dashboard
- Analyse et aide à la prise de décision via des **courbes (KPI)** et des **graphiques interactifs** (Angular Charts).  
- **Suivi en temps réel** des activités de la plateforme.  
- Téléchargement des graphiques en **PNG, SVG, CSV**.  

### 2. Gestion des administrateurs
- Tableau détaillé des administrateurs avec **CRUD (Create, Read , Update, Deactivate)**.  
- **Recherche, tri, export Excel**.  
- Possibilité de **désactiver un compte admin**.  

### 3. Gestion des véhicules
- Ajout et modification via un **wizard en 5 étapes**.  
- Gestion de la disponibilité et des statuts d’approbation.  
- **Filtres dynamiques** (disponibilité, approbation), tri et recherche.  
- Gestion des **avis utilisateurs** pour chaque véhicule.  
- Affichage et modification du **calendrier de disponibilité**.  
- Exportation des données en **Excel**.  

### 4. Gestion des marques & modèles
- Ajout et modification des marques et modèles.  
- **Recherche, tri, désactivation**.  
- Exportation des données en **Excel**.  

### 5. Gestion des clients
- Ajout et modification des informations client.  
- Affichage détaillé (profil, réservations, etc.).  
- **Tri, recherche, filtres** (par rôle et statut d’approbation).  
- Gestion des rôles, approbations et désactivation.  
- Exportation des données en **Excel**.  

### 6. Gestion des hôtes
- Ajout et modification des hôtes.  
- **Tri, recherche, filtres** (statut d’approbation).  
- Gestion des commentaires liés aux hôtes.  
- Approbation ou désactivation des comptes hôtes.  
- Exportation des données en **Excel**.  

### 7. Gestion du contenu
- Gestion de la page d’accueil via une interface en **accordéon**.  

### 8. Gestion des réservations
- Tableau détaillé des réservations avec affichage des informations du véhicule, du client et de l’hôte.  
- Gestion des **statuts de réservation** (pending, confirmed, canceled, completed) et des **statuts de paiement** (paid, unpaid).  
- **Recherche, tri, filtres**, exportation en Excel.  
- **Envoi automatique d’e-mails** liés aux réservations.  
- Génération de **factures professionnelles** téléchargeables en **PDF**.  

## Stack technique
- **Frontend** : Angular + Bootstrap + bibliothèques Angular (Charts, etc.)  
- **Backend** : Node.js / Express  
- **Database** : MongoDB  
