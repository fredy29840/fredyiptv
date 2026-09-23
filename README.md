# BREIZH IPTV — releases

APK de l'app IPTV perso (client Xtream Codes / M3U, usage privé famille).

## Code Downloader (Android TV / Fire TV)

Dans l'app **Downloader**, taper simplement le code :

| Code | APK | Pour |
|---|---|---|
| **`9436702`** | arm64-v8a | TV/box 64 bits — **cas général, essayer d'abord** |
| **`9562453`** | armeabi-v7a | TV/box 32 bits ancienne (si « app non installée » avec l'autre) |

Équivalents navigateur : https://aftv.news/9436702 · https://aftv.news/9562453

## Téléchargement (v0.3.0)

| Appareil | APK | Lien direct |
|---|---|---|
| Android TV / box / téléphone récent (64 bits) | `fredyiptv-arm64-v8a.apk` | https://github.com/fredy29840/fredyiptv/raw/main/apk/fredyiptv-arm64-v8a.apk |
| TV/box ancienne 32 bits (ex. TCL) | `fredyiptv-armeabi-v7a.apk` | https://github.com/fredy29840/fredyiptv/raw/main/apk/fredyiptv-armeabi-v7a.apk |
| Émulateur PC | `fredyiptv-x86_64.apk` | https://github.com/fredy29840/fredyiptv/raw/main/apk/fredyiptv-x86_64.apk |

En cas de doute sur l'architecture : prendre **arm64-v8a** d'abord ; si
« app non installée », prendre **armeabi-v7a**.

## Installation sur Android TV (Downloader)

1. Installer **Downloader** (AFTVnews) depuis le store de la TV.
2. Autoriser les sources inconnues pour Downloader
   (Paramètres → Applications → Accès spécial → Installer apps inconnues).
3. Entrer l'URL du lien direct ci-dessus (arm64-v8a en général).
4. Installer, ouvrir, se connecter au serveur.

## Nouveautés v0.3.0

Nouvelle interface TV inspirée de TiviMate :

- **Guide TV** refait : catégories, aperçu et grille des programmes sur un seul écran,
  menu contextuel (appui long OK) avec replay, favoris, recherche.
- **Films et Séries** : grille d'affiches avec note, fiche du titre en haut de l'écran,
  icônes Recherche et Tri, option « Tous » regroupé en rangées par catégorie.
  L'appli rouvre sur la dernière catégorie visitée.
- **Fiches film et série** plein écran : Regarder / Reprendre, bande-annonce YouTube
  (RETOUR revient sur la fiche), **ouvrir dans un lecteur externe** (VLC, MX Player…),
  saisons et épisodes.
- **Paramètres** dans un panneau à droite, par-dessus l'écran, rangés comme TiviMate.
- Base de données allégée au lancement et guide plus rapide à charger.

## Nouveautés v0.2.5

- Messages d'erreur clairs au lieu de codes bruts : « Serveur injoignable »,
  « Le serveur ne répond pas », « Accès refusé : identifiants ou abonnement expiré »…
- Abonnement expiré : l'app affiche **« Abonnement expiré le … »** avec la date,
  dès la connexion et lors des mises à jour.
- « Mettre à jour » indique la cause d'un échec, ex. « chaînes (délai dépassé) ».
- Écran Profils : un serveur en panne n'y bloque plus l'affichage (10 s maximum).

## Nouveautés v0.2.4

- Logo **BREIZH IPTV** au démarrage.
- Erreur **504** (serveur surchargé) : l'app réessaie toute seule 2 fois en quelques
  secondes avant d'afficher l'erreur.
- Écran Profils plus rapide : l'état d'abonnement est gardé 15 min au lieu d'être
  redemandé à chaque ouverture.

## Nouveautés v0.2.3

- L'app s'appelle désormais **BREIZH IPTV** (bandeau TV aux couleurs du Gwenn-ha-du).
  Mise à jour par-dessus l'ancienne version, sans perte de données.
- Films et Séries : la rangée **Historique** (ex-« Continuer » dans Séries) se nettoie
  à la télécommande :
  - rester appuyé sur **OK** sur une affiche → la retirer de l'historique ;
  - rester appuyé sur **OK** sur le libellé « Historique » → tout effacer.

## Nouveautés v0.2.2

- Films et Séries : en **restant appuyé** sur DROITE/GAUCHE, les affiches
  défilent toutes seules (et accélèrent si on garde la touche enfoncée).
- Recherche : les catégories masquées n'apparaissent plus dans les résultats,
  et l'écran s'ouvre sur les onglets Chaînes / Films / Séries (HAUT pour écrire).
- Diagnostics réseau : nouveau **test de débit** (serveur IPTV vs ligne internet)
  et écran TV sur deux colonnes, entièrement visible.

## Nouveautés v0.2.1

- Les listes ne repartent plus au début : en revenant d'un film, d'une série ou
  d'une chaîne, on retrouve sa place **et** la vignette d'où l'on vient.
- Écran Profils : formulaire navigable à la télécommande (HAUT/BAS entre les
  champs, sans passer par le clavier), état d'abonnement lisible et bouton
  « Activer » de nouveau visible sur un profil inactif.

## Notes

- Signé clé debug — distribution privée uniquement, pas de Play Store.
  Une mise à jour s'installe par-dessus sans perte de données.
- Version : 0.3.0 (versionCode 8).
