# Nettoyage de Données et Fusion de Jeux de Données

## Table des Matières
- [Description](#description)
- [Contexte du Projet](#contexte-du-projet)
- [Jeux de Données](#jeux-de-données)
- [Installation et Prérequis](#installation-et-prérequis)
- [Utilisation](#utilisation)
- [Processus de Nettoyage et de Fusion](#processus-de-nettoyage-et-de-fusion)
- [Analyse Exploratoire](#analyse-exploratoire)
- [Licence](#licence)

## Description
Ce projet a pour objectif de transformer et fusionner deux jeux de données provenant de formats différents (JSON et CSV) pour obtenir un jeu de données final propre, cohérent et exploitable. Le processus inclut plusieurs étapes allant de l'importation initiale, à l'analyse préliminaire, au nettoyage des données, et enfin à la fusion des sources.

## Contexte du Projet
Dans le domaine de la gestion des données hospitalières, les informations sont souvent collectées sous différents formats et à partir de sources multiples. Ce projet a été réalisé dans le but de :
- Éliminer les incohérences entre les jeux de données.
- Corriger ou éliminer les valeurs manquantes et les erreurs de format.
- Fusionner les données en un seul jeu cohérent pour faciliter l'analyse et la prise de décision.

## Jeux de Données
Le repository contient les fichiers suivants :
- **hopital1.json** : Jeu de données au format JSON, comprenant diverses informations sur les patients (ex : âge, poids, taille, etc.).
- **hopital2.csv** : Jeu de données complémentaire au format CSV, contenant des informations qui viendront enrichir ou compléter celles du premier fichier.
- **atelier1.ipynb** : Notebook Jupyter qui détaille l'ensemble du processus de nettoyage, fusion et analyse des données.

## Installation et Prérequis
Pour reproduire ou exécuter ce projet, vous devez disposer des éléments suivants :
- **Python 3.x**  
- **Jupyter Notebook**

Les bibliothèques Python utilisées incluent principalement :
- **pandas**
- **numpy**
- **matplotlib** (pour la visualisation des résultats)

Pour installer ces dépendances, il est recommandé d’utiliser un environnement virtuel et d’exécuter la commande suivante dans le terminal :

```bash
pip install -r requirements.txt
