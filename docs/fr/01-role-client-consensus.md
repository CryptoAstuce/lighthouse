# 1. Rôle du client consensus

Lighthouse implémente le client consensus Ethereum en Rust. Il suit la Beacon Chain, participe au fork choice et échange des messages avec les validateurs et les autres pairs.

Le client consensus ne calcule pas seul les transitions d’exécution : il dialogue avec un client d’exécution via l’Engine API. Cette séparation permet de faire évoluer les deux couches indépendamment.

La configuration regroupe le réseau, les ports, les clés, le stockage et les paramètres de synchronisation.

Un nœud consensus doit distinguer données finalisées, tête optimiste et tête choisie.

Suite : [Beacon Chain et état](02-beacon-chain-etat.md).
