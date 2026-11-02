# Camping — Hivernage

Application web mobile pour inventorier les mobil-homes et leurs équipements avant de construire les procédures d'hivernage.

## Première version (0.1)
- Inventaire des mobil-homes.
- Identification du type de chauffe-eau : ballon électrique, gaz à allumage automatique, gaz avec veilleuse, à identifier.
- Fiche modifiable avec notes terrain.
- Sauvegarde locale dans le navigateur.
- Import/export JSON pour sauvegarder et transférer l'inventaire.

## Donnée initiale connue
- **MH 12** : ballon électrique à accumulation. Marque et modèle non identifiés.

## Limite importante
GitHub Pages héberge des fichiers statiques : les modifications effectuées dans l'interface sont actuellement stockées dans le navigateur utilisé. Elles ne sont pas automatiquement écrites dans le dépôt et ne sont pas partagées entre appareils. La synchronisation distante nécessitera une couche d'authentification sécurisée ; aucun jeton GitHub ne doit être intégré au JavaScript public.

## Déploiement
Le workflow GitHub Actions publie le contenu de la racine sur GitHub Pages.
