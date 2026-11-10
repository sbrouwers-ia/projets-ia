# Portfolio IA – Automatisation

Trois projets d'automatisation avec l'IA, menés en octobre et novembre 2026, sans écrire de code applicatif.

Chaque projet est mené comme un vrai projet : backlog Jira, sprints, définition de « terminé », jeu de tests, documentation et coût mesuré.

## Les projets

| Projet | En une phrase | Outils | Détails |
|---|---|---|---|
| **1. Veille IA** | Chaque lundi à 9h, un mail avec les meilleurs articles IA de la semaine, résumés en français, et une archive dans Notion | Make, Claude Haiku, Gmail, Notion | [veille-ia](veille-ia/README.md) |
| **2. Réunion → Jira** | Le transcript d'une réunion devient des tickets Jira validés un par un, puis un compte rendu envoyé aux participants | n8n, Claude Haiku, Jira, Gmail | [reunion-vers-jira](reunion-vers-jira/README.md) |
| **3. Assistant documentaire (RAG)** | Un chat qui répond à partir de mes documents, cite sa source et dit « je ne trouve pas » plutôt que d'inventer | n8n, Gemini, Claude Haiku | [rag-portfolio](rag-portfolio/README.md) |

## Principes

* No-code / low-code : Make, puis n8n.
* L'IA au bon endroit : des règles pour tout ce qui est prévisible, l'IA seulement pour ce qui demande du jugement.
* Validation humaine avant tout envoi ou toute écriture dans un outil d'équipe.
* Accès au strict minimum et aucune clé ni mot de passe dans les fichiers.
* Chaque étape est documentée, avec le coût de chaque projet.

## À propos de ce dépôt

Ce dépôt présente les projets : besoin, fonctionnement, réglages, coûts, tests et limites. Les workflows et les prompts restent privés : **démo en direct sur demande**.
