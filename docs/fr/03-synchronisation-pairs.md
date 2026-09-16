# 3. Synchronisation et paires

La synchronisation récupère les en-têtes, blocs et états nécessaires auprès de pairs. Lighthouse combine découverte, téléchargement, validation et progression vers une tête exploitable.

Les pairs annoncent leurs capacités et peuvent être écartés si leurs réponses sont invalides, trop lentes ou incohérentes. La disponibilité d’un pair ne constitue pas une preuve de validité.

Le mode de synchronisation dépend de la distance à la tête et de la présence d’un checkpoint de confiance.

Une reorganisation ou une donnée manquante doit être traitée sans confondre retard temporaire et chaîne invalide.

Suite : [Attestations et fork choice](04-attestations-fork-choice.md).
