# wirds-2021-binder-przyklad
#REPOZYTORIUM NA POTRZEBY PRZEDMIOTU WIRDS 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kameckif/wirds-2021-binder-przyklad/main?urlpath=rstudio)


Aby blinder działał potrzebuje następującego pliku :

1.'runtime.txt' == okreslamy z jakiejs wersji R będziemy korzystać oraz z jakiego dnia mają być pakiety (np.'r-2021-01-01','r-3.6-2021-01-01'

Możemy założyć jakie pakiety mają być w ramach tego obrazu. W takim razie powinniśmy utowrzyć plik o nazwie 'install.R', który będzie zaweirał skrpyt R do instalacji pakietów.
Na przykład :

'''r
install.packages("tidyvere")
install.packages("data.table")
install.packages("sf")
install.packages("rio")
'''r
