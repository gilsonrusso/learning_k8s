# Learning Docker and K8S

## What is Docker and Why Containers or Virtual Machine ?
- [Learning more Docker.com](https://www.docker.com/resources/what-container/)

## Need install to use and practice. (Windows or Linux)
- [Docker Quick Start](https://www.docker.com/get-started/)
- [Kind Quick Start](https://kind.sigs.k8s.io/docs/user/quick-start#installation)
- [Kubectl CLI](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)


## Main commands:

- #### Cluster (Create, Interactive and Get)
```
- kind create cluster --name=my-first-cluster
- kubectl cluster-info --context kink-my-first-cluster
- kind get clusters
```
- #### Kubectl (POD, SERVICE, DEPLOYMENT, PVC)
```
- kubectl apply -f pod.yaml
- kubectl get pods
- kubectl port-forward pod/name-pod 8080:80
- delete pod pod-name
- kubectl exec -it pod-name /bin/bash
```

### Notes
- The service do not be scaled just PODs
