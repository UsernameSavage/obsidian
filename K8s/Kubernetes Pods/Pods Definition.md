- A Pod is a single instance of a application
- A Pod is the smallest object that you can create in kubernetes

- If the number of user that want to access your pod increases, you dont create a new instance in the pod, you create a new pod with the same instance as the first one that runs on the same k8s node. Here an example: ![[k8s-Pod.png]]