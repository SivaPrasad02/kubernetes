# Deployment

How to run these files

```
kubectl create -f ****-definition.yml
```


Helper commands

```
# list all the replicaset with status
kubectl get deployments
kubectl get deploy
kubectl get deploy -o wide

# list all the replicaset with more descrioption
kubectl describe deployments {name}
kubectl describe deployments nginx

# delete the replicaset
kubectl delete deployments {name}

# edit the replicaset
kubectl edit deployments {name}

# scale the replicas
kubectl scale deployments {name} --replicas=={int:number}
or edit with above step or in yaml file if you have one

# create deployments with cmd
kubectl create deployments  --image={name} --replicas={int:number}

# Help
kubectl create deployments --help


# Rolling, rollback, Rollingupdate
```
kubectl rollout status deployements.apps/{name}
kubectl rollout history deployements.apps/{name}
# Needed to look into rollout strategy(recreate, Rollouth...)
```