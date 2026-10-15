# Atlas des avant-gardes — prototype 0.1

Site statique en HTML/CSS/JavaScript, avec Cytoscape.js (chargé via CDN).

## Démarrage local

Depuis le dossier `atlas-avant-gardes` :

```bash
python3 -m http.server 8000
```

Ouvrez http://localhost:8000. L'ouverture directe du fichier index.html ne fonctionne pas toujours à cause des restrictions de lecture des fichiers JSON.

## GitHub Pages

Créez un dépôt GitHub, envoyez **le contenu du dossier** à la racine du dépôt, puis allez dans Settings → Pages → Deploy from a branch → main / root. L'adresse publique sera généralement `https://VOTRE-COMPTE.github.io/NOM-DU-DEPOT/`.

## Données

- `data/people.json` : identifiants, noms, dates, groupes, biographies et œuvres.
- `data/relations.json` : liens sourcés, avec catégories A (direct/éditorial), B (via tiers), C (lecture).

**Attention** : A n'implique pas forcément une rencontre physique. Certains liens et URL sont des points de départ bibliographiques, pas des références primaires suffisamment précises. Fondane figure sans lien faute de preuve dans cette version. Les données constituent un prototype de recherche et doivent être enrichies et vérifiées avant publication scientifique.

## À venir

Nœuds « revues », œuvres, événements, sources détaillées, portraits libres de droits, dates des relations, recherche de chemins, édition des fiches et exports.
