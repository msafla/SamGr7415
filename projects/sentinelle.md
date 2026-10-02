# La Sentinelle — audit des permissions Confluence

**Contexte :** projet interne réalisé chez Skaleet.  
**Rôle :** conception et développement d'un outil d'audit et de suivi des permissions.

![Aperçu de La Sentinelle](../assets/sentinelle.png)

## Problème

À l'échelle de plusieurs espaces Confluence, les permissions et restrictions sont difficiles à vérifier manuellement et à comparer à une référence. Les écarts demandent un suivi explicite pour éviter qu'une anomalie disparaisse dans un traitement interrompu.

## Contribution

- Audit des permissions et restrictions via l'API Confluence.
- Comparaison avec une source de référence et identification des écarts.
- Rapports par espace, suivi des exceptions et gestion des erreurs.
- Checkpoints pour permettre la reprise des traitements.

**Technologies présentées dans le portfolio :** Python, Flask, API Confluence, Gunicorn.

## Résultat et limites

Le système rend les écarts plus visibles et les rapports plus exploitables pour l'équipe. Aucun volume audité ni réduction de risque chiffrée n'est revendiqué publiquement. Les règles de référence, données et sources internes restent privées.

[Étude de cas complète sur msafla.fr](https://msafla.fr/projet/sentinelle)
