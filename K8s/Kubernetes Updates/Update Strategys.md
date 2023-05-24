##### Recreate Updates
Recreate Updates destroys all applications at once and create new ones. During the time, the applications are not available for anyone. - bad
You can see on the events that the replica set was set from 5 to 0 and then from 0 to 5
![[k8s-Update.png]]
##### Rolling Updates
Rolling Update is the default Update strategy by kubernetes. Bei Rolling Updates handelt es sich um eine Lösung, indem die Applikationen stück für stück geupdated werden und nicht alle auf einmal. Das ermöglicht User immernoch auf die Applikationen zuzugreifen während des Updates - good
You can see on the events that the replica set was set from 5 to 2, from 2 up to 4..
![[k8s-Update2.0.png]]