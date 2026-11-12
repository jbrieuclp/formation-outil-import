# Étape 1 : importer un fichier CSV

## Fomater le fichier CSV
L'outil d'import demande à ce que le tableur importé le soit au format CSV séparé par des ; et encodé en UTF8.

## Convertir un fichier Excel en CSV par Excel
Excel permet d'exporter au format CSV. La manip est détaillée [ici](https://support.microsoft.com/fr-fr/excel/save-a-workbook-to-text-format-txt-or-csv).   
Il faut choisir le format "CSV (séparateur : point virgule)". Mais Excel ne permet pas d'exporter en UTF-8. 

Il faut alors passer par le bloc-note de Windows pour convertir l'encodage du CSV en UTF-8.  
Ou option recommandée : utiliser **Notepad++** en suivant [cette manip](https://www.nosyweb.fr/astuce-joomla/convertir-en-utf-8-avec-notepad-plus-plus.html) 

## Convertir un fichier Excel en CSV par libre office
Sous-libre office, la manip est [là](https://fiches-techniques-statistiques-9e9a16.gitlab.io/04_enregistrer_csv.html)  
* Jeu de caractères : Unicode (UTF-8)  
* Séparateur de champ : ; (point virgule)  
* Séparateur de chaine de caractère : " (double guillemet)  
* Cocher la case "Mettre en guillemets toutes les cellules de texte"

## Importer le fichier dans l'outil
![alt text](img/1-import.png)
1. Renseigner le nom de la table qui sera stocké dans la base de donnée.   

Ce nom doit être obligatoirement :
* en minuscule 
* sans espace
* avoir une lettre comme premier caractère. 

Sauf pour le premier caractère, les lettre, les nombre et l'underscore (_) sont autorisés.

Formatage recommandé : [**initial**]\_[**date (AAAAMMJJ)**]_[**contexte_très_succinct**]  
Ex : **jblp_20261112_data_formation**

2. Selectionner le fichier CSV à importer
3. Cliquer sur Envoyer
