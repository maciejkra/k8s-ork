```sh
kubectl create ns workshops
kubectl apply -f deployment.yaml
kubectl get all -n workshops
kubectl -n workshops describe deployment replicate-my-app
```