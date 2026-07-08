# Studio Auvent — site vitrine

Site une page, déployé sur GitHub Pages (`studio-auvent.fr` via le fichier `CNAME`).

## Intégrer les vraies captures des démos

Les cartes du portfolio affichent un aperçu stylisé en CSS **tant que la capture réelle n'existe pas**.
Pour les remplacer, il suffit de déposer à la racine du repo les fichiers suivants (aucun code à toucher) :

- `apercu-plombier.jpg`
- `apercu-boulangerie.jpg`
- `apercu-electricien.jpg`
- `apercu-traiteur.jpg`
- `apercu-menuisier.jpg`

Recommandé : capture du **hero** de chaque démo déployée, ~1200 px de large, format JPEG (qualité 80).
Chaque image recouvre automatiquement l'aperçu stylisé de sa carte ; si le fichier manque, la carte
retombe sur l'aperçu CSS (via `onerror`).
