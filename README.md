# Projet8-(Openclassrooms/CentraleSupelec)
Parcours Data Science

Projet n°8 : "Déployez un modèle dans le cloud"

## Description du projet

"Fruits!" une startup de l'AgriTech souhaite développer des robots ceuilleurs intelligents. Dans ce but une première étape de récolte des données est mise en place par le développement d'une application permettant aux utilisateurs de prendre ene photo un fruit et d'obtenir des informations à propos de celui-ci.

Source des données : https://www.kaggle.com/moltean/fruits

## Mission

Développer une première **chaîne de traitement des données (images)**, dans un environnement **Big Data**, qui comprendra le **preprocessing et la réduction de données**. Cette application utilisera le framework **PySpark** afin de préparer à l'augmentation rapide du volume de donnée qui se produira rapidement.

* Mise en place d'une infrastructure de prétraitement de données dans le cloud, en vue d'une augmentation du volume des données
* Configuration d'une instance **AWS EC2 (OS Ubuntu Server 18.04)**
* Réalisation de **scripts pyspark** et exécution dans le cloud
* Lecture et enregistrement de données sur **Amazon S3**
* Appel à la librairie MLLib pour approche **Transfer Learning** du prétraitement

## Compétences évaluées

* Identifier les outils du cloud permettant de mettre en place un environnement Big Data
* Paralléliser des opérations de calcul avec Pyspark
* Utiliser les outils du cloud pour manipuler des données dans un environnement Big Data

## Livrables

* Un [notebook sur le cloud](https://github.com/raissaSaleu/P8_MBIADOU_SALEU/blob/main/P8_notebook_cloud.ipynb) contenant les scripts en Pyspark exécutables (le preprocessing et une étape de réduction de dimension).
* Les [images du jeu de données initial](https://github.com/raissaSaleu/P8_MBIADOU_SALEU/blob/main/inputs.zip) ainsi que la [sortie de la réduction de dimension](https://github.com/raissaSaleu/P8_MBIADOU_SALEU/blob/main/results.csv) (une matrice écrite sur un fichier CSV ou autre) disponible dans un espace de stockage sur le cloud.
* Un [support de présentation](https://github.com/raissaSaleu/P8_MBIADOU_SALEU/blob/main/Soutenance%20Projet%208.pdf) pour la soutenance, présentant :
  - les différentes briques d'architecture choisies sur le cloud ;
  - leur rôle dans l’architecture Big Data ;
  - les étapes de la chaîne de traitement.
