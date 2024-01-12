# hello-DBMS
Ce projet vise à établir une corrélation entre le stockage de données, souvent appelé Big Data, et son impact sur l’environnement.

## Introduction

D’après les données recueillies par Statista, le volume de données numériques créées ou dupliquées à travers le monde a connu une augmentation spectaculaire, multipliée par 30 au cours de la dernière décennie, passant de 2 zettaoctets en 2010 à 64 zettaoctets l’année précédente.

Cependant, ce volume semble modeste par rapport aux prévisions pour les années à venir. Selon ces estimations, le volume de données produites mondialement devrait atteindre plus de 180 zettaoctets d’ici 2025, ce qui représente une croissance annuelle moyenne de près de 40% sur une période de cinq ans. 😊

### A. Qu’est ce qu’une donnée ? Sous quelle forme peut-elle se présenter ?

Une donnée est une représentation symbolique d’une information qui peut être manipulée par un ordinateur ou d’autres dispositifs. Les données peuvent se présenter sous diverses formes, y compris :
Données numériques : Ce sont des chiffres qui peuvent être utilisés dans des calculs. Par exemple, l’âge d’une personne, le nombre de ventes effectuées par une entreprise, etc.
Données textuelles : Il s’agit de mots, de phrases ou de textes. Par exemple, un livre, un article de blog, un tweet, etc.
Données d’image : Il s’agit de données visuelles sous forme d’images ou de photos.
Données audio : Il s’agit de sons, de voix ou de musique.
Données vidéo : Il s’agit de séquences d’images en mouvement, souvent accompagnées de son.
Données géographiques : Il s’agit de données liées à un emplacement ou à une position sur la Terre. Par exemple, les coordonnées GPS, les cartes, etc.

### B. Donnez et expliquez les critères de mesure de qualité des données.

La qualité des données peut être mesurée selon ces critères :
Exactitude : L’exactitude fait référence à la proximité des valeurs de données à leurs valeurs réelles. Des données inexactes peuvent conduire à des conclusions erronées.
Complétude : La complétude fait référence à l’absence de valeurs manquantes dans les données. Des données incomplètes peuvent biaiser les résultats de l’analyse.
Consistance : La consistance fait référence à l’absence de contradictions dans les données. Par exemple, une personne ne peut pas avoir deux âges différents dans deux enregistrements différents.
Pertinence : La pertinence fait référence à la mesure dans laquelle les données répondent aux besoins actuels de l’analyse. Des données non pertinentes peuvent détourner l’attention des informations importantes.
Fiabilité : La fiabilité fait référence à la mesure dans laquelle les données peuvent être vérifiées et validées. Des données non fiables peuvent semer le doute sur les résultats de l’analyse.
Actualité : L’actualité fait référence à la mesure dans laquelle les données sont à jour. Des données obsolètes peuvent ne pas refléter la situation actuelle.
Unicité : L’unicité fait référence à l’absence de doublons dans les données. Des données en double peuvent fausser les résultats de l’analyse.
Chaque critère aide à s’assurer que les données sont de haute qualité et utiles pour l’analyse.


### C. Définissez et comparez les notions de Data Lake, Data Warehouse et Lake
House. Illustrez les différences à l’aide de schémas.


Data Lake : Un Data Lake est un système de stockage qui peut accueillir une grande quantité de données brutes dans leur format natif pour une durée indéterminée. Il peut stocker tous les types de données générées par une entreprise, qu’elles soient structurées, semi-structurées ou non structurées12. Les données sont conservées sous leur forme la plus brute et ne sont ni traitées ni analysées1. Chaque élément de données d’un Lake se voit attribuer un identifiant unique et est marqué avec un ensemble de balises de métadonnées étendues1.
Data Warehouse34 : Un Data Warehouse est une base de données relationnelle hébergée sur un serveur dans un Data Center ou dans le Cloud4. Il recueille des données de sources variées et hétérogènes dans le but principal de soutenir l’analyse et faciliter le processus de prise de décision34. Les données stockées dans un Data Warehouse sont généralement structurées et proviennent principalement de traitement transactionnel en ligne (OLTP).
Lake House56 : Un Lake House est un nouveau paradigme qui combine les meilleurs éléments des Data Lakes et des Data Warehouses56. Il repose sur une nouvelle conception de système qui permet d’effectuer des analyses de Business Intelligence et de Machine Learning sur toutes les données. Il offre la flexibilité d’un Data Lake pour le stockage de données brutes à grande échelle, tout en permettant des requêtes SQL et des transactions comme un Data Warehouse.




