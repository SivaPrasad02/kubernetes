How to run these files

```
kubectl create -f pod-definition.yml
```


Helper commands

```
# list all the replicaset with status
kubectl get replicaset
kubectl get rs
kubectl get replicaset -o wide

# list all the replicaset with more descrioption
kubectl describe replicaset {name}
kubectl describe replicaset nginx

# delete the replicaset
kubectl delete replicaset {name}

# edit the replicaset
kubectl edit rs {name}

# scale the replicas
kubectl scale rs {name} --replicas=={int:number}
or edit with above step or in yaml file if you have one
```