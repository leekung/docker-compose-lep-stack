# Docker-Compose LEP Stack
### NGinx & PHP 7.0 (--fpm)

How to use
===========

Place your project files inside the folder html locate in the souce of this project (if not there, then create the folder html).

cd into the folder you want to use, then run in the terminal:

    docker-compose up --build


Your file structure should look like this:

    - /html
        - my_project
    - /nginx
    - /php
    - /.gitignore
    - docker-compose.yml