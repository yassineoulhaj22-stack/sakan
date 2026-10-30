# Sakan – App Android (APK)

## Générer l'APK avec GitHub
1. Créez un dépôt GitHub (ex. `sakan-app`).
2. Décompressez ce ZIP et envoyez TOUT son contenu à la racine du dépôt
   (y compris le dossier `.github`). Sur le site : Add file > Upload files.
3. Ouvrez l'onglet **Actions** > **Build Android APK** > **Run workflow**
   (il se lance aussi automatiquement à chaque push sur main).
4. Attendez ~5 min, ouvrez l'exécution terminée, section **Artifacts**,
   téléchargez **Sakan-APK** (zip contenant `app-debug.apk`).
5. Envoyez l'APK sur votre téléphone et installez-le
   (autorisez « sources inconnues »).

## Modifier l'app
Tout le code de l'interface est dans `www/index.html`.
