# silex_skeleton
PHP Silex framework skeleton with pulsion scripts

##Install

####Required : Pulsion, Composer

    pulsion install [--nginx] [--mysql]

Add options nginx and/or mysql to install their runtime. Homebrew is required

##To only generate database

    pulsion generate_database
Note : This operation is done on install command

##Test the setup

    pulsion doctor

##Start all services

    pulsion start

##Stop all services

    pulsion stop

##Restart all services

    pulsion restart

##Update php libraries, namespace autoload, and nginx/mysql runtimes

    pulsion update

