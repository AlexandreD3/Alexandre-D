# Bibliothèque (GitHub Pages)

Site statique (GitHub Pages) : page d'accueil + lecture en ligne des livres (PDF.js) + boutons de téléchargement.

## Structure
- `index.html` : accueil
- `books/` : pages de lecture
- `pdf/` : fichiers PDF
- `assets/` : styles, JS, couvertures

## Déploiement
1. Pousse le contenu sur GitHub (branche `main`).
2. GitHub → Settings → Pages → Build and deployment:
   - Source: Deploy from a branch
   - Branch: `main` / `(root)` ou `/docs` (selon où tu mets les fichiers)
3. Ouvre l’URL GitHub Pages.

## Ajouter un livre
1. Dépose le PDF dans `pdf/`
2. Ajoute une couverture dans `assets/`
3. Ajoute une carte dans `index.html`
4. Crée une page `books/<slug>.html` (copie d’une page existante)
