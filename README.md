# LGEO2250

**Facteurs influençant le choix de destination Erasmus**

## AUTEURS

- Lucas Wautot
- Nicolas Jamar Rodriguez
- Eléonore Vanderlinden
- Laura Damien

Cours: LGEO2250 – Mesures de terrain en Géographie  
Institution: UCLouvain – Earth and Life Institute

## DESCRIPTION

Ce dépôt contient les données et scripts associés à une enquête visant à identifier les destinations Erasmus les plus populaires et les facteurs influençant ces préférences.

### Question de recherche

Quels facteurs influencent le choix de destination Erasmus chez les étudiants ?

### Type de données

- Données catégorielles (genre, niveau d’étude, région)
- Données ordinales (échelles de Likert 1–5)
- Données de classement (préférences de destinations)
- Données textuelles (réponses ouvertes)

### Période de collecte

Du 16 février 2026 à 16h30 jusqu’au 27 février 2026 à 17h30.

### Population

Échantillon composé principalement d'étudiants universitaires francophones (N = 170)

### Méthode de collecte

Questionnaire en ligne diffusé via Microsoft Forms.

## STRUCTURE DES FICHIERS

`data_raw/`  
`→ enquete_erasmus_raw.xlsx`  
Export original du questionnaire (non modifié).

`data_processed/`  
`→ enquete_erasmus_clean.csv`  
Données nettoyées utilisées pour l’analyse.

`scripts/`  
`xx.R`  
`xx.R`  
`....`  
Scripts permettant les analyses et les figures.

`figures/`  

`metadata/`  
`→ data_dictionary.csv`  
`→ LICENSE.txt`

## NETTOYAGE ET TRANSFORMATIONS

- Suppression des réponses incomplètes
- Recodage des réponses « Peut-être » en « Oui » pour l’analyse binaire
- Codage des échelles de Likert (1 = Très peu → 5 = Très fort)

## REPRODUCTION DES ANALYSES

Les analyses peuvent être reproduites en :
1. Chargeant data_processed/enquete_erasmus_clean.csv
2. Exécutant les scripts du dossier scripts/
3. Toutes les figures présentées sont générées automatiquement lors de l’exécution des scripts situés dans le dossier scripts/.

## CONFORMITÉ RGPD

Aucune donnée personnelle identifiable n’est incluse.

## CITATION DU JEU DE DONNÉES

Wautot L., Jamar Rodriguez N., Vanderlinden E., Damien L. (2026).
Erasmus Survey Dataset. UCLouvain.

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.
