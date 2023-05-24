When you first create a Deployment it triggers a Rollout. A new Rollout creates a new Deployment Revision. With every Update it creates a new Revision to help us track the changes of the previous versions

##### Rollout Commands
kubectl rollout status deployment/deployment-name = Status of Rollout
`kubectl rollout history deployment/deployment-name` = History of Rollout

#### Create, Get, Update, Status, Rollback Commands
![[k8s-Update4.0.png]]