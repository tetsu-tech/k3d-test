
install k3d

````
curl -s https://raw.githubusercontent.com/rancher/k3d/main/install.sh | bash¥
```

crete resources

```
kubectl create deployment my-deployment --image=nginx:latest --replicas=3

kubectl create service clusterip my-deployment --tcp=80:80

kubectl get all

kubectl apply -f ingress.yaml
```

links
- https://github.com/tiborpetroczy/k3d-cluster
- https://tiborpetroczy.medium.com/lightweight-k3d-kubernetes-cluster-e49b48b979a2
