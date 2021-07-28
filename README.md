https://docs.docker.com/samples/django/


#Build:

docker-compose run web django-admin startproject composeexample .



#Database:

to replace in composeexample/settings.py

'ENGINE': 'django.db.backends.postgresql',
'NAME': 'postgres',
'USER': 'postgres',
'PASSWORD': 'postgres',
'HOST': 'db',
'PORT': 5432



#To enter in container:
docker-compose exec web sh 