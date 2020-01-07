iMac-de-codeloccol:~ Daouda$ cd ~
iMac-de-codeloccol:~ Daouda$ mkdir cli_tmp
iMac-de-codeloccol:~ Daouda$ touch cli_tmp/je_suis_dans_tmp.txt
iMac-de-codeloccol:~ Daouda$ cd cli_tmp
iMac-de-codeloccol:cli_tmp Daouda$ touch in_cli_tmp.txt
iMac-de-codeloccol:cli_tmp Daouda$ mkdir in_cli_tmp
iMac-de-codeloccol:cli_tmp Daouda$ rm je_suis_dans_tmp.txt
iMac-de-codeloccol:cli_tmp Daouda$ cd ..
iMac-de-codeloccol:~ Daouda$ rm -r cli_tmp
iMac-de-codeloccol:~ Daouda$ mkdir grand_parent parent grand_frere grande_soeur ami connaissances
iMac-de-codeloccol:~ Daouda$ cd grand_frere
iMac-de-codeloccol:grand_frere Daouda$ touch bachir
iMac-de-codeloccol:grand_frere Daouda$ mv bachir ../ami
iMac-de-codeloccol:grand_frere Daouda$ cd ..
iMac-de-codeloccol:~ Daouda$ mv ami parent
iMac-de-codeloccol:~ Daouda$ pwd
/Users/Daouda
iMac-de-codeloccol:~ Daouda$ cd ~