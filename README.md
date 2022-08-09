# CBIR
Content Based Image Retrieval 

| **Fichier**          | **Desciption**                                            |
|----------------------|-----------------------------------------------------------|
| feature_extractor.py | Fonction d'extraction de features VGG16                   |
| offline.py           | Parcourir la base de données et extraire les descripteurs |
| cluster.py           | Clustering avec KMeans                                    |
| offline_features.py  | Matcher chaque cluster avec ses images et leurs features  |
| server.py            | Serveur Flask                                             |
| centroids.pkl        | Les centroides de chaque cluster                          |
| requirements.txt     | Liste des dépendances                                     |
| rapport.pdf          | Rapport détaillant le projet                              |


| **Dossier**             | **Desciption**                                                       |
|-------------------------|----------------------------------------------------------------------|
| static                  |                                                                      |
|              static/img | Base de données de 1 million d'images                                |
|          static/feature | Base de données des features de chaque image sous format Numpy       |
|          static/results |                                                                      |
| static/results/features | Contient les features des images de chaque cluster sous format Numpy |
|  static/results/imgfile | Contient les paths correspondants                                    |
| templates               | Contient le fichier index.html                                       |
