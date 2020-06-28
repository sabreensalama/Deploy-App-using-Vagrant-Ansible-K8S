# Deploy-App-using-Vagrant-Ansible-K8S
#Steps
```
vagrant up
```

```
vagrant provision
```

```
vagrant ssh k8s-master
```
```
- vagrant ssh node-1
- kubectl create -f python-deployment.yml redis-deployment.yml
- kubectl create -f service.yml redis-svc.yml

```

# Final Output
![output of app](https://github.com/sabreensalama/Deploy-App-using-Vagrant-Ansible-K8S/blob/master/Output/Screenshot%20from%202020-06-28%2017-48-36.png)
- master node
![master node](https://github.com/sabreensalama/Deploy-App-using-Vagrant-Ansible-K8S/blob/master/Output/Screenshot%20from%202020-06-28%2018-06-55.png)
