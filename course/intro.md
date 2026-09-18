# Introduction
On va utiliser Django pour tes projets web principalement. 
Django s'integre avec des packages dont DRF permet de transformer en API.

Entreprise avec Django :
- Insta, Mozilla, Pinterest.

Rapid & secure development. DRF -> small amount of code and time.

Prerequis : Django for begineers + Python.

## DRF
Django n'a pas de built-in function pour dev des APIs. DRF est cree en OS et maintenu par des devs independants de Django.

DRF s'integrent avec tout le coeurs de Django : models, views, url et template. Mais il integre deux nouvelles notions :
- DRF Serializers : queryset + model = json (serialization) -> de-serialization
- DRF Views : Django views + serializers = Expose URLS. Viewsets + Routers = common cases.

DRF est un des packages les plus importants de Django. Toutefois, une liste est dispo [ici](https://github.com/wsvincent/awesome-django).

Techniquement DRF est separe du corebase de django. Mais dans les faits, ils sont inseparables. DRF est tres mature, mis a jour reguliremenet et en contact etroit avec ls gens de Django.


## Rest API
C'est un ensemble de regles qui definissent comment des ordinadeurs ou programmes interagissent et communiquent entre eux.
API - Application programming interface
REST - Representational State Transfer

REST - un style d'architecture avec des standards pour le WWW.
REST trois criteres : 
- Separation client / server;
- Stateless : pas d'historique;
- Uniform interface - uniforme URI.

Django a ete lance en 2005. Il est ne dans un env de server-side temlates rendering. Donc il a juste adopte ca comme pattern au debut.

Maintenant, les sites adoptent le API-first approche qui est de separer le front-end et le backend. Comme ca, tous types de JS framework peuvent se connecter a l'API et meme le mobile.

Un backend Django -> supportent plusieurs differents / types de clients frontends.

Le souci avec une approche API -> il genere plus de configurations et complexite qu'une app django simple. Mais DRF permet de bien gerer ca.


## Why 
Manque de ressources fiables sur DRF.


## Ressources 
[Code](https://github.com/wsvincent/djangoforapis)

