# Progression MINESEC – Android

Projet préparé pour compiler l'application HTML en APK Android avec GitHub Actions, sans Android Studio sur le téléphone.

## Compilation
1. Créer un dépôt GitHub nommé `progression-minesec-android`.
2. Importer tous les fichiers et dossiers de ce projet à la racine du dépôt.
3. Ouvrir l'onglet **Actions** et autoriser les workflows si GitHub le demande.
4. Dans **Construire l'APK Android**, lancer **Run workflow** (ou pousser un commit sur `main`).
5. Quand le workflow est terminé avec une coche verte, ouvrir son exécution et télécharger l'artefact `Progression-MINESEC-APK`.
6. Extraire le ZIP téléchargé : il contient `app-debug.apk`.

## Informations
- Nom affiché : Progression MINESEC
- Identifiant Android : `cm.lybiyom.progressionfrancais`
- Les fichiers web sont embarqués dans l'application : l'interface peut fonctionner hors ligne.
- Les données enregistrées dans `localStorage` restent dans le stockage privé de l'application Android. Elles ne sont pas automatiquement synchronisées avec un navigateur ou un autre téléphone.
- Cette première compilation produit un APK de test (`debug`). Pour une diffusion durable, il faudra ensuite préparer une version signée (`release`) et conserver sa clé de signature en lieu sûr.
