# Yann Poaty Games — PS4 Host

Version personnalisée de présentation basée sur l'archive fournie `PS4_Host(1).zip`.

## Contenu
- `index.html` : page d'accueil personnalisée en français.
- `jb.html` et les fichiers JavaScript/binaires : fichiers techniques d'origine conservés.
- `patches/` : correctifs firmware présents dans l'archive source.
- `cache.manifest` : références harmonisées avec le fichier réellement présent.

## Publication avec GitHub Pages
1. Décompresser l'archive.
2. Ouvrir le dossier `PS4_Host`.
3. Déposer **le contenu** de ce dossier à la racine d'un dépôt GitHub (ne pas créer un dossier supplémentaire autour).
4. Dans GitHub, ouvrir **Settings → Pages**.
5. Choisir **Deploy from a branch**, sélectionner `main` et `/ (root)`, puis enregistrer.
6. Attendre la publication et ouvrir l'URL GitHub Pages affichée par GitHub.

## Important
- La page d'accueil a été redessinée. Le code de détection du firmware et de redirection vers `jb.html` a été conservé.
- Les fichiers techniques d'origine n'ont pas été renommés ni remplacés.
- L'archive contient une configuration firmware plus large que 13.52; la présence d'un fichier de patch ne prouve pas à elle seule que l'ensemble fonctionne sur une console donnée.
- Le manifeste original référençait `goldhen.bin`, absent de l'archive. La configuration 13.52 de `ps4_offsets.js` indique `payload2.bin`; le manifeste a donc été corrigé pour référencer les fichiers réellement présents.
- L'Application Cache est une technologie ancienne et son comportement dépend du navigateur PS4. GitHub Pages ne garantit pas le fonctionnement de l'exploit.
- À utiliser uniquement sur une console que vous possédez ou êtes autorisé à administrer. Aucune réussite ni stabilité n'est garantie.
