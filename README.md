# Aproximació a la diversitat vegetal

[![processa-rmarkdown](../../workflows/processa-rmarkdown/badge.svg)](../../actions?query=workflow%3Aprocessa-rmarkdown)

Per facilitar l'entrega i la correció de la pràctica sobre la diversitat vegetal
de l'assignatura de botànica, feu anar aquest repostori GitHub on trobareu els
següents fitxers que heu de modificar o reemplaçar amb les dades o el codi que
desenvolupeu com a part d'aquesta pràctica:

* `dades.csv`: fitxer CSV amb les dades (parcel.la, distància al camí, espècie i
  estrat) que heu recollit.

* `index.Rmd`: fitxer de R Markdown amb el codi, el texte que reprodueixen les
  anàlisis que se us demanen.

* `index.html`: fitxer HTML generat a partir del fitxer `index.Rmd` que mostra
  el codi, la gràfica i el texte que ho explica tot plegat.

* `README.md`: aquest mateix fitxer que esteu llegint.

Tot i que podeu afegir al repositori tots els fitxers que necessiteu,
**és important que aquests quatre fitxers hi siguin amb els noms donats**,
ja que això ens permetrà agilitzar la correcció.

Aquest repositori està equipat amb el que s'anomena un flux de treball de
_GitHub Actions_, el qual cada cop que feu _push_ en el repositori intentarà
processar el fitxer `index.Rmd`. Si el resultat d'aquest pas, que pot trigar uns
minuts, és satisfactori veureu un símbol verd de vist-i-plau a dalt d'aquesta pàgina,
i si no ho és una creu vermella. Aquests dos resultats també són visibles a través
d'una insígnia que trobareu just a sota del títol d'aquest README, i que a la vegada
és un enllaç a la pestanya del flux de treball on trobareu els detalls dels errors
que s'han trobat, si n'hi ha hagut. Si voleu que el propi flux de treball actualitzi
el fitxer `index.html`, heu d'afegir al repositori un fitxer de text buit anomenat
`.push`, però tingueu en compte aleshores que haureu d'actualitzar la vostra còpia
local del repositori (via `git pull`) per baixar-vos aquest fitxer generat.
