# Comment créer les agents

## Niveau 1 - logique projet
Avant la technique, chaque agent doit avoir :
- un rôle clair
- un périmètre
- des inputs
- des outputs
- des accès définis
- des playbooks

## Niveau 2 - dans OpenClaw
Approche recommandée au début :
- garder Napoleon comme agent principal
- lancer des sous-agents à la demande pour Product / CTO / Frontend / Growth / Ops
- ne pas créer 15 sessions permanentes trop tôt

## Quand créer un vrai agent dédié
Créer un agent dédié quand :
- le rôle est récurrent
- il a un périmètre stable
- il a ses propres docs / mémoire / workflow
- le volume de travail le justifie

## Agents initiaux recommandés
- Product Lead
- CTO Lead
- Frontend Lead
- Growth Lead
- Ops/QA Lead

## Règle
Les agents lisent le tronc commun + leur périmètre + le brief, pas tout le projet entier en permanence.
