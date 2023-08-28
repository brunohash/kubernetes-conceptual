# introdução
https://medium.com/@brunohashimoto/kubernetes-para-iniciantes-434b845f6d3f

# Load balance
kubectl port-forward svc/nginx-service 8080:80

# Comandos
kubectl get <br>
kubectl delete <br>
kubectl apply -f manifest.yaml <br>
kubectl port-forward pod/nginx-replicaset-4h4nk 8080:80

# Estrutura 
:: Deployment <br>
    :: Replicaset <br>
        :: Pods <br>
            :: App <br>
