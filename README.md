17a3c689537a ID 17a3c689537a
/workspace/docker.com/webapp
# Dockerfile
docker commit 17a3c689537a 
docker run -it -p 8080 -v /workspace/docker.com/webapp:/webapp --name php -h php ubuntu:20.04
ubuntu:20.04
apt-get update 
apt-get install php
apt-get install php-sqlite3
apt-get install sqlite3
docker build -t tarea_1:v1 .e
php -S 0.0.0.0:8080
docker start ID -i
FROM    ubuntu:bionic
LABEL   description = 'demo dockerfile'
RUN     apt update 
RUN     apt upgrade -y 
RUN     apt install -y python3
RUN     apt install -y python3-pip
RUN     pip3 install web.py
#docker save mi_imagen:v1 .
## Save image
#'''bas
#docker sabe mi_imagen > mi_imagen.tar.gz
#docker rmi _mi_imagen:v1
#docker rm ID
#$ docker rm ID
#docker load -i mi_imagen.tar.gz

#//Para gitnore
#*.pyc
#__pycache__
#*.tar.gz
docker run -d --name servidor_apache -h servidora_pache debian_9_apache bash -c "apache2ctl -D FOREGROUND"# docker.com
