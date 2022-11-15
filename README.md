# DevpOps

PROJET FINALE DEVOPS .

PARTICIPANTS DU GROUPE :
-ZEBOUDJ MELISSA 
-BELMIHOUB INES SARAH
-TAFERRANT WASSIM 
-KOUFI NASSIM 

#PARITE 1 :

1-2) aprés avoir télècharger l'image python:3.6-alpine , on dois définir le répertoire /opt comme répertoire  de travail .


![Capture d’écran du 2022-11-15 09-21-25](https://user-images.githubusercontent.com/93126220/201900892-3309be11-e995-4bd2-bedf-e8f178480863.png)
![Capture d’écran du 2022-11-15 09-23-11](https://user-images.githubusercontent.com/93126220/201900970-8311c06b-003a-495c-8485-fe1de3149f14.png)


et comme on le vois dans ces images on a télècharger les images odoo et pgadmin .

Aprés on devait faire un docker build avec le nom de l'image qui nous a étais donné a l'énoncé .


   ![Capture d’écran du 2022-11-15 09-24-44](https://user-images.githubusercontent.com/93126220/201902654-7f65f4b5-4776-489e-a16d-d7cf13090918.png)
   
   
4) on dois éxposer le port 8080 avec la commande docker run :


![Capture d’écran du 2022-11-15 09-25-19](https://user-images.githubusercontent.com/93126220/201903335-8bf2fe47-703b-47d4-afa2-108f3426a6ea.png)

5)Pour créer les variables d'environnement ODOO_URL et PGADMIN_URL on a créer le dockerfile avec les informations que vous nous avez donné .


![image](https://user-images.githubusercontent.com/93126220/201904119-0b011710-ada5-4f38-8315-f5b325823497.png)


6) et pour finir avec cette premiere partie on lance l'application :


![Capture d’écran du 2022-11-15 09-29-30](https://user-images.githubusercontent.com/93126220/201904486-73ef99ed-1355-4d66-9550-2b3a4e1b08b5.png)


#PARTIE 2 :

1) On met en place un registre privé avec docker registry .


![Capture d’écran du 2022-11-15 10-38-49](https://user-images.githubusercontent.com/93126220/201904949-cdbe2b08-15af-4018-8c4c-9405d9e5b8f9.png)
![Capture d’écran du 2022-11-15 10-40-00](https://user-images.githubusercontent.com/93126220/201905351-b0cafeef-9f1b-4c72-a6dc-b82ad5ff2c36.png)


2-3) on rajoute une interface web à ce registre et une fois fais on supprime le container test  et on push notre image sur notre registre privé Docker et sur le registre dockerhub :


![Capture d’écran du 2022-11-15 10-44-20](https://user-images.githubusercontent.com/93126220/201905855-d8566ff4-f3d1-4a72-824a-c75bcd60e1eb.png)
![Capture d’écran du 2022-11-15 10-44-47](https://user-images.githubusercontent.com/93126220/201905877-131ad2ca-7d28-4069-9360-bdd266b1799d.png)


