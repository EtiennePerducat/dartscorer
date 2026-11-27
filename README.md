# DartScorer

Compteur de fléchettes pour **301, 501, Cricket et Horloge**, de 1 à 4 joueurs, avec profils et statistiques.

- Saisie fléchette par fléchette, annulation, suggestion de finish, annonce vocale.
- En 301 / 501, on saisit en touchant la cible à l'endroit où la fléchette s'est plantée (les fléchettes de la volée et le finish conseillé s'y affichent), ou au pavé numérique, au choix.
- Affichage adapté au téléphone en portrait et à la tablette ou au PC en paysage (la cible prend alors toute la hauteur). Chaque écran remplit la hauteur sans laisser de vide : grande cible sur l'accueil, cible du numéro visé à l'Horloge quand il y a la place. Thème sombre ou clair.
- Options choisies en début de partie : double in / double out / master out, bust ou non, handicap, manches, variantes du Cricket et de l'Horloge.
- Sur les grands écrans (tablette, PC), les stats de la partie en cours s'affichent dans la place libre : volées, moyenne, précision, meilleure volée, etc., et un graphique des volées. Seul, en tuiles ; à plusieurs, en tableau comparatif. Le panneau se réduit ou disparaît quand la place manque.
- Stats par joueur : moyenne par volée, 100+ / 140+ / 180, finish, MPR, victoires, face-à-face, courbes d'évolution.
- Photo de profil prise avec l'appareil photo du téléphone ou de la tablette (ou choisie dans la galerie), affichée dans les listes et pendant la partie.
- Gestion des profils (Réglages › Gérer les profils) : recherche, tri, archivage et restauration, fusion des doublons, suppression définitive.

## Utilisation

- **En ligne** : ouvre la page GitHub Pages du dépôt. Sur téléphone, « Ajouter à l'écran d'accueil » l'installe comme une appli, utilisable hors ligne.
- **En local** : double-clique sur `index.html`.

Les données restent dans le navigateur de chaque appareil. Pour les transférer : Réglages › Exporter, puis Importer sur l'autre appareil (l'import fusionne, rien n'est écrasé).

Tout tient dans `index.html` (HTML, CSS et JavaScript, sans dépendance). `sw.js` et `manifest.webmanifest` servent au mode hors ligne et à l'installation.
