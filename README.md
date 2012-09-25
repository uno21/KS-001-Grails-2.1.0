# Kickstart 001

Este proyecto tiene como intención ser la base para proyectos rápidos, prototipos y pequeñas pruebas sobre el stack Grails

## El stack

- Grails 2.1.0

## Cómo configurarlo

- Hacer un fork del repo en uno nuevo (desde GitHub o a mano)

    git clone git@github.com:uno21/KS-001-Grails-2.1.0.git my-app

- Cambiar el nombre de la aplicación en application.properties

    app.name=my_app

## Cómo repetir el Kickstart

    grails create-app my_app
    cd my_app
    
    git init
    grails integrate-with --git
    grails integrate-with --eclipse
    echo '/target-eclipse/' >> .gitignore
    
    grails install-plugin kickstart-with-bootstrap
    grails kickstartWithBootstrap