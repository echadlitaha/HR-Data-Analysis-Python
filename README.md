# Analyse RH et démographique avec Python

## Présentation du projet

Ce projet consiste à analyser les données de 650 employés afin d'explorer la répartition des effectifs, les différences de rémunération et les taux de promotion au sein d'une entreprise.
L'objectif est de transformer les données RH en indicateurs pertinents pour faciliter la prise de décision.

## Objectifs

- Analyser la répartition des employés par département et par genre.
- Étudier les différences salariales entre départements.
- Comparer les rémunérations des femmes et des hommes.
- Examiner les taux de promotion selon le genre et le département.
- Formuler des recommandations RH à partir des résultats observés.

## Technologies utilisées

- **Python** : analyse des données.
- **Pandas** : nettoyage, manipulation et agrégation.
- **NumPy** : opérations numériques.
- **Matplotlib et Seaborn** : visualisation.
- **Jupyter Notebook** : développement et présentation de l'analyse.

## Jeu de données

Le dataset contient 650 employés répartis dans 6 départements et 19 catégories de postes.
Les variables étudiées comprennent notamment le département, le genre, l'âge, l'expérience professionnelle, le salaire mensuel, la satisfaction, la performance et les promotions.

## Méthodologie

L'analyse a été réalisée en quatre phases :

1. **Audit et nettoyage** : recherche des doublons, contrôle des valeurs manquantes et vérification des données atypiques.
2. **Analyse descriptive** : calcul des effectifs, salaires moyens et médians, et taux de promotion.
3. **Visualisation** : création de quatre graphiques pour comparer les principaux indicateurs RH.
4. **Interprétation** : identification des écarts observés, recommandations et limites de l'analyse.

## Principaux résultats

| Indicateur | Résultat |
|---|---|
| Nombre d'employés | 650 |
| Nombre de départements | 6 |
| Salaire médian global | 14 900 MAD |
| Département le plus représenté | Sales : 158 employés |
| Salaire médian Data | 17 200 MAD |
| Salaire médian RH | 12 600 MAD |
| Taux de promotion des femmes | 13,99 % |
| Taux de promotion des hommes | 10,71 % |

L'analyse met également en évidence un écart de salaire médian de 1 425 MAD en faveur des hommes dans le département Finance.

Ces résultats sont descriptifs et ne permettent pas, à eux seuls, d'établir l'existence d'une discrimination.

## Visualisations

Le notebook présente quatre graphiques :

1. Répartition des effectifs par département.
2. Comparaison des salaires moyens et médians par département.
3. Comparaison des salaires médians par département et par genre.
4. Taux de promotion par département et par genre.

## Recommandations et limites

L'analyse suggère de poursuivre l'étude des écarts salariaux en tenant compte des postes, de l'expérience et des niveaux de responsabilité, et de suivre les promotions par département.

Certaines données sont manquantes : 13 scores de satisfaction et 9 scores de performance. Les comparaisons réalisées ne contrôlent pas simultanément l'ensemble des facteurs susceptibles d'expliquer les différences observées.

## Exécution du projet

Le projet nécessite Python, Jupyter Notebook et les bibliothèques Pandas, NumPy, Matplotlib et Seaborn.

Le notebook utilise le fichier `J23_dataset_employes.csv`, qui doit être accessible dans son répertoire d'exécution.

Pour reproduire les résultats, ouvrir le notebook dans Jupyter et exécuter toutes les cellules dans l'ordre.

**Remarque :** le jeu de données ne doit être publié que si sa diffusion est autorisée et ne révèle aucune information personnelle confidentielle.