# BLACK GOKU CHECK BAN

PWA gratuite, conçue pour être publiée avec GitHub Pages.

## Fichiers
- `index.html` : interface, validation internationale, historique local et langues FR/PT/EN.
- `manifest.json` : identité installable de la PWA.
- `sw.js` : cache des fichiers de l'application.
- `icons/icon.svg` : icône vectorielle.

## Publication GitHub Pages
1. Téléversez tous les fichiers et le dossier `icons` à la racine du dépôt.
2. Ouvrez Settings > Pages.
3. Dans Build and deployment, choisissez Deploy from a branch.
4. Sélectionnez `main` et `/ (root)`, puis Save.
5. Attendez la publication et ouvrez l'URL GitHub Pages en HTTPS.
6. Dans Chrome Android, ouvrez le menu ⋮ puis « Installer l'application » ou « Ajouter à l'écran d'accueil ».

## Limites importantes
Cette application vérifie le format des numéros avec une bibliothèque de validation téléphonique. Elle ne confirme pas qu'un numéro est attribué, actif, inscrit sur WhatsApp ou banni. Le statut de bannissement d'un compte tiers n'est pas consultable publiquement.
L'historique est stocké localement dans le navigateur via localStorage. Les numéros ne sont pas envoyés à un serveur par le code de l'application. La bibliothèque de validation est chargée depuis jsDelivr, donc la première validation nécessite une connexion Internet.
