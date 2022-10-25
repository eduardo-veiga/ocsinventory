# ocsinventory
repositório para salvar scripts, comandos , ocs a7
links uteis

neste link esta o tutorial de como instalar o ocs inventory em um container

nas pastas do diretorio contem:
*instalador para windowns
*script silencioso para windowns


https://wiki.ocsinventory-ng.org/13.Docker-documentation/Using-the-docker-image/

utilizado a imagem docker acima com os seguintes comandos

docker run -p 80:81 --name ocscon --link mariadb:mariadb -e MARIADB_DATABASE=ocsdb -e OCS_DB_SERVER=127.17.0.2 -e OCS_DB_PORT=3306 -e OCS_DB_USER=ocsuser -e OCS_DB_PASS=password -itd ocsinventory/ocsinvent                                                              ory-docker-image:latest
