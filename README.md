# Projet N°1 : Analysez des données de systèmes éducatifs

## **Mise en situation :**
- **Entreprise** : Academy.
- **Logo** : ![Logo](PhotosReadme/LogoP1.png)
- **Fonction** : Propose des contenus de formation en ligne pour un public de niveau lycée et université.
- **But** : Déterminer si les données sur l’éducation de la banque mondiale permettent d’informer le projet d’expansion.
- **Jeux de données** : https://datacatalog.worldbank.org/dataset/education-statistics ou [Téléchargement direct](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Donn%C3%A9es+%C3%A9ducatives/Projet+Python_Dataset_Edstats_csv.zip)
- **Questions** : 
    - Quels sont les pays avec un fort potentiel de clients pour nos services ?
    - Pour chacun de ces pays, quelle sera l’évolution de ce potentiel de clients ?
    - Dans quels pays l'entreprise doit-elle opérer en priorité ?

- **Missions** :
    - Valider la qualité de ce jeu de données (comporte-t-il beaucoup de données manquantes, dupliquées ?)
    - Décrire les informations contenues dans le jeu de données (nombre de colonnes ? nombre de lignes ?)
    - Sélectionner les informations qui semblent pertinentes pour répondre à la problématique (quelles sont les colonnes contenant des informations qui peuvent être utiles pour répondre à la problématique de l’entreprise ?)
    - Déterminer des ordres de grandeurs des indicateurs statistiques classiques pour les différentes zones géographiques et pays du monde (moyenne/médiane/écart-type par pays et par continent ou bloc géographique)
 

## **Réalisations :**
- **Librairies** : Pandas, Matplotlib, Seaborn, Numpy, random, sklearn
- **Etapes** :
    - Ouverture des fichiers
    - Analyse de la qualité des données (df.isna(), df.info(), df.shape(), df.duplicated()...)
    - Etude de la pertinance des indicateurs en fonction de l'objectif du projet (Nb d'incateurs, Nb de pays/indicateurs, Années pertinantes...)
    - Merge des fichiers après nettoyage.
    - Réalisation de différents graphiques :
        - ![Indicateurs]()          
