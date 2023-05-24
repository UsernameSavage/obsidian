##### worker
- A worker machine is known as a Node or Minion in K8s
##### apiserver
- Kube-apiserver processes runs on Kubernetes Master Node
##### etcd
- etcd  is a distributed reliable key-value store used by k8s to store all data used to manage the cluster
###### scheduler
- The scheduler is responsible for distributing work or containers across multiple nodes

##### Container runtime
- Container runtime is the underlying framework that is responsible for running application in containers like Docker


##### The Command kubectl describe
with the command "describe" you can see:
- All the Containers running on the pod
- ![[kubectl-describe3.0.png]]
- IP of the Pod And Node
- ![[kubectl-describe2.0.png]]
- The state/status of the containers on the pod
- ![[kubectl-describe.png]]