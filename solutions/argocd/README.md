### Pre-requisites
```
* A k8s cluster
* kubectl
```

### Setup
```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```

