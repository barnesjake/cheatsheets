kubectx ----> context, change between clusters
kubens  ----> namespace
kubectl ----> control, run commands against Kubernetes clusters
kubectl get deployments ----> show what is running in the namespace you are on
kubectl get pods -> show running pods
kubectl get ingress
kubectl get ingresses
kubectl describe ingress
kubectl get all
kubectl get events
kubectl get secrets -o yaml
kubectl apply -f someconfig.yaml
kubectl get configMaps
kubectl scale deployment --replicas=0 <service_name>
kubectl scale deployment --replicas=1 <service_name> 

kubectl get ns
Or 
kubectl get namespaces
kubectl get ns | grep plutus
Or just use: kubens
Show current namespace: kubens -c