##### kubectl run
`kubectl run nginx --image=nginx`
##### kubectl info
`kubectl cluster-info` = Get Cluster Infos
`kbectl get nodes` = Lists all nodes
`kubectl get pods` = Lists all pods
`kubectl version --output=yaml` = Kubernetes Version
`kubectl get nodes -o wide` = You can see the OS from the nodes
`kubectl describe pod "podname"` = Describes the pods in Detail
`kubectl get rs` = Get ReplicaSets on the system
`kubectl describe replicaset` = Describes the replicaset
`kubectl get all` = All information


##### kubectl create
kubectl create -f pod-definition.yml = Creates the Pod
kubectl create -f service-definition.yml = Creates a service defined in the yaml file
kubectl expose pod redis --port=6379 --name redis-service