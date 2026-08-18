Plan d'entrainement marathon — web-app
======================================

CONTENU
  index.html            l'application (tout est dedans)
  manifest.webmanifest  nom, icone, mode plein ecran
  sw.js                 fonctionnement hors connexion
  icon-*.png            icones

METTRE EN LIGNE AVEC GITHUB PAGES
  1. Cree un compte sur github.com
  2. Bouton "+" en haut a droite > New repository
  3. Nom : marathon   |   coche Public   |   Create repository
  4. Sur la page du depot vide : "uploading an existing file"
  5. Glisse LE CONTENU de ce dossier (les 8 fichiers), pas le dossier
     lui-meme. index.html doit etre a la racine du depot.
  6. Bouton vert "Commit changes"
  7. Onglet Settings > menu Pages > Branch: main, dossier / (root) > Save
  8. Attends une minute, recharge : l'adresse s'affiche, du type
     https://<pseudo>.github.io/marathon/

AJOUTER A L'ECRAN D'ACCUEIL
  iPhone (Safari)  : bouton Partager > "Sur l'ecran d'accueil"
  Android (Chrome) : menu ... > "Ajouter a l'ecran d'accueil"
  L'app s'ouvre en plein ecran et fonctionne sans connexion.

METTRE A JOUR
  Depot > Add file > Upload files > glisse les nouveaux fichiers
  (ils ecrasent les anciens) > Commit changes.
  L'adresse et l'icone ne changent pas.

NOTE
  Le depot est public : cette app ne contient volontairement aucune
  donnee personnelle, aucun nom, aucun lieu, aucun resultat passe.
  Uniquement le contenu des seances.
