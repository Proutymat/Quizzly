# Projet de Programmation : Quizzly

Quizzly est un projet universitaire réalisé dans le cadre du second semestre de L2 par une équipe de 4 personnes.

## Objectifs
Le but de ce projet était de développer une application web permettant à des enseignants d'identifier et de proposer des énoncés d'exercices en informatique. 
Contrairement aux nombreux sites proposant des exercices de mathématiques, il existe peu de ressources pour des exercices en informatique.

## Technologies utilisées
Ce projet est divisé en deux parties ;

- Le back-end est codé en python et utilise le micro-framework [flask](https://github.com/pallets/flask).
- Le front-end est codé en Javascript et utilise le framework [Vue.js](https://github.com/vuejs/vue).

Le projet sauvegarde ses données dans un fichier local .db et y accède via l'API sqlite3 de python

## Durée de réalisation

| Numéro de la partie réalisée | Temps de réalisation  | Lien du sujet                                                      |
|:-----------------------------|-----------------------|--------------------------------------------------------------------|
| Première partie              | Une semaine           | [Lien du sujet de la première partie](./Sujets/Sujet_Phase_1.pdf)  |
| Seconde partie               | Six semaines          | [Lien du sujet de la seconde partie](./Sujets/Sujet_Phase_2.pdf)   |
| Troisième partie             | Une semaine           | [Lien du sujet de la troisième partie](./Sujets/Sujet_Phase_3.pdf) |

## Fonctionnalités
- Ajout de questions fermés avec des propositions de réponses, possibilité de spécifier les réponses correctes.
- Ajout de questions ouverte avec un affichage des réponses en nuage de mot.
- Création d'énoncés d'exercices en informatique avec possibilité d'utiliser du markdown, du code, du LaTeX et des graphs mermaid.
- Attribution d'étiquettes pour chaque question pour faciliter l'organisation et la recherche des énoncés.
- Regroupement des questions en séquences.
- Gestion de comptes utilisateurs pour les enseignants et les étudiants, y compris la possibilité pour les enseignants de créer des comptes étudiants à partir d'un fichier CSV.
- Authentification des utilisateurs et possibilité de modifier leurs profils des étudiants.
- Diffusion de questions et de séquences en direct pour que les étudiants puissent y répondre en temps réel en utilisant un code d'accès.
- Enregistrement des réponses des étudiants et consultation des statistiques pour les enseignants.
- Génération automatique de QCM et de contrôles aléatoires à partir des questions existantes.



## Installation

**Node.js 16.9.0 ou une version plus récente est requise.** <br>
Back-end : Installation des dépendances :

```shell
cd ./Quizzly-Flask
pip install -r requirements.txt
```

Lancement du serveur back-end :

```shell
python3 app.py
```

<br>


Front-end : Installations des dépendances :

```shell
cd ./Quizzly-Vue
npm install
```

Build et lancement de l'application :

```shell
npm run build
serve -s dist
```

## Site de Démonstration
Une version démo de Quizzly est disponible à l'adresse suivante : [lien de la démo](https://quizzly.jhune.dev)

## Rapport et vidéo de présentation

Dans le cadre de la partie 2 de ce projet, nous avons réalisé un rapport détaillé présentant les différentes fonctionnalités de Quizzly ainsi que les choix techniques et les difficultés rencontrées lors du développement. 
Vous pouvez consulter ce rapport sur [GitHub](./Rapport).

Nous avons également créé une vidéo de présentation pour vous donner un aperçu de l'application en action. 
Cette vidéo est disponible sur [YouTube](https://www.youtube.com/watch?v=ZQjNgWnm5mE).

## :trophy: Prix :trophy:

À la fin du semestre nos professeurs ont décerné des prix aux meilleurs projets, nous les avons tous remportés.

- Prix de la meilleure vidéo de présentation
- Prix de la meilleure application
- Prix du meilleur projet

