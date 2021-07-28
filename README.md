<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- 
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Richi2293/DjangoDockerStarter">
    <img src="https://freepikpsd.com/media/2019/10/django-png-6-Transparent-Images.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">DjangoDockerStarter</h3>

  <p align="center">
    From docs.docker.com
    <br />
    <a href="https://docs.docker.com/samples/django/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <!-- 
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
    -->
  </p>
</p>



### Build command:

```
docker-compose run web django-admin startproject composeexample .
```

### Database settings:

to replace in composeexample/settings.py

```
'ENGINE': 'django.db.backends.postgresql',
'NAME': 'postgres',
'USER': 'postgres',
'PASSWORD': 'postgres',
'HOST': 'db',
'PORT': 5432
```

### Command to enter in container:

```
docker-compose exec web sh
```