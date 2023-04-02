# Symfony Docker 

Prérequis 
  Avoir Docker et docker compose installés sur sa machine

## Getting Started

1. depuis le dossier racine: docker compose up -d 
2. toujours depuis le dossier racine, faire les commandes : 
    docker compose exec web composer update
    docker compose exec web bin/console make:mi
    docker compose exec web bin/console d:m:m 
    docker compose exec web bin/console d:f:l -n 
3. Vérifier si les containers sont bien lancés avec docker ps 
