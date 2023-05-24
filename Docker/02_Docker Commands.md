##### Docker run
`docker run nginx` = looking for locally, then pulling from the web with running
`docker run  -d yyy/webapp` = "-d" = dettached
`docker run -it centos bash`  = loggt sich in das centos bash ein
`docker run -p 8282:8080 -t webapp-color` = Host Port: 8282 ext), Container Port: 8080(int)
`docker run -d --name blue-app -p 38282:8080 -e APP_COLOR=blue imagename` = mit -e kannst du im Dockerfile eine Variable ändern
`docker run -d --name=clickcounter --link redis:redis -p 8085:5000 kodekloud/click-counter`  = 2 Container miteinander Linken
["ENTRYPOINT"]= ex. ENTRYPOINT ["sleep"] = `docker run ubuntu-sleeper 10` Mit ENTRYPOINT kannst du eine Variable erstellen die im Befehl eingegeben wird
##### Docker pull
`docker pull nginx` = pulling nxing image without running
##### Docker stop
`docker stop imagename` Stoppt Image
##### Docker rm
Container mit `docker rm containername` entfernen = Image läuft nicht mehr
`docker rm 7c8 29b 5c4 3f6 704` = Entfernt mehrere Container
##### Docker ps
`docker ps` = Zeigt Images an
`docker ps -a`=  Zeigt alle Images an, ob sie laufen oder nicht
##### Docker image
`docker image ls` = Listet Images
`docker image build -t webapp-123 .` = Erstellt ein Image mithilfe eines Dockerfiles im Verzeichnis
`docker image build -t webapp-123 "path"` = Erstellt ein Image mithilfe eines Dockerfiles der sich im angegebenen Pfad befindet
##### Docker info
`docker version` = Docker Version
`docker exec e015 cat /etc/*release*` = Lists the Dockerfile
`docker inspect containername` = Inspecting the Dockerfile

