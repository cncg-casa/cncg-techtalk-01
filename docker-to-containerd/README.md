# From Docker to Containerd migration


#### Prerequisites :

- [Git](https://git-scm.com/downloads)
- [vagrant](https://www.vagrantup.com/downloads)
- [vitualbox](https://www.virtualbox.org/wiki/Downloads)
- [kubectl](https://kubernetes.io/docs/tasks/tools/) v1.21.0



#### Instructions :

- Browse to the lab's directory 
```
git clone https://github.com/cncg-casa/cncg-techtalk-01.git
cd cncg-techtalk-01/docker-to-containerd
```
- Create, configure, and provision your kubernetes cluster
```
vagrant up
```
- Copy the kubeconfig file in your local environment 
```
scp root@172.16.16.100:/etc/kubernetes/admin.conf ~/.kube/config
```
