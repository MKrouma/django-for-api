# Chapitre 1 : Inital Setup
Ca concerne la config de l'ordi avant de commencer son projet Django & DRF.

- Commands line
- Shell commands
- Virtual env
- Install pthon & django
- Text editor
- Version control + Git

## Command Line
Une autre facon de controler son ordi. Eviter de copier coller des commandes en ligne qu'on comprend pas.

Le built-in terminal on windows est Powershell et sur mac c'est terminal. Le shell par defaut sur MacOs est le zsh. Son signe est le %. Le $ est pour le shell bash.

## Shell commands
- cd : change directory
- pwd : print working directory
- mkdir : make directory
- clear : clear terminal
- exit : close terminal
- date : date & time
- 

[Leanring shell commands](ss64.com)

## Python
Telecharger depuis le site. Pour verifier en local, il faut taper `python -V`. 
La presence `>>>` signifie que nous sommes dans python et non en ligne de commande. Il faut dans ce cas taper du code python et non les commandes vu precedemment.

## Virtul Env
Creer des env differents avec ces versions differentes pour plusieurs projets python sur l'ordinateur. Il en faut un pour chaque projet.

Il a plusieurs moyens, mais le meilleur est le core package `venv` qui vient avec python meme.

```
python3 -m venv .venv
ls -la
source .venv/bin/activate
deactivate
```

## PyPI
Python Package Index. C'est le gestionnaire de package de python. 
```
python3 -m pip install --upgrade pip
```

Mieux d'utiliser python -m pip pour etre sur que la version desiree de python est utilisee. Pip peut alterner entre plusieurs versions pour la meme commande a chaque demande. [A lire](https://snarky.ca/why-you-should-use-python-m-pip/).


## Install django
```
python -m pip install django
cd learn_django
django-admin startproject learn_django .
python manage.py runserver
python manage.py migrate
```

## Install DRF
```
python -m pip install djangorestframework
python -m pip freeze
python -m pip freeze > requirements.txt
```

## Text Editors
Text editor est l'endroit ou le code est ecrit. Pycharm et VSCode.

## VSCode Config
- Add official python extension 
- python -m pip install black, black - code formatter
- Install black formatter extension
- Code -> Preferences -> Settings -> Default formatter -> Black formatter
- Code -> Preferences -> Settings -> Format on save -> True
- Command + Shift + P -> Shell command install `code` -> this will have a command to run vscode from terminal

Fichier est formatte lors de son enregistrement seulement.


## First DRF