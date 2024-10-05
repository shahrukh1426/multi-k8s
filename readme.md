### Apply group of config files

```
kubectl apply -f k8s
```

### Get the storage types available in the kubernetes

```
kubectl get storageclass
```

### Get list of persistent volumes

```
kubectl get pv
```

### Get list of persistent volume claims

```
kubectl get pvc
```

### Create kubernetes secrets

```
kubectl create secret generic pgpassword --from-literal PGPASSWORD=12345asdf
```

### Follow the instruction of the given link to setup kubernetes dashboard

```
https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/learn/lecture/15492160#overview
```
