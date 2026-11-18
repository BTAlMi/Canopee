# Canopée

Canopée sert à organiser un projet ou une veille sur un tableau libre : cartes (notes, images, photos, liens), cadres et flèches. Elle fonctionne hors ligne, sans compte ni abonnement, sur PC Windows, sur Android et dans un navigateur web.

## Mettre en ligne sur GitHub Pages (une seule fois, environ 10 minutes)

1. Sur github.com, crée un nouveau dépôt nommé `canopee`, en visibilité **Public**.
   - Le compte gratuit l'exige pour GitHub Pages.
   - Seul le code est public : tes tableaux ne sont jamais envoyés sur GitHub.
2. Dans le dépôt vide, clique sur **uploading an existing file**. Glisse tout le contenu de ce dossier : `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` et le dossier `icons`. Valide avec **Commit changes**.
3. Va dans **Settings → Pages**. Choisis **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis **Save**.
4. Une à deux minutes plus tard, l'appli répond à l'adresse `https://<ton-pseudo>.github.io/canopee/`.

## Installer l'appli

- **PC Windows (Edge ou Chrome) :** ouvre l'adresse, puis clique sur l'icône « Installer » dans la barre d'adresse, ou passe par Menu → Installer l'application. Un double-clic sur un fichier `.canopee` peut ensuite l'ouvrir directement.
- **Android (Chrome) :** menu ⋮ → **Installer l'application**.

## Où sont enregistrés les tableaux

- **Brouillon :** chaque tableau a un brouillon sur l'appareil, enregistré en continu. La barre latérale liste ces brouillons, rangés en dossiers.
- **Fichier :** pour retrouver un tableau sur un autre appareil, enregistre-le dans un fichier `.canopee` dans ton OneDrive (Ctrl+S). Sur Android, le fichier est téléchargé : dépose-le ensuite dans OneDrive.
- **Images :** elles sont intégrées au fichier, réduites à 1 600 px.
- Rien n'est envoyé sur internet.

## Conversion avec Ramure (par fichier)

- **Vers Ramure :** « Exporter en carte Ramure » (clic droit sur un cadre, une sélection, ou Menu pour le tableau entier) enregistre un fichier `.ramure`. Ouvre-le dans Ramure. Les flèches entre cartes deviennent la hiérarchie, les textes deviennent des notes.
- **Depuis Ramure :** ouvre un fichier `.ramure` ici (Ctrl+O). Chaque feuille devient un cadre, chaque branche principale une carte.

## Publier une mise à jour

Remplace les fichiers dans le dépôt, puis augmente `VERSION` dans `sw.js` (par exemple `canopee-v1.1.1`). La version est visible en bas de la barre latérale.
