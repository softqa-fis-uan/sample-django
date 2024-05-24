# Ejemplo usando DJango

Incluye 

1. Creacion de una aplicacion usando django y django-restframework
1. Creacion de un contenedor para la aplicacion
1. Pruebas unitarias
1. Pruebas de backend
1. Integracion con BrowserStack
1. Integracion continua usando CircleCI y Github Actions

## Creacion de la aplicacion base usando django

1. Instalar dependencias

   ```bash
   pipenv install django djangorestframework
   ```

1. Cree un nuevo proyecto

   ```bash
   pipenv run django-admin startproject mysite
   ```

1. Ejecute el servidor de desarrollo

   ```bash
   pipenv run python mysite/manage.py runserver
   ```

1. La aplicacion esta disponible en la URL http://localhost:8000/

1. Crear una nueva app (modulo) en la aplicacion. 



### Referencias

- [Writing your first Django app](https://docs.djangoproject.com/en/5.0/intro/tutorial01/)