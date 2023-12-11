Installation -> https://git.mgmtbi.ch/bedag/k8s-config
```yaml
git clone git@git.mgmtbi.ch:bedag/k8s-config.git
cd k8s-config
echo "source $(dirs)/bashrc" >> ~/.bashrc
source ~/.bashrc
```

```yaml
cat ~/.bashrc = export PATH="~/kubernetes/k8s-config/:${KREW_ROOT:-$HOME/.krew}/bin:$PATH"
```

```bash
[aib@aib ~]$ echo $PATH  
~/kubernetes/k8s-config/:/home/aib/.krew/bin:/usr/local/sbin:/usr/local/bin:/usr/bin:/usr/bin/site_perl:/usr/bin/vendor_perl:/usr/bin/core_perl:/var/lib/snapd/snap/bin:/home/aib/fzf/bin
```

```bash
[aib@aib ~]$ k8s-config login  
Status of k8s-prod-02: ok  
Status of k8s-prod-03: ok  
Status of k8s-prod-04: ok  
Status of k8s-prod-05: ok  
Status of k8s-prod-06: ok  
Status of k8s-prod-07: ok  
Status of k8s-prod-08: ok  
Status of kind-cluster-1: ok  
Status of kind-helm: ok  
Status of kind-kind-cluster: ok  
Status of kind-test: ok
```

```bash
[aib@aib ~]$ k8s-config  
usage: k8s-config command ...  
  
Provides list of available kubernetes tenants, generates kubeconfig  
files for easy acces on clusters and tenants and set tiller namespace  
environment variable.  
  
Usage:  
  
   get-namespace [clustername]                              (alias: gn)  
       List the namespaces. If a clustername is given, only the  
       namespaces of the given cluster is shown. The output format is:  
       <clustername> <namespace>  
  
   use-namespace <namespace> [clustername]                  (alias: un)  
       Cretes a temporary kubeconfig for the given namespace and cluster.  
       If the cluster is missing, try to find the cluster automatically.  
       If several clusters have the same namespace, a error message is  
       shown. This command is slower than use-cluster. If you know the  
       clustername, you should consider to use use-cluser.  
  
   get-cluster                                              (alias: gc)  
       List the available clusters. To add a cluster to the list, go to  
       klog and follow the login procedure for the desired cluster:  
       http://bedag.pages.mgmtbi.ch/klog/index.html  
  
   use-cluster <clustername> [namespace]                    (alias: uc)  
       Creates a temporary kubeconfig for the given cluster and sets  
       the namespace if given. Sets the environment variables:  
       KUBECONFIG and TILLER_NAMESPACE if a namespace was given.  
  
   login                                                     (alias: l)  
       Check if the cluster tokens are still valid and uses oulogin to  
       renew cluster token, if expired.
```

```bash
alias k8s-config='https_proxy=http://127.0.0.1:8888 k8s-config'  
alias kgc='k8s-config gc '  
alias kgn='k8s-config gn |grep '
```
