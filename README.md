# Kickstart 001

Este proyecto tiene como intención ser la base para proyectos rápidos, prototipos y pequeñas pruebas sobre el stack Grails

## El stack

- Grails 2.1.0

## Cómo configurarlo

- Hacer un fork del repo en uno nuevo (desde GitHub o a mano)

## Cómo repetir el Kickstart

    grails create-app KS-001-Grails-2.1.0
    cd KS-001-Grails-2.1.0
    git init
    grails integrate-with --git
    grails integrate-with --eclipse
    echo '/target-eclipse/' >> .gitignore