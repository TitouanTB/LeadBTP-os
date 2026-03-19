# Environment Policy

## Goal
Créer un environnement visible, contrôlable et suffisamment autonome pour opérer LeadBTP sans chaos.

## Surfaces
- Telegram: commandement rapide et échanges avec Napoleon
- Dashboard OpenClaw: supervision locale des sessions et de l'activité
- Workspace Git: source de vérité documentaire et opérationnelle
- GitHub: source de vérité distante pour le code, la collaboration et les sauvegardes

## Visibility rules
Toute tâche importante doit laisser une trace dans au moins un de ces emplacements:
- `10-control-tower/tasks/`
- `10-control-tower/handoffs/`
- `10-control-tower/decisions.md`
- commit Git si modification structurelle

## Agent operation rules
- Napoleon orchestre
- Les agents spécialisés travaillent par périmètre
- Ils lisent le tronc commun + leur dossier + le brief
- Ils documentent leurs sorties

## Sensitive actions
Validation requise pour:
- prod critique
- envoi réel massif
- suppression de données
- dépenses
- outreach sensible

## Environments
- local/dev: exploration et build
- staging: validation
- prod: restreint et traçable
