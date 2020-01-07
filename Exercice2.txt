iMac-de-codeloccol:~ Daouda$ pwd
/Users/Daouda
iMac-de-codeloccol:~ Daouda$ ls 
Applications	Downloads	Music		connaissances	grande_soeur
Desktop		Library		Pictures	grand_frere	parent
Documents	Movies		Public		grand_parent
iMac-de-codeloccol:~ Daouda$ mkdir conteneur
iMac-de-codeloccol:~ Daouda$ cd conteneur
iMac-de-codeloccol:conteneur Daouda$ mkdir voitures ustensiles electronique
iMac-de-codeloccol:conteneur Daouda$ cd voitures
iMac-de-codeloccol:voitures Daouda$ touch mes_voitures.txt
iMac-de-codeloccol:voitures Daouda$ echo "benz toyota honda">>mes_voitures.txt
iMac-de-codeloccol:voitures Daouda$ cd ..
iMac-de-codeloccol:conteneur Daouda$ cd ustensiles
iMac-de-codeloccol:ustensiles Daouda$ touch cuisine.txt
iMac-de-codeloccol:ustensiles Daouda$ echo "cuillere marmite couteau">>cuisine.txt
iMac-de-codeloccol:ustensiles Daouda$ cat cuisine.txt
cuillere marmite couteau
iMac-de-codeloccol:ustensiles Daouda$ cd ..
iMac-de-codeloccol:conteneur Daouda$ ls -a
.		.DS_Store	ustensiles
..		electronique	voituress