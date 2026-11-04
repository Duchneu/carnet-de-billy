# Carnet de Billy

Application compagnon pour les livres-jeux *Les Aventures du Pyro-Barbare et de Billy*, tomes 1 à 3. Elle remplace la feuille d’aventure : fiche de Billy, sac, dés, combats et notes. Le livre reste indispensable pour jouer : l’application ne contient aucun texte des livres.

## Fonctionnalités

- **Parties** : plusieurs aventures en parallèle, une par partie, pour *La Forteresse du Chaudron Noir*, *La Corne des Sables d’Ivoire* et *La Lance de Valkar*. Un autre tome peut être ajouté en saisissant sa page de création de Billy.
- **Création de Billy** : choix des trois objets de départ ; la classe et les caractéristiques se calculent seules, règle des deux mains comprise.
- **Fiche** : PV, Chance, caractéristiques avec le détail de leur calcul, compteurs de la feuille d’aventure, bonus propres à chaque tome.
- **Paragraphes** : paragraphe en cours, retour au précédent, historique et notes par paragraphe.
- **Combats** : table des situations, esquive, contre-attaque critique, domination, pouvoirs de classe et évolutions de caractère. Les combats des tomes 1 et 2 sont pré-remplis avec leurs règles spéciales. Un assaut peut être annulé.
- **Dés** : lancer libre, tests d’Adresse et de Chance.
- **Sac** : objets de départ et objets trouvés, avec leurs bonus.
- **Succès** : déblocage automatique en arrivant au paragraphe (tomes 1 et 2) ou saisie manuelle.
- **Sauvegardes** : points de sauvegarde nommés, export et import de copies de sécurité.
- Fonctionne hors connexion, en thème clair comme en thème sombre.

## Installation

### Dans le navigateur

Ouvrir la page publiée du dépôt. Sur téléphone, « Ajouter à l’écran d’accueil » l’installe comme une application, qui fonctionne ensuite sans connexion.

### Sur Android

Télécharger le fichier APK depuis la page **Releases** du dépôt, puis l’ouvrir sur le téléphone en autorisant l’installation depuis cette source.

## Prise en main

1. **Mes parties** (icône des livres, en haut à gauche) → **Nouvelle partie** → choisir le tome.
2. Choisir trois objets de départ, puis **Créer Billy**.
3. Taper le numéro du paragraphe où l’on se trouve, puis **Aller**.
4. En combat : engager le combat proposé ou saisir l’adversaire depuis son encadré, puis **Lancer l’assaut**. L’icône d’édition, sous la barre de vie de Billy, permet d’ajuster les valeurs.
5. L’engrenage, en haut à droite, ouvre les réglages. Un tutoriel s’affiche au premier lancement et peut être revu depuis les réglages.

## Données

Tout reste sur l’appareil : rien n’est envoyé sur un serveur. Pour changer d’appareil, **Carnet → Copie de sécurité → Exporter**, puis **Importer** sur le nouvel appareil. Sur Android, un dossier de sauvegarde automatique peut être choisi dans le Carnet.

## Publication avec GitHub Pages

**Settings → Pages → Build and deployment** : source « Deploy from a branch », branche `main`, dossier `/ (root)`. L’application est alors disponible à l’adresse `https://<utilisateur>.github.io/<dépôt>/`.

## Avertissement

Projet de fan, non officiel, sans lien avec l’auteur ni l’éditeur des livres. *Les Aventures du Pyro-Barbare et de Billy* et leurs contenus appartiennent à leurs ayants droit.
