##### Create
`kubectl create -f replicaset-definition.yml` = Creates a replicaset from the file
##### Get
`kubectl get replicaset` = Lists all replicasets
##### Delete
`kubectl delete replicaset replicaset-name` = Deletes the replicaset, also all underlying PODs
kubectl replace
##### Replace
kubectl replace -f replicaset-definition.yml = Replace or Update replicaset
##### Scale
kubectl scale --replicas=6 -f replicaset-definition.yml = Scale the pods up to 6