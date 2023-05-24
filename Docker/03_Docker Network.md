*Netzwerke auflisten*
`docker network ls` = Listet alle Netzwerke auf dem System auf

*Netzwerk vom Container herausfinden*
Um herauszufinden, welches auf welchem Netzwerk der Container läuft: `docker inspect containername` ganz unter unter "Networks"

*Netzwerk untersuchen*
mit `docker network inspect bridge/host/none` findest du informationen zum Netzwerk z.B Subnetzmaske, Gateway usw.

*Netzwerk zuteilen*
`docker run --network bridge --name alpine-2 alpine` = Netzwerk zuteilen Teilt dem Container ein Netzwerk zu via Befehl

*Netzwerk erstellen
`docker network create --driver bridge --subnet 182.18.0.1/24 --gateway 182.18.0.1 wp-mysql-network` = Erstellt ein Bridge Netzwerk inklusive Subnetz und Gateway  
