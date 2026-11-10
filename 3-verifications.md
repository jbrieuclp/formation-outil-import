# Étape 3 : Vérification des champs

## Accéder à la vérification
Dès qu'au moins un champ du fichier a été mappé, le dashboard se complète 
![alt text](img/3-verification1.png)  
Cliquer sur l'outil "Vérifier les champs"

## Véfifier un champ
Pour chacun des champs, il faut vérifier les valeurs qu'il contient.  
Pour charger la liste des différentes valeurs, il suffit de cliquer sur l'icone oeil du champ à vérifier 
![alt text](img/3-verification2.png) 

Les vérifications du champ se font selon le mappage réalisé lors de l'étape précédentes

Les champs GeoNature sont de plusieurs types et selon, des règles de contrôles différentes s'imposent :
* le dénombrement : doit obligatoirement être un chiffre
* la date : doit obligatoirement être au format aaaa-mm-jj
* le jdd : il doit exister dans geonature
* les observateurs : doivent exister en geonature
* une valeur correspondant à une liste déroulante GN : doit faire partie de la liste
* le nom taxref : doit être présent dans TaxRef
* le nom cité : ne doit pas être null
* l'altitude : doit obligatoirement être un chiffre
* les coordonnées carto : le séparateur doit être un point et non une virgule
* un champ additionel : doit être au format JSON

Si la valeur est ok, la ligne est verte. Si elle ne l'est pas, la ligne est rouge.

## Corriger une valeur
