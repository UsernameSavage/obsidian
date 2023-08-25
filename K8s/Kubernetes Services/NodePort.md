With NodePort you can easily access your PODs inside your Cluster. You define the NodePort in the service.yaml file. If you dont define the NodePort it will chose a port between 30000 and 32767 by default. On the ScreenShot below you can see how NodePort works.
![[k8s-NodePort.png]]
Now you can access your Node with ://NodeIPAddress:30008
Port Range; 30000 - 32767

It uses a algorithm to balance load the 3 diffrent PODs
![[k8s-NodePort2.0.png]]

![[k8s-NodePort3.0.png]]