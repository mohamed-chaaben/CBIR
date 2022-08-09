Fichier				Description
-------------------------------------------------------------------------------------
feature_extractor.py		Fonction d'extraction de features VGG16
offline.py			Parcourir la base de données et extraire les descripteurs
cluster.py			Clustering avec KMeans
offline_features.py		Matcher chaque cluster avec ses images et leurs features
server.py			Serveur Flask
centroids.pkl			Les centroides de chaque cluster
requirements.txt		Liste des dépendances


Dossier				Description
-------------------------------------------------------------------------------------
static				
 - img				Base de données d'images
 - feature			Feature de chaque image
 - results
     - features			Contient les features des images de chaque cluster
     - imgfile			Contient les paths correspondants

templates			Contient le fichier index.html