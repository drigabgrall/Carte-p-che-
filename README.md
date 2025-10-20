# Spots de pêche – Carte + Météo

Application web statique (Leaflet + Open‑Meteo) pour enregistrer des spots de pêche et consulter la météo/mer en direct.

## Utilisation
- Ouvrir `index.html` dans un navigateur.
- Ajouter des spots en cliquant sur la carte (bouton **Ajouter un spot**).
- Sauvegarde locale automatique (localStorage). Export/Import JSON.

## Déploiement GitHub Pages
1. Crée un dépôt public et ajoute `index.html` à la racine.
2. Va dans **Settings → Pages**.
3. Source: *Deploy from a branch*. Branch: `main`. Dossier: `/ (root)`.
4. Ton site sera disponible à `https://<user>.github.io/<repo>/`.

## Crédits
- Cartes : OpenStreetMap via Leaflet.
- Données météo & houle : Open‑Meteo (pas de clé API).
