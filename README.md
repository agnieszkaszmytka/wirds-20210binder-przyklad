# Repozytorium na potrzeby przedmiotu WIRDS 2021

Aby binder działał potrzebuje następującego pliku:
1. runtime.txt -- określamy z jakiej wersji R będziemy korzystać oraz z jakiego dnia mają być pakiety (np. r-2021-01-02)


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/agnieszkaszmytka/wirds-20210binder-przyklad/main?urlpath=rstudio)

Możemy założyć jakie pakiety mają być w ramach tego obrazu. W takim razie powinniśmy utworzyć plik o nazwie install.R, który będzie zawierał skrypt R do intalacji pakietów. Na przykład:

install.packages("tidyverse")
install.packages("data.table")
install.packages("sf")
install.packages("rio")
