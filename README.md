# kubernetes cheat sheet

## Creating objects
```
kubectl apply -f ./my-manifest.yaml  
```

## Pods
```
kubectl get pods
kubectl get pods --all-namespaces             # List all pods in all namespaces
kubectl get pod my-pod -o yaml                # Get a pod's YAML
kubectl describe pods my-pod                  # Describe pod
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



```
minikube start                                   # Start minikube cluster 
minikube service db-adminer-service --url        # Check url service in minikube 
```




