# fusion

### Installs
```pycon
pip install --upgrade pip

# python 3.10 
# installs iniciais
pip install django psycopg2-binary gunicorn dj-static django-stdimage 
pip freeze > requirements.txt

# iniciar projeto django
django-admin startproject fusion .

# iniciar aplicacao app
django-admin startapp core

# criar diretorios > templates e static

# Configurando settings 
# incluir app > core, 
# db > postgres

STATIC_URL = "static/"
STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')

# Arquivos de mídia
MEDIA_URL = '/media/'
MEDIA_ROOT = os.path.join(BASE_DIR, 'media')

# configurar fusion/urls

```