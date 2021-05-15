# Recherche de corrélations entre prix du loyer et répartition des associations dans Paris Intramuros
Groupe 6 : Raphaël Robert, Léo Sablong, Zhifeng Liang, Etienne Roseau, Loïc Amiand et Alexis Da Mota.

Consignes : 
1. A l'aide de 2 datasets (ou plus) de votre choix (provenant de Kaggle ou autres sources), établissez 3 analyses permettant de mettre en avant des corrélations entre les différents datasets

2. Chaque analyse devra :
    - être faite à l'aide de PySpark avec soit des RDD ou des DataFrames
    - comporter une représentation graphique de votre choix

# Objectif
Le but de l'analyse est de trouver des corrélations entre les prix des loyers dans Paris Intramuros et le nombre d'associations ainsi que leur domaine d'activité pour chaque arrondissement.

# Datasets
Nous avons téléchargé trois datasets depuis : https://opendata.paris.fr/   
    - https://urlz.fr/fdWY (Encadrement des loyers parisiens en 2019)   
    - https://urlz.fr/fdX5 (Liste des associations parisiennes)   
    - https://urlz.fr/fdYW (Données géographiques surfaciques de Paris)   

# Installations requises
```
!sudo apt-get update  
!sudo mkdir -p /usr/share/man/man1  
!sudo apt-get install -y openjdk-11-jdk  
!pip install pyspark  
!pip install import-java  
!pip install geopandas
```
