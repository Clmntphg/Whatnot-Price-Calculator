# Calculateur JP — déploiement GitHub Pages

## Étapes

1. Crée un nouveau repo GitHub (public), ex. `calculateur-jp`.
2. Mets ces 5 fichiers à la racine du repo :
   - `index.html`
   - `manifest.json`
   - `icon-192.png`
   - `icon-512.png`
   - `icon-180.png`
3. Repo → **Settings** → **Pages** → Source : `main` / dossier `/ (root)` → **Save**.
4. Attends 1–2 min. L'URL apparaît en haut de la page Settings → Pages, du type :
   `https://tonpseudo.github.io/calculateur-jp/`

## Ajouter à l'écran d'accueil (iPhone)

1. Ouvre l'URL dans **Safari** (pas Chrome — l'ajout à l'écran d'accueil de Safari respecte le manifest).
2. Bouton **Partager** → **Sur l'écran d'accueil**.
3. L'icône rouge ¥ apparaît, lancement en plein écran sans barre d'adresse.

## À savoir

- Les données (réglages + historique) sont stockées en `localStorage`, donc **propres à cet appareil et à ce navigateur**. Si tu changes de téléphone ou vides les données Safari, elles sont perdues — pense à noter tes commandes importantes ailleurs si besoin.
- Toute modification future du fichier `index.html` sur GitHub se répercute automatiquement sur l'app (pas besoin de republier ailleurs), il suffit de recharger la page.
