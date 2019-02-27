# base-docker-stack
1) Installer Docker
2) cloner ce repository dans son workspace
3) ce placer dans le dossier "docker-traefik-portainer" qui vient d'être cloné et lancer les commande :
```sh 
	$ docker network create proxy 
    $ docker-compose up -d
```
4) Vous pouvez accédez à portainer sur localhost:9000 et à traefik sur localhost:8080
5) Pour aller plus loin, ajouter dans votre fichier hosts les hosts que vous souhaitez conformément au fichier docker-compose.yml.
