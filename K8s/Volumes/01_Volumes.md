In k8s when you delete the pod, the volume will be gone as well. Thats why we create a Persistent Volume (PV) to mount the data into our local file:
![[Pasted image 20230824111341.png]]
In this case the container creates number.out in /opt
Then we create a volume local on our device named data-volume under /data
With volumeMounts we create a Persistent Volume Claim (PVC). With PVC you tell the container you can acess data-volume in our local /data