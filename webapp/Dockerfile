FROM ubuntu:20.04
LABEL description = 'Servidor de PHP/webapp for commit '
ARG DEBIAN_FRONTEND=noninteractive
RUN apt update 
RUN apt upgrade -y
RUN apt-get install -y php-fpm
RUN apt-get install -y php-sqlite3 
RUN apt install -y sqlite3 
