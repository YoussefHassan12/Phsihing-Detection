# Phsihing-Detection

Le projet consiste en deux fichiers Python : "features_extractions.ipynb" et "classification_models.ipynb".

Le fichier "features_extractions.ipynb" utilise "top500Domains.csv" pour obtenir 500 liens légitimes et scrappe 500 liens non légitimes pour extraire des features. Ces features sont ensuite enregistrées dans un dataset appelé "urldata.csv".

Le fichier "classification_models.ipynb" lit "urldata.csv" et entraîne des modèles de classification pour prédire le phishing. Il lit également un jeu de données plus important appelé "full_url_data.csv" pour étudier l'importance des features.
