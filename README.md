# Cleaner Society

Landing page statique pour **Cleaner Society**, un service de nettoyage pour maisons, bureaux et espaces partagés.

Le site présente les services, les points forts, les marques de référence, une section qualité, un formulaire de demande et un footer de contact.

## Démarrage

Aucune installation n'est nécessaire.

Ouvrir simplement le fichier suivant dans un navigateur :

```text
C:\Users\DELL\cleaner-society-landing\index.html
```

Si le projet est ouvert dans VS Code, vous pouvez aussi utiliser une extension comme **Live Server** pour lancer le site localement.

## Structure

```text
cleaner-society-landing/
  images/       Images et logos utilisés par le site
  index.html    Structure HTML de la page
  styles.css    Styles, responsive design et animations
  script.js     Menu mobile et animations d'apparition
  README.md     Documentation du projet
```

## Fonctionnalités

- Page responsive pour desktop, tablette et mobile
- Navigation mobile avec bouton hamburger
- Section hero avec image de fond
- Cartes de services
- Slider infini de marques sur deux lignes
- Animations légères au scroll et au survol
- Support `prefers-reduced-motion` pour réduire les animations
- Formulaire de demande de réservation

## Personnalisation

Pour changer le texte du site, modifier `index.html`.

Pour changer les couleurs, modifier les variables CSS au début de `styles.css` :

```css
:root {
  --ink: #10201d;
  --green: #1f8a61;
  --green-dark: #116647;
}
```

Pour remplacer les logos ou images, ajouter les fichiers dans le dossier `images/`, puis mettre à jour les balises `<img>` dans `index.html`.

## Git

Le projet est déjà initialisé avec Git.

Commandes utiles :

```bash
git status
git add .
git commit -m "Description du changement"
```

## Notes

Ce projet est un site statique. Il ne contient pas encore de backend : le formulaire ne transmet pas réellement les demandes. Pour recevoir les réservations, il faudra connecter le formulaire à un service externe ou à une API.

