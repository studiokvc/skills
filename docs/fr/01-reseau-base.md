# 01 — Réseau Base et frontières L2

Le parcours `build-on-base` rassemble les paramètres réseau nécessaires aux applications.
Base mainnet utilise l’identifiant de chaîne 8453 et Base Sepolia 84532.
Un client doit vérifier l’identifiant retourné par le portefeuille avant de signer.
RPC, explorateur et chaîne doivent désigner le même environnement.
Base hérite de l’OP Stack mais une application reste responsable de ses hypothèses de finalité.
Les dépôts et retraits traversent une frontière L1/L2 avec des délais différents.
Une configuration de testnet ne doit jamais être confondue avec une adresse de production.
Centraliser ces paramètres réduit les erreurs silencieuses d’environnement.

Suite : [Base Account et permissions](02-base-account.md).
