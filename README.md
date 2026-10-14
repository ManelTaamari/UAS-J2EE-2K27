# TP 1 — Environnement Java et rappels fondamentaux

## Présentation du projet

Ce projet a été réalisé dans le cadre du TP 1 du module J2EE pour mettre en place un environnement de développement Java et réviser les concepts fondamentaux de la programmation orientée objet (POO).

## Objectifs

- Vérifier et utiliser un environnement Java avec le JDK.
- Créer et exécuter un projet Java avec IntelliJ IDEA.
- Comprendre les classes, les objets et les constructeurs.
- Appliquer le principe d'encapsulation.
- Utiliser les getters et les setters.
- Organiser le code en packages et utiliser les importations.

## Technologies utilisées

- **Langage :** Java
- **JDK :** version installée sur l'environnement de développement
- **IDE :** IntelliJ IDEA
- **Gestion de versions :** Git et GitHub

## Structure du projet

```text
t1java/
├── src/
│   ├── app/
│   │   └── Main.java
│   └── Model/
│       └── Etudiant.java
└── README.md
```

## Description des classes

### `Etudiant.java`

Cette classe représente un étudiant à travers trois attributs privés :

- `nom` : de type `String`
- `age` : de type `int`
- `moyenne` : de type `double`

Elle contient un constructeur pour initialiser les données, des getters pour les consulter, des setters pour les modifier et une méthode `afficher()` pour présenter les informations.

### `Main.java`

La méthode `main()` constitue le point d'entrée de l'application. Elle permet de créer deux objets `Etudiant`, d'afficher leurs informations et de modifier la moyenne du premier étudiant.

## Exemple de fonctionnement

Deux étudiants sont créés :

- Manel, âgée de 32 ans, avec une moyenne de 17.5.
- Sami, âgé de 22 ans, avec une moyenne de 16.0.

La moyenne de Manel est ensuite modifiée à 18.0 à l'aide de la méthode `setMoyenne()`.

## Concepts étudiés

- **Classe :** modèle définissant les données et les comportements.
- **Objet :** instance d'une classe.
- **Constructeur :** initialise un objet lors de sa création.
- **Encapsulation :** protège les attributs grâce au modificateur `private`.
- **Getter :** permet de consulter un attribut.
- **Setter :** permet de modifier un attribut.
- **Package :** organise les classes selon leur rôle.

## Exécution du projet

1. Ouvrir le projet dans IntelliJ IDEA.
2. Vérifier que le JDK est correctement configuré.
3. Ouvrir la classe `Main.java`.
4. Exécuter la méthode `main()`.



Ce TP a permis de mettre en pratique les bases de Java et de la programmation orientée objet. L'organisation des classes en packages constitue une première étape vers l'architecture multicouche qui sera étudiée dans les prochains TP du module J2EE.

merci Mr Marwen :)