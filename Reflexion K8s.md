|   |   |
|---|---|
|CKAD, edit Pods|Bei diesem Abschnitt konnte ich die Aufgaben porblemlos lösen. Ich habe einfache Pods bereits in der Schule gemacht.|
|CKAD, ReplicaSets|Bei diesem Abschnitt hatte ich keine Probleme. Ich habe Replicasets sehr gut verstanden.|
|CKAD, Deployments|Dieser Abschnitt war ein bisschen schwieriger als die vorherigen. Ich musste mir Deployments nochmal anschauen, da ich die YAML Formatierung nicht ganz im Kopf hatte.|
|CKAD, Formatting Output with kubectl|Die meisten Befehle konnte ich hier. Bei den 3 letzten musste ich auf der Kubernetes Dokumentations Seite nachschauebn. Jedoch hatte ich keine Schwierigkeiten damit.|
|CKAD, Namespace|Namespaces war für mich relativ einfach. Bei diesem Abschnitt musste ich auch Replicas und Deployments erstellen. Das habe ich bei den vorherigen Aufgaben schon gemacht. Jedoch hat es nicht geklappt. Da musste mir Bruno mit den Redis Services helfen, weil meine Redis Container nicht zusammen kommunizieren konnten.|
|CKAD, ENV Variables|Dieser Abschnitt war relativ einfach. Ich habe meine vorherigen yaml files genommen und die nötigen Variabeln gesetzt. Schwierigkeiten hatte ich keine|
|CKAD, ConfigMaps|Dieser Abschnitt war zu Beginn herausfordernd, jedoch konnte ich mich gut in das Thema ConfigMaps einlesen und konnte dementsprechend die Aufgaben gut lösen. Ich musste ebenfalls eine index.html file in mein Deployment einbauen. Da hatte ich ebenfalls keine Schwierigkeiten, da ich etwas ähnlcihes bereits gemacht habe.|
|CKAD, Secrets|Secrets war für mich neu in der Praxis. Ich habe mir nochmals die Udemy Videos zu Secrets angeschaut. En- und Decoded habe ich zum ersten Mal auf Linux. War aufjedenfall spannend.|
|CKAD, Encrypting|Dieser Abschnitt war für mich neu. Ich konnte eigentlich alles problemlos lösen. Jedoch beim reviewen von den Aufträgen mit Steven, hat er mich darauf hingewiesen, dass ich einen 3072BIT key und kein 4096BIT (wie erwünscht) erstellt habe. Deshalb musste ich den ganzen Prozess neu machen.|
|CKAD Security Contexts|Bei diesem Abschnitt musste ich viel googlen, bis ich meine Lösung gefunden habe. Jedoch war ich mir nicht sicher, ob ich die Aufgaben richtig gelöst habe, Mein Pod hat nicht gestartet, da ich den Root User rausgenommen habe. Ich habe danach Steven gefragt. Er meinte es wäre richtig gelöst, deshalb konnte ich weiter machen|
|CKAD, Service Account|ServiceAccount habe ich sehr einfach gefunden. Mit Hilfe von meinen Notizen konnte ich die Aufgaben lösen.|
|CKAD, Ressource Requirements|Da hatte ich ein bisschen Schwierigkeiten. Ich habe die Aufgaben zuerst falsch gemacht. Steven hat mich darauf hingewiesen, dass es eine einfachere und schnellere Methode gibt, CPU Limits etc. zu konfigurieren. Unzwar mit Ressources. Deshalb habe ich mich danach schlau über Ressources gemacht und konnte die Aufgaben dementsprechend lösen.|
|CKAD, Taints und Tolerations|Dieser Abschnitt ging recht schnell. Ich habe dazu mein vorheriges yaml file ergänzt.|
|CKAD, Multi Container Pods|Hier ging es auch wieder recht schnell und unkompiziert. Ich habe einen weiteren Container zu meinem Deployment hinzugefügt. Schwierigkeiten hatte ich keine.|
|CKAD Init Containers|Dieser Abschnitt war ähnlich wie der vorherige, Nur das diesmal ein Init Container und nicht ein normales Container benötigt wird. Ich habe die Udemy Videos zu init Containers erneut angeschaut und konnte damit die Aufgaben lösen.|
|CKAD, Liveness|Zu Liveness Probe habe ich mir die Kubernetes Dokumentaion durchgelesen. Ich habe das Thema rasch verstanden und konnte die Aufgaben problemlos lösen.|
|CKAD, Container Logging|Bei diesem Abschnitt ging es darum, logs von Containern anzuzeigen. Ich konnte die Aufgaben problemlos lösen. Bei dem letzen musste ich rasch auf der K8s Dokumentationsseite nachschauen.|
|CKAD, Monitoring|Dieser Abschnitt ging ganz einfach. Ich musste nur einen Befehl ausführen|
|CKAD Rolling Updates & Rollbacks|èfr diesen Abschnitt hatte ich viele Notizen bereit. Ich konnte alle Aufgaben mithilfe von meinen Notizen lösen. Ich habe dieses Thema recht gut verstanden.|
|CKAD, Jobs|Bei diesem Abshcnitt war ich sehr lange dran und musste mich mit vielen Problemen beschäftigen. Ich hatte 2 verschiedene Möglichkeiten. Bei Option 1 habe ich aufgegeben, da ich mitten drin gemerkt habe, dass dieser Weg keinen Sinn ergibt. Deshalb habe ich eine andere Methode probiert. Alles hat pronblemlos funktioniert, bis auf den test, ob der Job geklappt hat. Ich war sehr lange an diesem Problem dran. AM Ende konnte ich es mithilfe von Patrick lösen. Das Problem war, dass ich den dump auf dem Redis-Leader ausgeführt habe und nicht auf den Follower Container.|
|CKAD, Cronjobs|Diese Aufgabe war ähnlich wie der vorherige. Ich konnte mein job.yaml in mein cornjob.yaml hinzufügen und habe noch den Timer hinzugefügt. Es hat beim 1. Versuch geklappt.|
|CKAD, Services|Dieser Abschnitt wurde im Udemy Kurs verständlich erklärt, deshalb hatte ich hier keine besonderen Schwierigkeiten.|
|CKAD, Helm|In diesem Abschnitt ging es um helm. Für mich war helm etwas total neues. Deshalb habe ich mir auf Youtube Videos zu Helm angeschaut, da auf Udemy helm nicht besonders angesprochen wurde. Ich habe zuerst meine eigene Helm Umgebung aufgebaut. Später als ich mich wohl in helm gefühlt habe, habe ich mit den Aufgaben angefangen. Ich hatte zu beginn direkt einige Probleme. Ich wusste nicht weiter, deshalb musste mir Bruno weiterhelfen. Mit seiner Hilfe konnte ich mit den Aufgaben weiterfahren. Ich habe immer Stück für Stück meine helm umgebung ergänzt und nicht alles auf einmal, damit ich bei Fehlermeldungen direkt erkennen kann, an was es gelegen hat. Ich finde die Helm Fehlermeldungen nicht besonders hilfreich. Ich konnte mich rasch in helm einarbeiten. Ich bin immer noch dran meine helm Umgebung zu erweitern, obowhl ich mit meinen Aufträgen fertig bin.|