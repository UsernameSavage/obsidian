helm search hub wordpress = kubectl get
hel repo list = get helm repos in node
helm uninstall name = delete package

Reihenfolge:
helm search hub name = available hubs
helm repo add name https://charts.name.com/name = add repo
helm search repo name = repo, not hub
helm repo list = get repos
helm install [release-name] [chart-name] = install
![[Pasted image 20230829092529.png]]
helm uninstall release-name = uninstall
If you only need to download it = helm pull --untar bitami/wordpress