### D. Donnez une définition et des exemples de systèmes de gestion de bases de
données avec des illustrations.
Les systèmes de gestion de base de données ont un acronyme, les SGBD.Les SGBD  sont des logiciels qui permettent de créer et de gérer des bases de données. Ils fournissent une interface entre les utilisateurs finaux et les bases de données elles-mêmes, garantissant que les données sont organisées de manière efficace et sont facilement accessibles.


### E. Qu’est ce qu’une base de données relationnelle ? Qu’est ce qu’une base de données non relationnelle ? Donnez la différence entre les deux avec des
exemples d’applications.
Les bases de données relationnelles organisent les données en tables avec des lignes et des colonnes. Chaque ligne représente un enregistrement et chaque colonne représente un champ. Cette structure permet de faire des requêtes et de manipuler les données facilement grâce au langage de requête structuré (SQL).Elles sont souvent utilisées dans des domaines tels que la finance et le commerce de détail pour stocker, assurer et fiabiliser leurs transactions.
D’un autre côté, une base de données non relationnelle, également connue sous le nom de base de données NoSQL, est un type de base de données qui n’utilise pas la structure relationnelle traditionnelle basée sur des tables. Au lieu de cela, les bases de données non relationnelles utilisent divers modèles de données, tels que clé-valeur, document, famille de colonnes et graphiques. Elles sont souvent utilisées par des entreprises qui ont besoin de stocker de grandes quantités de données diversifiées, comme Twitter ou Facebook, qui stockent chaque jour plusieurs téraoctets de données.


### F. Définissez les notions de clé étrangère et clé primaire.
Une clé unique est un identifiant unique pour chaque enregistrement de la table. Une clé étrangère fait référence à un identifiant unique d’une autre table.G. Quelles sont les propriétés ACID ?



Les propriétés ACID sont un ensemble de propriétés qui garantissent qu’une transaction dans un système de gestion de base de données est traitée de manière fiable. L’acronyme ACID signifie Atomicité, Cohérence, Isolation et Durabilité.
Atomicité : C’est comme un tout ou rien. Si une partie de la tâche échoue, tout échoue et rien ne change.
Cohérence : Les données sont cohérentes avant et après une tâche. Toutes les règles doivent être respectées.
Isolation : Même si plusieurs tâches se déroulent en même temps, chacune est traitée comme si elle était seule.
Durabilité : Une fois la tâche terminée, tout ce qui a été fait reste, même si le système tombe en panne.


### H. Définissez les méthodes Merise et UML. Quelles sont leur utilité dans le monde de l’informatique ? Donnez des cas précis d’utilisation avec des schémas.


Merise est une méthode d’analyse et de conception de projet informatique, utilisée pour l’informatisation des organisations. UML (Unified Modeling Language) est un langage de modélisation standardisé utilisé en génie logiciel pour visualiser, spécifier, construire et documenter un système. Ces deux méthodes aident à structurer et à planifier les projets informatiques.


### I. Définissez le langage SQL. Donnez les commandes les plus utilisées de ce langage et les différentes jointures qu’il est possible de faire. 
SQL (Structured Query Language) est un langage informatique normalisé servant à exploiter des bases de données relationnelles1. Il permet de rechercher, d’ajouter, de modifier ou de supprimer des données dans les bases de données relationnelles.


Les commandes les plus utilisés en sql sont : CREATE : Crée une nouvelle table, une vue ou une base de données.
ALTER : Modifie la structure d’une table existante.
DROP : Supprime une table, une vue ou une base de données.
INDEX : Créer un index sur une ou plusieurs colonnes d’une table
SELECT : Récupère des données dans une table.
INSERT : Insère des données dans une table.
UPDATE : Met à jour des données dans une table.	
DELETE : Supprime des données dans une table.
