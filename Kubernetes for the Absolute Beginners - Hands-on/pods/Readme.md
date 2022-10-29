How to run these files

```
kubectl create -f pod-definition.yml
```


Helper commands

```
# list all the pods with status
kubectl get pods
kubectl get pods -o wide

# description of pod
kubectl describe pod {name}
kubectl describe pod nginx

# delete the pod
kubectl delete pod {name}

# Edit the pod
kubectl edit pod {name}
```