1. Option
```yaml
apiVersion: v1  
kind: Pod  
metadata:  
 name: myapp-pod  
  
spec:  
 containers:  
   - name: nginx  
     image: nginx  
     ports:  
       - containerPort: 80 
```


```
[aib@aib kubernetes]$ cat pod-definition.yml    

[aib@aib kubernetes]$ nano pod-definition.yml    
[aib@aib kubernetes]$ kubectl port-forward myapp-pod 8080:80  
Forwarding from 127.0.0.1:8080 -> 80  
Forwarding from [::1]:8080 -> 80  
Handling connection for 8080
```

![[Pasted image 20230803085648.png]]

2. Option

```yaml
apiVersion: v1
kind: Service
metadata:
  name: myapp-service
spec:
  selector:
    app: myapp-pod
  ports:
    - protocol: TCP
      port: 80
      targetPort: 80
```
