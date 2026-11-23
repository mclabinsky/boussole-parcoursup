# Boussole Parcoursup – MCLAB Conseil

Application web d'accompagnement à l'orientation et à Parcoursup pour lycéens et parents (version famille, sans IA).
Toutes les réponses restent dans le navigateur de l'utilisateur : aucun serveur, aucune base de données.

## Mettre en ligne avec GitHub Pages (sans code)

1. Se connecter sur https://github.com, cliquer sur **New repository**.
2. Nom : `boussole-parcoursup`, visibilité **Public** (obligatoire pour GitHub Pages sur un compte gratuit), puis **Create repository**.
3. Cliquer sur **uploading an existing file**, glisser `index.html`, `README.md` et `.nojekyll`, puis **Commit changes**.
4. Onglet **Settings** > **Pages** > Source : **Deploy from a branch**, branche **main**, dossier **/ (root)**, **Save**.
5. Attendre quelques minutes : l'adresse s'affiche en haut de la page Pages (`https://[identifiant].github.io/boussole-parcoursup/`).

## Avant de partager le lien

- Remplacer `[lien vers la politique de confidentialité]` dans `index.html` par l'adresse publique de la politique.
- Mettre à jour le calendrier Parcoursup chaque année (tableau `CAL` dans `index.html`).

## Mettre à jour

Dans le dépôt, ouvrir `index.html` > icône crayon, ou **Add file > Upload files** pour remplacer le fichier.
