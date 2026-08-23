# batononfreeman-star.github.io

Site personnel de **Freeman N. Batonon** — Data & Document Expert / Chef de
projet en ingénierie documentaire / Information & Data Governance / Digital
Transformation.

## Aperçu

Site statique **one-page**, sans dépendance ni build : il suffit d'ouvrir
`index.html`. Publié automatiquement via **GitHub Pages** (dépôt
`<user>.github.io`) depuis la branche `main`.

### Sections
Hero · Profil · Expertise (4 piliers) · Expérience (frise chronologique) ·
Compétences & outils · Formation & langues · Contact

## Structure

```
index.html            Page unique (one-page)
styles.css             Charte graphique (encre/graphite, accents cuivre + teal)
script.js               Menu mobile, reveal au défilement, nav active
assets/monogram.svg     Monogramme "FB" (favicon / logo)
```

## Personnalisation

Les couleurs sont centralisées dans les variables CSS (`:root`) en haut de
`styles.css` — notamment `--copper-500` (accent ferroviaire/industrie) et
`--teal-400` (accent data/systèmes).

## Contenu

Le contenu (parcours, compétences, formation) est basé sur le CV de
Freeman N. Batonon. Pour le mettre à jour, éditer directement les sections
correspondantes dans `index.html`.

## Développement local

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```
