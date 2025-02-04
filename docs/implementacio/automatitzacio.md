---
title: Automatització
icon: fontawesome/solid/gears
alias: automatitzacio
---

*[CI]: Continuous Integration
*[CD]: Continuous Deployment

# :fontawesome-solid-gears: Automatització
Un aspecte clau en la __integració contínua i desplegament continu (_CI/CD_)__ és l'automatització
de tasques. Aquestes tasques poden incloure:

- Realitzar validacions en el funcionament del sistema.
- Compilar els binaris i empaquetar-los.
- Realitzar el desplegament.

## Tasques automatitzades en el projecte
En aquest projecte, s'utilitzara [:octicons-play-16: GitHub Actions][actions] per automatitzar les següents tasques:

- Executar les [:material-marker-check: Proves del programari][proves] quan una
    :material-source-pull: _Pull Request_ estiga preparada per a ser revisada.
- Executar validacions d'estil en el codi font quan una
    :material-source-pull: _Pull Request_ estiga preparada per a ser revisada.
- Compilar i empaquetar el codi del projecte quan es realitze un nou
    [:material-tray-arrow-up: Llançament (_Release_)][releases].

[proves]: proves.md
[actions]: https://github.com/features/actions
[releases]: https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases
