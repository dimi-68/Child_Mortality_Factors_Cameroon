# Analyse des facteurs sociodémographiques associés à la mortalité infanto-juvénile au Cameroun (EDS 2018)

## Objectif 
Explorer les facteurs sociodémographiques associés au risque de mortalité infanto-juvénile au Cameroun à partir des données de l’Enquête Démographique et de Santé (EDS) 2018, en utilisant un modèle de Cox à risques proportionnels.

## Contexte 
Selon l'EDS 2018, 80 enfants sur 1000 naissances vivantes sont décédés avant leur cinquième anniversaire. La mortalité infanto-juvénile est un problème majeur de santé publique ayant de fortes répercussions sociales et économiques.

Bien que plusieurs études locales aient exploré des facteurs cliniques de la mortalité néonatale, peu ont intégré les facteurs sociodémographiques et utilisé des méthodes appropriées pour prendre en compte la censure des données. L'analyse de survie (modèle de Cox) permet de mieux répondre à cette problématique.

## Données 
- Source : Enquête Démographique et de Santé du Cameroun (EDS 2018)
- Population : Enfants issus des naissances survenues au cours des 5 années précédant l'enquête.

## Méthodologie 
- Construction d'un jeu de données adapté (temps de suivi, événement (décès ou non).
- Vérification des hypothèses du modèle de Cox (proportionnalité des risques).
- Ajustement d'un modèle multivarié de Cox avec sélection de facteurs sociodémographiques pertinents.
- Présentation des résultats par hazard ratios (HR) et intervalles de confiance à 95 % (IC 95 %).

## Résultats principaux
- Les enfants masculins avaient un risque de décès 21 % plus élevé que les féminins (HR=1.21, p=0.017).
- Résider dans la région de l'Est augmentait le risque de 34 % (HR=1.34, p=0.033).
- Être issu d'une naissance multiple (jumeaux) multipliait le risque par 2,6 à 4 selon l'ordre de naissance (HR=2.60 et HR=4.08, p<0.001).
- Le poids de naissance inconnu ou faible était fortement associé à une surmortalité (+109 % et +77 % respectivement).

## Technologies utilisées
- R version 4.4.2
- Packages principaux : `survival`, `survminer`, `dplyr`, `ggplot2`

## Remarques importantes 
- Les données utilisées sont soumises à des droits d'accès spécifiques (DHS Program).
- Les résultats doivent être interprétés dans le contexte camerounais de 2018 et ne peuvent pas être directement extrapolés à d'autres contextes ou périodes sans précaution.

## Auteur
- **YONTA Dimitry Emerson**  
- [Dyonta68@gmail.com]
