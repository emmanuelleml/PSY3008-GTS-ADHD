# PSY3008 - Syndrome de Gilles de la Tourette et TDAH

Question de recherche : les individus atteints du syndrome de Gilles de la Tourette avec une symptomatologie TDAH comorbide répondent-ils différemment au traitement par TCC que les individus sans symptomatologie TDAH comorbide au niveau de l'amélioration des tics et du maintien de la réponse 6 mois plus tard ?

## YGTSS_CAARS.Rmd :
- Fusion des banques de données des différentes variables (données sociodémographiques, BAI, BDI, CAARS, YGTSS)
- Uniformisation des appellations des temps de mesure
- Retrait des participants ayant des mesures manquantes
- Reformattage de la banque de données au format large
- Méthode RCI pour déterminer si les deux mesures pré-traitement (s'il y a lieu) sont supérieures au seuil délimité par l'effet test-retest (cliniquement équivalents)
- Séparation des groupes sur la base de la médiane des scores au CAARS : Contrôle, Contrôle+TDAH, Tourette, Tourette+TDAH

## stats.Rmd :
- Vérification de la plausibilité des scores, scores extrêmes, et postulats
- Analyses préliminaires : correspondance des groupes sur BAI, BDI, CAARS total, âge et sexe
- Analyses principales :
        1) ANCOVA réponse à la TCC : sévérité des tics post-traitement (VD) en fonction du groupe (VI; Tourette VS Tourette+TDAH), en contrôlant pour la sévérité des tics pré-traitement (CV)
        2) ANCOVA maintien de la réponse à la TCC : sévérité des tics 6 mois post-traitement (VD) en fonction du groupe (VI; Tourette VS Tourette+TDAH), en contrôlant pour la sévérité des tics post-traitement (CV)
