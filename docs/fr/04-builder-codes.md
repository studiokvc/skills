# 04 — Builder Codes et attribution ERC-8021

Les Builder Codes ajoutent un suffixe ERC-8021 aux données d’une transaction.
Ce suffixe attribue l’activité à l’application sans modifier la logique du contrat ciblé.
L’intégration varie selon viem, wagmi, ethers ou un portefeuille injecté.
Le suffixe doit être ajouté une seule fois et préserver le calldata métier original.
Une bibliothèque intermédiaire peut déjà appliquer l’attribution.
La revue doit donc comparer longueur, terminaison et décodage avant envoi.
L’attribution ne remplace ni authentification ni contrôle d’accès.
Elle doit rester explicite lorsque des agents construisent les transactions.

Suite : [agents et limites](05-agents-limites.md).
