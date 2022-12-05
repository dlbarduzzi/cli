# kubectl

```sh
# Get nodes based on label key/value pair (-l or --selector)
kubectl --context="<context>" get nodes -l dedicated=prometheus-test

# Scale deployment
kubectl --context="<context>" --namespace="<namespace>" scale deployment/<deployment-name> --replicas=0
```
