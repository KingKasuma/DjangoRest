## Para hacer correr el proyecto
* npm install (instalar las dependencias del package.json)
* pipenv install (instalar las dependencias del Pipfile)(ojo primero se tiene que estar en el pipenv shell)

## Comandos para el proyecto (Django)
* pipenv shell (para activar el entorno virtual)
* pipenv install django djangorestframework django-rest-knox (instalar dependencias con pipenv)
* django-admin startproject leadmanager (para iniciar un proyecto con django)
* python manage.py startapp leads (crea una app para el proyecto llamado leads)
* python manage.py makemigrations leads (crea las migraciones de la app leads)
* python manage.py migrate (añade las migraciones a la base de dato s)

## Comandos para el frontend (React)
* npm init -y (create a package.json file for dependencies)
* npm install -D webpack webpack-cli (instala  y añade las dependencias al package.json como devDependencies)
* npm install -D @babel/core babel-loader @babel/preset-env @babel/preset-react babel-plugin-transform-class-properties
* npm i react react-dom prop-types (instala las dependencias)
* npm i react react-dom prop-types (instala las dependencias)
* npm i redux react-redux redux-thunk redux-devtools-extension
* npm run dev (para correr el script que actualiza el webpack que esta configurado en el package.json)