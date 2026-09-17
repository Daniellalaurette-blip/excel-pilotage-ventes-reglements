# Pilotage des ventes & règlements clients --- Excel

## Présentation

Ce projet présente un outil Excel de **pilotage des ventes, règlements
et créances clients**, inspiré d'une mission réalisée dans le cadre de
mon expérience en contrôle de gestion chez Deviseo Fret.

Pour des raisons de confidentialité, **toutes les données présentées
dans ce projet sont fictives et anonymisées**. La base de démonstration
contient **1 000 transactions** afin d'illustrer le traitement d'un
volume important de données.

## Objectif du projet

L'objectif est de transformer une base de données transactionnelle brute
en un outil de pilotage fiable et exploitable.

Le projet permet notamment de :

-   structurer et fiabiliser les données ;
-   rapprocher les informations de facturation et de règlement ;
-   enrichir les données à l'aide d'un référentiel clients ;
-   automatiser le calcul des soldes et des statuts de paiement ;
-   identifier les impayés et règlements partiels ;
-   analyser les performances par période et par client ;
-   contrôler la qualité des données avant restitution ;
-   suivre l'ancienneté des créances ;
-   restituer les principaux indicateurs dans un dashboard.

## Démarche

Le projet suit une logique progressive :

**Base brute → Référentiel → Base fiabilisée → Reporting mensuel →
Analyse clients → Contrôles → Analyse technique → Dashboard → Balance
âgée**

### 1. Base brute

Point de départ du projet : données de facturation et de règlement
contenant notamment les références de factures, dates, clients, montants
facturés, montants encaissés, payeurs réels et dates de règlement.

### 2. Référentiel clients

Création d'un référentiel permettant d'enrichir automatiquement les
transactions avec des informations complémentaires telles que le
segment, la zone et le responsable.

### 3. Fiabilisation des données

Transformation de la base brute en base exploitable avec calcul et
contrôle automatiques de plusieurs éléments :

-   solde restant ;
-   statut de règlement ;
-   délai de paiement ;
-   identification des payeurs différents du client facturé ;
-   contrôles de cohérence ;
-   rapprochement avec le référentiel.

### 4. Reporting et analyses

Consolidation des données pour suivre les indicateurs par mois et par
client : facturation, encaissements, créances, taux d'encaissement,
impayés, règlements partiels et délais.

### 5. Contrôles

Mise en place de contrôles permettant d'identifier les anomalies ou
situations nécessitant une vérification avant diffusion du reporting.

### 6. Analyse technique

Analyse plus détaillée des écarts, des statuts de règlement et de
l'évolution des principaux indicateurs entre différentes périodes.

### 7. Dashboard final

Création d'une synthèse visuelle destinée au pilotage : montant facturé,
montant encaissé, créances, taux d'encaissement, volume de transactions
et principaux points de vigilance.

### 8. Balance âgée

Analyse de l'ancienneté des créances afin d'identifier les dossiers
nécessitant une attention ou une relance prioritaire.

## Compétences mises en pratique

-   Microsoft Excel
-   Nettoyage et fiabilisation de données
-   Consolidation de données
-   Rapprochement de bases
-   Formules conditionnelles
-   `SUMIFS` / `COUNTIFS`
-   `INDEX` / `MATCH`
-   Analyse des écarts
-   Construction de KPI
-   Reporting
-   Contrôle de gestion
-   Création de tableaux de bord
-   Analyse et aide à la décision

## À propos des données

Ce dépôt est un **projet de démonstration professionnelle**. Les noms,
transactions, montants et autres informations visibles dans le classeur
sont fictifs et ne correspondent pas aux données confidentielles de
Deviseo Fret ou de ses clients.

## Auteur

**Daniella Laurette Kenmeugne**\
Master Grande École --- spécialisation RH & Finance\
Intérêt : Contrôle de gestion • Data RH • Contrôle de gestion sociale •
Reporting
