# kubernetes cheat sheet

## Creating objects
```
kubectl apply -f ./my-manifest.yaml  
```

## Pods
```
kubectl get pods
kubectl get pods --all-namespaces             # List all pods in all namespaces
```

## Replica Set 

```
kubectl get rs
```

## Deployment

```
kubectl get deployments
```

## Service 

```
kubectl get svc
```

## Minikube

Check url service in minikube 

```
minikube service db-adminer-service --url
```




