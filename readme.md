#

# Load balance
kubectl port-forward svc/nginx-service 8080:80

# Comandos
kubectl get
kubectl delete
kubectl apply -f manifest.yaml
kubectl port-forward pod/nginx-replicaset-4h4nk 8080:80

# Estrutura 
:: Deployment
    :: Replicaset
        :: Pods
            :: App