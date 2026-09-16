# 4. Attestations et fork choice

Les validateurs émettent des attestations qui votent pour un bloc et un checkpoint. Le client vérifie leur format, leur signature, leur slot et leur cohérence avec l’état connu.

Le fork choice agrège ces votes pour sélectionner la chaîne préférée parmi les branches disponibles. La tête peut être optimiste avant que l’exécution ne confirme le payload.

Les poids de vote et les checkpoints justifiés orientent la sélection ; la finalité intervient lorsque les conditions de justification sont remplies.

Une attestation valide isolément ne garantit pas la finalité de toute la chaîne.

Suite : [Propositions, finalité et slashing](05-propositions-finalite.md).
