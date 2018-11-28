# Banff Mining
### V1
Robin Masliah & Gillian Divard
---

### Méthode 1

- Scrapping des données brutes.
- Création dataframe.
- Export CSV.<br/>
![Image](scrap.png)
<br/>
- Base de référence.
---

### Méthode 1
![Image](banff_encoded.png)
![Image](doc.png)
---
### Méthode 1
Cleaning :
- Split des phrases.
- Interactions avec le dictionnaire.
- Suppression des stop words.
- Purification des phrase au maximum pour faciliter la recherche.
- Ex : Vessels: The  cv  show focal  2  intimal  fibrosis.<br/>
-> devient :  'cv 2'
<br/>cv = 2
<br/>
- Ajout dans la table.
---
### Méthode 1
Erreur :
- Sur 5 textes > Environ 10-20% d'erreur.
---
### Méthode 2
- Vectorisation des phrases.
- Désambiguation.
- Étude du contexte.
---
### Méthode 2
- Création de la métrique de validation.
---
### À suivre...
- Déterminer l'innacceptable.
- Étude text mining.
- Gérer les clefs uniques patient-pdf-hôpital.
