# 6. Architecture et limites

Lighthouse sépare réseau, stockage, état, consensus, API et intégration d’exécution. Cette architecture rend les composants testables et permet de choisir différents modes de fonctionnement.

Un client consensus correctement synchronisé ne garantit pas la sécurité d’un opérateur qui expose ses clés, configure mal l’Engine API ou accepte une source non vérifiée.

La disponibilité dépend des pairs, du stockage, des horloges, de l’exécution et des mises à jour de réseau. Les métriques et journaux sont donc une partie opérationnelle du système.

Périmètre : ce parcours traduit les composants Beacon Chain, réseau, synchronisation, attestations, fork choice, propositions et finalité du dépôt. Aucune installation, compilation ou exécution de test n’a été effectuée. Consulter les suites officielles pour une validation concrète.

Retour : [sommaire du parcours](README.md).
