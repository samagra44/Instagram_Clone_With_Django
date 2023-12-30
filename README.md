# Instagram Clone using HTML , CSS, JavaScript, Django

### Basic django project setup:
```
django-admin startproject instaclone
```

### Change the directory:
```
cd instaclone
```

### Create any app in django:
```
python manage.py startapp post
```

### Make changes in ```settings.py``` file:
- ```import os```
- Configure your app in InstalledApp var.
- Under *TEMPLATES* variable in *DIRS* join ```templates``` folder with **BASE_DIR**.
- ```os.path.join(BASE_DIR,"templates")```  


### Working with static files:
```
STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'static')
]

STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')

MEDIA_URL = '/media/'

MEDIA_ROOT = os.path.join(BASE_DIR, 'media')
```

### Make Migrations in Models:
```
python manage.py makemigrations
```

### Migrate the changes:
```
python manage.py migrate
```

### Create Super user:
```
python manage.py createsuperuser
```
