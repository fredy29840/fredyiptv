# FRED IPTV — releases

APK de l'app IPTV perso (client Xtream Codes / M3U, usage privé famille).

## Code Downloader (Android TV / Fire TV)

Dans l'app **Downloader**, taper simplement le code :

| Code | APK | Pour |
|---|---|---|
| **`9436702`** | arm64-v8a | TV/box 64 bits — **cas général, essayer d'abord** |
| **`9562453`** | armeabi-v7a | TV/box 32 bits ancienne (si « app non installée » avec l'autre) |

Équivalents navigateur : https://aftv.news/9436702 · https://aftv.news/9562453

## Téléchargement (v0.1.0)

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

## Notes

- Signé clé debug — distribution privée uniquement, pas de Play Store.
  Une mise à jour s'installe par-dessus sans perte de données.
- Version : 0.1.0 (versionCode 1).
