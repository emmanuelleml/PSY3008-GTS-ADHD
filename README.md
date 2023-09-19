# PSY3008-SGT-ADHD
PSY3008 - Syndrome de Gilles de la Tourette et TDAH
Analyses statistiques portant sur la question de recherche suivante : les individus atteints du syndrome de Gilles de la Tourette avec une symptomatologie comorbide répondent-ils différemment au traitement par TCC que les individus sans symptomatologie TDAH comorbide ?

YGTSS_CAARS.Rmd :
- Fusion des banques de données des différentes variables (données sociodémographiques, BAI, BDI, CAARS, YGTSS)
- Uniformisation des appellations des temps de mesure
- Retrait des participants ayant des mesures manquantes
- Reformattage de la banque de données au format large
- Utilisation de la méthode RCI pour déterminer si les deux mesures pré-traitement sont supérieures au seuil délimité par l'effet test-retest
- Séparation des groupes tourette et tourette+TDAH sur la base de la médiane des scores au CAARS

stats.Rmd :
- Préparation de la banque de données
- Vérification de la plausibilité des scores, des scores extrêmes, de la variance, de la normalité et de l'hétérogénéité
- Khi carré : vérification de l'égalité des groupes sur les variables de sexe et d'âge
- ANOVAs comparant les groupes tourette, tourette+TDAH et contrôle sur les variables BAI et BDI
- Test-t comparant les groupes tourette et tourette+TDAH sur les mesures d'intérêt du YGTSS et du CAARS
- Histogrammes de la répartition des scores entre les groupes
