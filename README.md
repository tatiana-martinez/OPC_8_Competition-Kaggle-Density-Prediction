# Concours Kaggle - GoDaddy – Microbusiness Density Forecasting

## Objet
Ce projet a été réalisé dans le cadre de la formation d'ingénieur machine learning proposé par **Openclassrooms**  en partenariat avec **CentraleSupélec**

## But du projet
Il consiste à participer à une compétition réelle et ouverte sur Kaggle.

La compétition s'intitule  **GoDaddy – Microbusiness Density Forecasting**.

## Objectif de la compétition
L'objectif de cette compétition est de soumettre ses prédictions de densité des microentreprises aux USA par comté pour  les périodes 01-11-2022 au 01-06-2023. 

Il est possible de s'appuyer sur les kernels de la compétition sans oublier de le(s) citer.

Le kernel suivant a été en partie suivi pour réaliser le projet : [better-xgb-baseline](https://www.kaggle.com/code/titericz/better-xgb-baseline)

## Contraintes
La contrainte de la compétition est de minimiser la métrique **SMAPE** (**S**ymmetric **M**ean **A**bsolute **P**ercentage **E**rror). 

La contrainte d'OPC est de fournir du code au format **PEP8**.


## Les étapes du projet :
- [x] nettoyage de données
- [x] complétion de données manquantes
- [x] winsorising
- [x] features engineering
- [x] comparaison de plusieurs modèles de ML sélection sur la performance de la métrique SMAPE
- [x] prédictions des densité des microentreprises aux USA par comté pour les 01-11-2022 au 01-06-2023

## Contenu du projet :
```
OPC_8_Competition-Kaggle-Prediction
├─ data
│  ├─ census_starter.csv
│  ├─ sample_submission.csv
│  ├─ test.csv
│  ├─ train.csv
├─ main
│  ├─ MARTINEZ_Tatiana_1_documentation_et_code_022023.ipynb
├─ .gitignore
├─ MARTINEZ_Tatiana_4_presentation_022023.pdf
├─ MARTINEZ_Tatiana_3_rapport_022023.pdf
├─ MARTINEZ_Tatiana_2_lien_kernel_kaggle_022023.pdf
└─ README.md
└─ requirements.txt
```

Le dossier `data/` contient les 4 fichiers issus de la compétition.

Le dossier `main/`  contient le notebook du projet pour la compétition.

