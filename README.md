# Lucas Gomes · Portfolio

Portfolio personnel : étudiant à l'ESGI Toulouse en reconversion vers l'informatique, à la recherche d'une alternance en **cybersécurité, IA ou data**.

## Ce qu'on y trouve
- Deux thèmes au choix : **Pro** (clair) et **Cyber** (sombre), avec transition circulaire.
- Fond interactif (canvas) qui réagit à la souris, titres animés, ligne de parcours qui se remplit au défilement.
- Projets avec aperçu animé au survol (vidéo du site, requête SQL, logs, capteurs de la serre…) et fiche détaillée au clic.
- CV en français et en anglais, consultable et téléchargeable.

## Technique
HTML, CSS et JavaScript **vanilla**, sans framework ni étape de build : le site est servi tel quel par GitHub Pages.
Le code est commenté section par section dans `index.html`.

```
index.html                  page principale (styles et scripts inclus)
assets/media/               vidéos de démonstration, affiches, aperçus du CV
cv/                         CV en PDF (FR / EN)
projets/cadence/            site de présentation de Cadence
projets/comptoir-des-saveurs/  TP HTML/CSS : site one page d'un restaurant
projets/cornichon-palace/   TP Bootstrap 5 : site vitrine 3 pages + page 404
```

## Lancer en local
Ouvrir un terminal dans le dossier puis :
```
python -m http.server 8000
```
et aller sur http://localhost:8000

Respecte `prefers-reduced-motion` : les animations sont coupées si le système le demande.
