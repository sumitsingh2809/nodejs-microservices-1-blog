`Create POD`
kubectl apply -f posts-depl.yaml

`Get DEPLOYMENTS list`
kubectl get deployments

`Delete a DEPLOYMENT`
kubectl delete deployment <DEPL NAME>

`Print details about a specific deployment`
kubectl describe deployment <DEPL NAME>

`Get POD list`
kubectl get pods

`Delete a POD`
kubectl delete pod <POD_ID>

`Update deployment`
kubectl rollout restart deployment <DEPL NAME>

`Print POD logs`
kubectl logs <POD_ID>

`List Services`
kubectl get services
