# Cameroun 360 · La vitrine

Portail institutionnel du patrimoine camerounais (MINREX) — site statique, sans build.

## Contenu
- `index.html` : tout le site (HTML, CSS, JS) — routage par hash (`#/regions`, `#/actus`, …)
- `img/` : photos et logo
- Bilingue FR / EN, carte interactive des 10 régions, hero animé, recherche, boîte à idées

## Lancer en local
Ouvrir `index.html` dans un navigateur (le dossier `img/` doit rester à côté).

## Déployer sur Vercel
1. vercel.com → **Add New… → Project** → importer ce dépôt GitHub
2. **Framework Preset : Other** — laisser *Build Command* et *Output Directory* vides
3. **Deploy**

## À brancher avant la mise en production
- Boîte à idées : la limite (2 contributions / 30 jours) est stockée dans le navigateur ; il faut un back-end pour la recevoir et la modérer
- Contenus rédactionnels (actualités, descriptions) : exemples à remplacer par les contenus validés
