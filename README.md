
# My Notes

My Notes est une application mobile développée avec Flutter permettant de créer, consulter, modifier et supprimer des notes.

Les notes sont enregistrées localement dans une base de données SQLite.

## Fonctionnalités

- Connexion utilisateur
- Création de notes
- Consultation des notes
- Modification des notes
- Suppression des notes
- Validation des champs
- Sauvegarde locale avec SQLite
- Conservation des notes après fermeture de l'application

## Technologies utilisées

- Flutter
- Dart
- SQLite
- sqflite
- Material Design

## Structure du projet

```text
lib/
├── main.dart
├── modele/
│   └── note.dart
├── services/
│   └── database_manager.dart
└── views/
    ├── login_interface.dart
    ├── notes_interface.dart
    └── note_form.dart
````

## Installation

1. Cloner le projet :

```bash
git clone URL_DU_REPOSITORY
```

2. Entrer dans le dossier :

```bash
cd activite5
```

3. Installer les dépendances :

```bash
flutter pub get
```

4. Lancer l'application :

```bash
flutter run
```

## Identifiants de démonstration

```text
Nom d'utilisateur : admin
Mot de passe : 1234
```

## Base de données

L'application utilise SQLite pour stocker les notes localement.

Nom de la base de données :

```text
my_notes.db
```

Table principale :

```text
notes
```

Champs :

* `id`
* `titre`
* `contenu`

## Utilisation

Après la connexion, l'utilisateur peut :

* Ajouter une nouvelle note.
* Modifier une note existante.
* Supprimer une note.
* Consulter les notes enregistrées.

## Auteur
Ralph LAURENT
Projet réalisé dans le cadre d'un exercice/projet Flutter.




