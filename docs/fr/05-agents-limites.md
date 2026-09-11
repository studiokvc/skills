# 05 — Agents, migrations et limites

Le dépôt documente l’enregistrement d’agents et l’association d’un Builder Code.
Un agent automatisé doit séparer stratégie, construction, simulation, signature et diffusion.
Les entrées utilisateur destinées aux outils de transaction exigent une validation stricte.
Les migrations OnchainKit ou MiniKit changent fournisseurs, contexte et parfois attentes du portefeuille.
Une migration doit donc vérifier réseau, session, méthodes disponibles et comportement de repli.
Ce parcours couvre réseau, Base Account, paiements, paymasters, ERC-8021 et agents.
Il décrit les instructions du dépôt sans effectuer de déploiement ni de transaction.
Aucune installation, compilation ou exécution n’a été effectuée ; les références amont restent normatives.
