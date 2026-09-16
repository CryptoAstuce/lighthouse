# 2. Beacon Chain et état

La Beacon Chain organise les slots, epochs, validateurs, committees et checkpoints. L’état consensus contient les balances, activations, sorties et attestations nécessaires à la transition.

Chaque slot fournit un contexte temporel pour les votes et la proposition de blocs. Les epochs regroupent les règles de récompense, justification et finalisation.

Le client persiste l’état et les blocs selon une stratégie qui permet de reprendre après un redémarrage et de servir les API.

La finalité repose sur l’accumulation de votes justifiés, pas sur la seule hauteur du dernier bloc reçu.

Suite : [Synchronisation et paires](03-synchronisation-pairs.md).
