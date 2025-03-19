Iniciar o projeto Django

```
python -m venv venv
. venv/bin/activate - mac linux
.\venv\Scripts\activate --> windows
pip install django
django-admin startproject project .
```

Configurar o git

```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
# Configure o .gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
git add . 
git commit -m 'upload repository'
git push origin main
- Caso ocorra um erro, tente levar para o pc os arquivos que existem no repositório online:
    - git pull origin main –rebase
    - Agora, faça novamente o push:
    - git push origin main
```

Iniciar o projeto, depois do git:
```
Com o Git OK:
- python manage.py startapp contact --> cria o aplicativo de contact
```
