# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
    ruby-3.1.2

* System dependencies

* Configuration
    1. Construir imagen de docker
        `Docker compose build`
    2. Crear contenedor a partir de la imagen recien creada
        `Docker compose up`
    3. Para crear un proyecto desde 0 inicia una consola de bash en tu recien creado contendor
        `Docker container exec -it $[ID_CONTENDOR] bash`
    4. Una vez dentro del contenedor inicia un nuevo proyecto de rails
        `rails new /app`
    5. Luego de crear la nueva base de rails inicia el servidor
        `rails s -b 0.0.0.0`

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
