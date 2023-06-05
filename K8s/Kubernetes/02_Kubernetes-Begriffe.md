##### worker
- A worker machine is known as a Node or Minion in K8s

##### apiserver
- Kube-apiserver processes runs on Kubernetes Master Node
- acts like a frontend for k8s, all talk to the api server to interact with k8s
##### etcd
- etcd  is a distributed reliable key-value store used by k8s to store all data used to manage the cluster
###### scheduler
- The scheduler is responsible for distributing work or containers across multiple nodes

##### Kubernetes Controller
- The Controllers are the brain behind the orchestration
- Controller are responsible for noticing and responding when stuff goes down
##### Container runtime
- Container runtime is the underlying framework that is responsible for running application in containers like Docker


##### kubelet
- Is the agent that runs on each nodes on clusters, it makes sure that everything is running
##### The Command kubectl describe
with the command "describe" you can see:
- All the Containers running on the pod
- ![[kubectl-describe3.0.png]]
- IP of the Pod And Node
- ![[kubectl-describe2.0.png]]
- The state/status of the containers on the pod
- ![[kubectl-describe.png]]