# Kubernetes practice

Course Ref : https://www.udemy.com/learn-kubernetes/

# Pod

Run the pod with kubectl cmd
```
kubectl run {name-of-pod} --image={name of image from docker registries}
kubectl run nginx --image nginx
```

Helper commands

```
kubectl get pods
kubectl get pods -o wide
kubectl describe pod {name}
kubectl describe pod nginx
```

