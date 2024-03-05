# Hello 123 this is my test  messagek helloojj 

```
# argo cd
microk8s start
microk8s stop
microk8s
microk8s kubectl get pod -n argocd
microk8s kubectl -n argocd get secret argocd-initial-admin-secret \
          -o jsonpath="{.data.password}" | base64 -d; echo
microk8s kubectl get nodes -o wide

minikube start
minikube stop
minikube delete
minikube start --memory 4096 --cpus 2 --disk-size 20g

minikube service {service-name}
minikube dashboard
minikube tunnel

kubectl apply -f {file-name}
```
