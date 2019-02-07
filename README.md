# Recipe for docker django single app

this recipe allows to run a django application without libraries for images or else. Its too simple and only for development

# What do you need

this recipe needs a structure in with three directories:
src, var and etc

## src

contains the projects django itself and here is where have been place settings.py

## etc
contains external files that application doesn't need like requirements.txt

## var
contains external files that provides data like a sql directory

# Settings
you need to change the vars PROJECT_NAME on every dockerfile with the name of the main directory that contains the structure mentioned before, thats all.

# How to run 

in this example:
## compose
docker-compose up