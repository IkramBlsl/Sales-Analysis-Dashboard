# 📊 Sales Analysis Dashboard

## 🧾 Description

Ce tableau de bord Power BI fournit une analyse complète des ventes par pays, produit, période et métriques clés. Il permet aux utilisateurs de visualiser les performances commerciales globales et de prendre des décisions éclairées sur la stratégie de vente.

## 🗺 Données analysées

Les données proviennent de la feuille Sheet1 et incluent :

    Pays (Country) : Canada, France, Germany, India, Kenya, Mexico, United States

    Années (Year) : de 2018 à 2023

    Produits (Product) : Chocolate Chip, White Chocolate, Oatmeal Raisin, Snickerdoodle, Sugar, Fortune Cookie, Coffee

    Indicateurs :

        Revenue (Chiffre d'affaires)

        Profit (Bénéfice)

        Cost (Coût)

        Units Sold (Unités vendues)

        Population (Population associée à chaque pays)

        Date (année, mois)
        
        GP Margin (Marge brute)

        Définition :

    GP Margin = (Profit brut / Revenu total) × 100

### Remarques :

1 - GP Margin mesure la rentabilité d’un produit ou d’une entreprise avant les frais fixes, comme les salaires, loyers, etc.

Formule en détail :

GP Margin (%) = [(Revenue - Cost) / Revenue ] × 100

Revenue : chiffre d’affaires (ventes totales)

Cost : coût direct (ex : coût de fabrication ou d’achat)

Profit brut = Revenue - Cost

Exemple simple :

Produit	: A

Revenue (€)	: 1 000

Cost (€): 600

GP Margin (%) : (1000 - 600) / 1000 × 100 = 40%		

Cela veut dire que pour chaque euro gagné, 40 centimes restent comme profit brut avant les autres dépenses.

À quoi ça sert ?

    Comparer la rentabilité entre différents produits ou marchés

    Identifier les produits les plus profitables

    Suivre l’effet des promotions ou des baisses de coûts

2 - Dans le fichier sheet1 initial, il y a des colonnes vides qu'il faut supprimer avant d'appliquer les analyses

## 🔍 Fonctions principales
### 🧭 Filtres interactifs

    Pays : sélection multi-pays

    Année : sélection de l'année d'analyse

### 📈 KPI Cards (indicateurs clés)

    Revenue total

    Units vendues

    Coût total

    Profit total

### 📊 Visualisations

    Barres empilées : Somme des revenus par produit

    Carte du monde : Revenu par pays

    Camembert : Répartition des unités vendues par pays

    Histogramme : Revenu par mois

    Tableau : Détail des performances produit/pays
 
    Graphique horizontal : Profit par produit 

### Overview

![image](https://github.com/user-attachments/assets/946ecc8b-2710-4a36-b861-dab6995da761)
