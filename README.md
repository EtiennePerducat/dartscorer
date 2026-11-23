# DartScorer

Compteur de fléchettes pour **301, 501, Cricket et Horloge**, de 1 à 4 joueurs, avec profils et statistiques.

- Saisie fléchette par fléchette, annulation, suggestion de finish, annonce vocale.
- Options choisies en début de partie : double in / double out / master out, bust ou non, handicap, manches, variantes du Cricket et de l'Horloge.
- Stats par joueur : moyenne par volée, 100+ / 140+ / 180, finish, MPR, victoires, face-à-face, courbes d'évolution.
- Gestion des profils (Réglages › Gérer les profils) : recherche, tri, archivage et restauration, fusion des doublons, suppression définitive.

## Utilisation

- **En ligne** : ouvre la page GitHub Pages du dépôt. Sur téléphone, « Ajouter à l'écran d'accueil » l'installe comme une appli, utilisable hors ligne.
- **En local** : double-clique sur `index.html`.

Les données restent dans le navigateur de chaque appareil. Pour les transférer : Réglages › Exporter, puis Importer sur l'autre appareil (l'import fusionne, rien n'est écrasé).

Tout tient dans `index.html` (HTML, CSS et JavaScript, sans dépendance). `sw.js` et `manifest.webmanifest` servent au mode hors ligne et à l'installation.
