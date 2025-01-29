---
title: Entorns de desenvolupament
# icon: fontawesome/solid/laptop-code
alias: rubriques-ed
---
# Entorns de desenvolupament

En aquesta pàgina és detallen les rúbriques tècniques o específiques del mòdul d'__Entorns de Desenvolupament__,
on es treballaran els següents aspectes:

- Diagrama UML de casos d'ús.
- [:material-source-branch-check: Control de versions][control-versions]
- [:material-marker-check: Proves del programari][proves]
- [:fontawesome-solid-gears: Automatització][automatitzacio]

[control-versions]: ../gestio/control_versions.md
[proves]: ../implementacio/proves.md
[automatitzacio]: ../implementacio/automatitzacio.md

Podeu consultar com s'integra la qualificació de cada rúbrica a la qualificació del mòdul
en els següents documents:

- [:material-book: Programació didàctica][didactica]
- [:material-book-plus-multiple: Annex 1: Avaluació dels blocs de competència][annex1]

[didactica]: https://joapuiib.github.io/daw-ed/programacio/daw1/programacio/
[annex1]: https://joapuiib.github.io/daw-ed/programacio/daw1/a1_avaluacio/

## Diagrama UML de casos d'ús
/// rubric
levels:
    - Excel·lent
    - Avançat
    - Acceptable
    - Insuficient

criteria:
    - title: Actors
      description: Identificació dels actors implicats en el sistema.
      score: 20 punts
      levels:
          - Tots els actors involucrats en el sistema s'identifiquen clarament
            i s'especifiquen les seves responsabilitats i interaccions amb el sistema. 
          - La majoria dels actors estan identificats i s'especifiquen
            les seves funcions, però amb algunes omissions o mancances en la descripció. 
          - Alguns actors podrien faltar o la seva descripció és confusa o incompleta,
            dificultant la comprensió del sistema. 
          - No s'han identificat tots els actors
            o la seua descripció és molt superficial o totalment inexistent. 

    - title: Casos d'ús
      description: Detall dels casos d'ús del sistema.
      score: 30 punts
      levels:
          - Tots els casos d'ús importants s'identifiquen i descriuen amb detall,
            incloent els seus actors associats, objectius i fluxos principals.
          - La majoria dels casos d'ús estan identificats i descriuen amb cert detall,
            però hi pot haver alguna manca d'informació o claredat en la descripció. 
          - Alguns casos d'ús podrien estar omesos o la seva descripció és massa breu
            o poc detallada, dificultant la comprensió del sistema. 
          - Hi ha una manca d'identificació o descripció dels casos d'ús,
            o la descripció és tan escassa que no aporta informació útil sobre el sistema.

    - title: Relacions entre els Actors i els Casos d'Ús
      score: 20 punts
      levels:
          - Les interaccions entre els actors i els casos d'ús es mostren clarament
            i de manera precisa, incloent els casos d'ús estesos o inclosos si és
            necessari.
          - Les relacions entre els actors i els casos d'ús són adequades,
            però podrien faltar alguns detalls o aclariments en els casos d'ús estesos o inclosos. 
          - Hi ha algunes relacions entre actors i casos d'ús, però són poc clares o incompletes,
            i potser hi ha omissions en els casos d'ús estesos o inclosos. 
          - Les relacions entre actors i casos d'ús són confuses o absents,
            dificultant la comprensió de com interactuen els diferents elements
            del sistema.

    - title: Cohesió i Coherència del Diagrama
      score: 30 punts
      levels:
        - El diagrama de casos d'ús està ben estructurat i organitzat,
          amb una distribució lògica dels casos d'ús i una clara cohesió temàtica.        
        - El diagrama de casos d'ús té una estructura adequada, però pot haver-hi
          algunes inconsistències o desordres en la distribució dels casos d'ús.
        - L'estructura del diagrama de casos d'ús és confusa o desorganitzada,
          amb manca de cohesió entre els casos d'ús i dificultats per comprendre el flux del sistema.
        - La manca de cohesió i coherència en el diagrama de casos d'ús fa que
          siga molt difícil de seguir o comprendre, amb informació dispersa
          o contradictòria.


///

## Estratègies de ramificació
## Proves unitàries amb objectes simulats
## Proves d'integració amb objectes simulats
## Automatització
