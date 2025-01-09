---
title: Proves del programari
icon: material/marker-check
alias: proves
---
# Proves del programari
Les __proves del programari__ són una part essencial de qualsevol projecte
de desenvolupament de programari. Les proves són necessàries per assegurar
que l'aplicació funciona correctament i que no es produeixen errors.

A més, ens proporciona un mecanisme per validar que el codi font compleix
amb els requisits establerts, cosa que ens permet realitzar canvis en el
codi amb la confiança que no es produeixen errors.


## Tipus de proves
Tenint en compte que el projecte està basat en una
[[arquitectura|:material-layers: Arquitectura per capes]],
es demana realitzar els següents tipus de proves:

- __Proves unitàries__: són proves que es realitzen sobre cada component
    de manera individual, per verificar que el seu comportament és correcte.

    _Per exemple, proves de la capa de domini, persistència, serveis, etc._

- __Proves d'integració__: són proves que es realitzen per verificar que
    els components funcionen correctament quan s'integren.

    _Per exemple, proves de la interacció entre la capa de domini i la de persistència._
    

## Ferramentes de proves
Per realitzar les proves del programari s'utilitzaran les següents
ferramentes:

- [:simple-junit5: JUnit5][junit5]: Llibreria per realitzar proves en Java.
- [Mockito][mockito]: Llibreria per a la creació d'__objectes simulats__.
    Aquesta ferramenta és essencial per a la realització de proves unitàries i d'integració
    de components que depenen d'altres components.
- [H2 Database][h2]: __Base de dades incrustada en memòria__ per realitzar proves 
    dels components que realitzen operacions amb la base de dades.

    Aquesta base de dades ens permet realitzar proves sense dependre d'una base de dades
    real, cosa que ens permet realitzar les proves de manera més ràpida i eficient.

[junit5]: https://junit.org/junit5/
[mockito]: https://site.mockito.org/
[h2]: https://www.h2database.com/html/main.html

## Recursos associats
