# LeadBTP.io - Project Brain

Ce workspace sert de cerveau central pour le projet LeadBTP.io et pour l'orchestration des agents.

## Objectif
Construire un SaaS/agence pour artisans BTP avec :
- site lead-gen
- inbox unifiée
- SMS appel manqué
- relances devis
- reporting ROI

## Control Tower
Pour avoir une vue d'ensemble, utilise :
- les dossiers de ce workspace comme source de vérité
- `07-agents/` pour les rôles et responsabilités
- `08-playbooks/` pour les handoffs et accès
- `10-control-tower/` pour le pilotage global

## Règle
Les agents ne doivent pas tout lire en permanence. Ils lisent :
1. le tronc commun (`00-core/`)
2. leur périmètre propre
3. le brief de la tâche

## Prochaines étapes
- compléter la couche produit
- compléter la couche tech
- créer les playbooks/skills d'exécution
- brancher les accès réels progressivement
