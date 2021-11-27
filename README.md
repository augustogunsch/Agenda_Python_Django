## Agenda_Python_Django

#### Objetivo:
Este projeto tem como objetivo criar uma agenda estilo to-do list com Python Django. 

![Screens](https://i.imgur.com/KDryu8r.png "Screens")

#### Instalando e rodando o projeto (Linux)
Instale o Django numa virtualenv:
```
$ python -m virtualenv venv
$ source venv/bin/activate
$ pip install django
```
Crie o banco de dados:
```
$ python manage.py migrate
```
Crie um usuário administrador (com o qual logará na tela de login):
```
$ python manage.py createsuperuser
```
Rode o servidor de desenvolvimento:
```
$ python manage.py runserver
```
Agora é só entrar pelo navegador em `http://localhost:8000`!
