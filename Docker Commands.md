Container mit `docker rm containername` entfernen = Image läuft nicht mehr
`sudo docker ps` = Zeigt Images an
`sudo docker image ls` = Listet Images
`sudo docker version`
`docker ps -a`=  Zeigt alle Images an ob sie laufen oder nicht
`docker stop imagename` Stoppt Image
`docker rm containerID` = Stoppt Container
`docker pull nginx` = pulling nxing image without running
`docker run nginx` = looking for locally, then pulling from the web with running
`docker run  -d yyy/webapp`
`sudo docker run -it centos bash`  = loggt sich in das centos bash ein
`docker rm 7c8 29b 5c4 3f6 704` = Entfernt mehrere Containet
`docker exec e015 cat /etc/*release*` = Zeigt das Dockerfile an