# prjava02

- Instruccions per realitzar la Pràctica 3a

Exercici 1

git checkout -b branca00  // Crea i entra directament a la branca00
git status // Mostra l'estat de la branca on estem situats (branca00)

Exercici 5

git checkout master // Canvia a la branca master
git status // Mostra l'estat de la branca on estem situats (master)
git log master // Mostra l'historial de la branca master

// A la branca master no surt el darrer commit realitzat, pel fet que la modificació al codi, l'add i el commit,
s'han realitzat a la branca00.

Exercici 10

git checkout master // Canvia a la branca master

// No aparèixen els canvis relitzats a la branca00.

git merge branca00 // Fusiona la branca on estem situats (master) amb la branca00

// Ara si que aparèixen les modificacions realitzades a la branca00.

Exercici 14

git push --all origin // Puja tots els continguts del dipòsit local al dipòsit remot

// S'ha generat correctament la branca01 a GitHub, i surten els canvis realitzats.

- Respostes a les preguntes

Exercici 6

No puc veure l'última línia afegida perquè aquesta modificació ha estat realitzada a la branca00. Per tant, no es pot 
veure a la branca master (fins que no la fusionem).

Exercici 7

Es pot veure l'última línia afegida perquè la modificació l'hem realitzada des de la branca00. I, com ara estem situats
a la branca00, podem veure-la.

Exercici 12

Només s'ha actualitzat la branca master perquè aquesta encara no tenia les modificacions realitzades a la branca00.
