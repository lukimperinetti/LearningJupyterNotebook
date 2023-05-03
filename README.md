# Introduction à Jupyter Notebook

**French :**
Ce projet est proposé par Dataquest.io. Il consiste en l'apprentissage de Python pour la data science et en la découverte de JupyterNotebook

*résumé : récupération d'un dableau regroupant toutes les évasion de prison a l'aide... d'un hélicoptère ! ce tableau de données ce trouvant sur Wikipédia, j'ai utilisé une fonction de récupération de donnée via l'url.
A noter que DataQuest utilise un module custom pour ca. vous le trouverez dans helper.py. Sinon il faut utiliser urllib ou autre.*

**Tout d'abord, il me faut importer le module helper.py.<br>
Je vais en suite réccupérer les données via l'url et afficher seulement les premières lignes pour voir si tout fonctionne.**
![alt tag](https://user-images.githubusercontent.com/40659534/235873379-e2400c52-6ca9-4cd2-815d-e89d6a9cfaf4.png)

**le row[:-1] mes permet d'éviter de réccupérer la dernière colone qui est une longue description du prisonnier**
<br><br>
**Maintenant, je format mes cellules pour n'avoir que l'année plutot que la date complète. ca me servira a trier mes données dessus**

![alt tag](https://user-images.githubusercontent.com/40659534/235873384-3b635e7c-4354-40de-9526-17d49ffaa821.png)

**Il faut en suite trier les dates dans l'ordre croissant, enlever toutes les infos et ne garder que le nombre de tentatives par an.**
<br>
**J'utilise la fonction anonyme ce dessous pour créer une limite a mon tri. ce point reste encore assez flou je suis en train de lire la doc pour etre sur de bien comprendre.**
![alt tag](https://user-images.githubusercontent.com/40659534/235873385-8bd30ca4-f0f0-4626-9096-6f9446811b68.png)

**ici j'affiche toutes les dates dans l'ordre avec un nombre de tentatives par défaut a 0 : **
![alt tag](https://user-images.githubusercontent.com/40659534/235873387-d519e2b0-9213-4b43-a935-f54d19862f39.png)

**J'affiche maintenant le nombre de tentatives en fonction de l'année**
![alt tag](https://user-images.githubusercontent.com/40659534/235873390-3ee894fc-f2be-4caf-ba9c-82d8aad13b6f.png)

**Voici deux façon de rendre ces données lisible. je n'en n'affiche ici qu'une partie, mais vous trouverez la totalité des informations dans le basics.ipynb**
![alt tag](https://user-images.githubusercontent.com/40659534/235873391-8c9c015d-d38f-42d1-a4ac-07174b39056c.png)
![alt tag](https://user-images.githubusercontent.com/40659534/235873392-78427ca5-6728-4d4c-8568-0811975e5918.png)

**Voila tout, il ne me reste plus qu'a m'amuser a récupérer des données un peu partout !**
