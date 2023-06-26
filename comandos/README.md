Iniciando o projeto Django
```
python -m venv venv
.\venv\Script\Activate
pip install django
django-admin startproject project .
python manage.py startapp contact
```


configurar o git
```
git config --global user.name 'Nome'
git config --global user.email 'seuemail'
git config --global init.defaultBranch main

# configure o .gitignore

git init
git add .
git commmit -m 'mensagem'
git remote add origin url_do_projeto
```


Migrando a base de dados do Django
````
py manage.py makemigrations
py manage.py migrate
```