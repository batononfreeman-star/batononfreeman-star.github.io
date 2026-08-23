# batononfreeman-star.github.io

Site personnel de **Freeman N. Batonon** — Data & Document Expert / Chef de
projet en ingénierie documentaire / Information & Data Governance / Digital
Transformation.

> Site de **personal & professional branding**, non destiné au référencement
> (voir [Indexation](#indexation)). Accessible uniquement via le lien partagé
> sur le CV et les réseaux professionnels.

## Aperçu

Site statique **one-page, bilingue (FR / EN)**, sans dépendance ni build : il
suffit d'ouvrir `index.html`. Publié automatiquement via **GitHub Pages**
(dépôt `<user>.github.io`) depuis la branche `main`.

- **Français** à la racine (`/index.html`)
- **Anglais** sous `/en/` (`/en/index.html`)
- Sélecteur **FR / EN** dans la barre utilitaire

### Sections
Hero (portrait) · Profil · Expertise (4 piliers) · Domaines (4 secteurs,
photos) · Expérience (frise chronologique) · Compétences & outils ·
Formation & langues · Contact

## Structure

```
index.html                              Page d'accueil (FR)
en/index.html                           Page d'accueil (EN)
styles.css                              Charte graphique (encre/graphite, accents cuivre + teal)
script.js                               Menu mobile, reveal au défilement, nav active
robots.txt                              Bloque l'indexation par les moteurs de recherche
assets/monogram.svg                     Monogramme "FB" (favicon / logo)
assets/portrait-freeman.jpg             Portrait (hero)
assets/secteur-qualite-documentaire.jpg Illustration — qualité & ingénierie documentaire
assets/secteur-data-gouvernance.jpg     Illustration — data & gouvernance de l'information
assets/secteur-ferroviaire-transport.jpg Illustration — ferroviaire & transport
assets/secteur-energie-industrie.jpg    Illustration — énergie & industrie
```

## Indexation

Le site n'est **pas destiné à être référencé** sur les moteurs de recherche :
- `robots.txt` interdit l'exploration (`Disallow: /`)
- Chaque page porte `<meta name="robots" content="noindex, nofollow">`

Ces mécanismes sont respectés par les moteurs de recherche de bonne foi
(Google, Bing…) mais n'empêchent pas techniquement l'accès direct au site si
l'URL est connue — le dépôt GitHub reste public. Pour une confidentialité
stricte, il faudrait un dépôt privé + hébergement tiers avec authentification.

## Personnalisation

Les couleurs sont centralisées dans les variables CSS (`:root`) en haut de
`styles.css` — notamment `--copper-500` (accent ferroviaire/industrie) et
`--teal-400` (accent data/systèmes).

## Contenu

Le contenu (parcours, compétences, formation) est basé sur le CV de
Freeman N. Batonon. Pour le mettre à jour, éditer les sections correspondantes
dans `index.html` **et** `en/index.html` (contenu dupliqué, pas de système de
traduction automatique).

## Développement local

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```
