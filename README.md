# Inicializacion
Levantar con ``docker-compose up``

Es necesario tener la variable de entorno:

``export PROJECT_L_DATABASE_URL=mongodb://localhost:27017,localhost:27018,localhost:27019/project-l-db?replicaSet=replicaset``

 Además es necesario añadir a /etc/hosts las siguientes entradas para poder conectarse desde Robo3T al clúster.

 ``
127.0.0.1 mongodb-primary
127.0.0.1 mongodb-secondary
127.0.0.1 mongodb-arbiter
``