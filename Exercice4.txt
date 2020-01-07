iMac-de-codeloccol:~ Daouda$ pwd
/Users/Daouda
iMac-de-codeloccol:~ Daouda$ touch .configuration
iMac-de-codeloccol:~ Daouda$ ls -a
.			Applications		actualites
..			Desktop			connaissances
.CFUserTextEncoding	Documents		conteneur
.DS_Store		Downloads		grand_frere
.Trash			Library			grand_parent
.bash_history		Movies			grande_soeur
.bash_sessions		Music			mes_camarades.txt
.configuration		Pictures		parent
.vscode			Public
iMac-de-codeloccol:~ Daouda$ mkdir -p creations/crayons
iMac-de-codeloccol:~ Daouda$ cd creations/crayons
iMac-de-codeloccol:crayons Daouda$ touch couleurs.txt
iMac-de-codeloccol:crayons Daouda$ mv couleurs.txt colors.txt
iMac-de-codeloccol:crayons Daouda$ cd ..
iMac-de-codeloccol:creations Daouda$ touch gomme.txt
iMac-de-codeloccol:creations Daouda$ mv gomme.txt ../crayons
iMac-de-codeloccol:creations Daouda$ cd ~
// le chemin de creation est Daouda/creations//