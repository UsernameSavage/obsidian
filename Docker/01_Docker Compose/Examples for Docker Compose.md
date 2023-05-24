![[Docker-Compose_example.png]]![[Docker-Compose_example2.0.png]]
![[Docker-Compose_example3.0.png]]
Mit build: anstatt image: kannst du ein Image im Compose File bauen indem du den Pfad angibt, wo das sich das Dockerfile befindet
![[Docker-Compose_example4.0.png]]
![[Docker-compose-example5.0.png]]


Next, create a simple container called clickcounter with the image kodekloud/click-counter, link it to the redis container that we created in the previous task and then expose it on the host port 8085 The clickcounter app run on port 5000. if you are unsure, check the hints section for the exact commands.

version: '3'
services:
  clickcounter:
    image: kodekloud/click-counter
    ports:
      - 8085:5000
    links:
      - redis

  redis:
    image: redis
