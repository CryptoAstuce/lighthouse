# 5. Propositions, finalité et slashing

Un proposant construit un bloc pour un slot et y associe un payload d’exécution. Les validateurs attestent ensuite la branche qu’ils considèrent correcte.

La finalité limite les réorganisations acceptables. Les règles de slashing sanctionnent certaines signatures incompatibles, comme des votes contradictoires ou des propositions concurrentes.

Le client doit conserver assez de contexte pour détecter ces conditions et exposer les événements aux opérateurs. Les clés de validation sont donc des actifs de sécurité critique.

Les récompenses et pénalités dépendent de la participation et de l’état global.

Suite : [Architecture et limites](06-architecture-limites.md).
