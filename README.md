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

Ce jeu de données contient les réponses à une enquête (aupres de la population Belge) afin d’identifier les facteurs influençant le choix de destination Erasmus.

### Question de recherche

Quels facteurs influencent le choix de destination Erasmus chez les étudiants ?

### Type de données

- Données catégorielles (genre, niveau d’étude, région)
- Données ordinales (échelles de Likert 1–5)
- Données de classement (préférences de destinations)
- Données textuelles (réponses ouvertes)

### Période de collecte

Février 2026 - (Mars 2026)

### Population

Population Belge (N = XXX)

### Méthode de collecte

Questionnaire en ligne diffusé via Microsoft Forms.

## LIMITES

- Échantillon non représentatif (biais universitaire + Brabant Wallon + Brabant Flamend)
- Tous les facteurs culturels n’ont pas été pris en compte.

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
Scripts permettant de reproduire le nettoyage, les analyses et les figures.

`figures/`  
`→ Graphiques utilisés dans le rapport final.`

`metadata/`  
`→ README.txt`  
`→ data_dictionary.csv`  
`→ LICENSE.txt`

## NETTOYAGE ET TRANSFORMATIONS

- Suppression des réponses incomplètes
- Codage des échelles de Likert (1 = Très peu → 5 = Très fort)

## REPRODUCTION DES ANALYSES

1. Ouvrir le projet R
2. Charger les données: `data_processed/enquete_erasmus_clean.csv`
3. Exécuter les scripts dans le dossier `scripts/`
4. Les figures sont automatiquement dans `figures/`

## FORMATS UTILISÉS

- CSV (interopérable)
- XXX (figures)
- TXT (metadata)

## CONFORMITÉ RGPD

Aucune donnée personnelle identifiable n’est incluse.

## CITATION DU JEU DE DONNÉES

Wautot L., Jamar Rodriguez N., Vanderlinden E., Damien L. (2026).  
*Facteurs influençant le choix de destination Erasmus*. UCLouvain.

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.
