# FHEM_docker
FHEM-Docker-Base

Contains

    FHEM     
    mySQL-Logging

Requirements

    Docker
    Docker-Compose

Install

    git clone https://github.com/octabia/FHEM_docker.git fhem-docker
    cd fhem-docker
    cp ./fhem/data/fhem.cfg.example ./fhem/data/fhem.cfg
    docker-compose up

Defaults

    FHEM-WEB: 8083 (8084 and 8085 have been deleted)
    mySQL-User: fhemuser
    mySQL-Password: 2jRHnEi3WuNSQAcX7
    
Updating FHEM

    Since all data in the container is static, you have to delete the container
    and recreate it to update fhem.

