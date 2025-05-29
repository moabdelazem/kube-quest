# kube-quest 

My personal journey through the world of **Kubernetes**!  

## Structure

### `docs/`
Conceptual notes and study guides covering Kubernetes fundamentals:
- Cluster architecture
- Pods, Deployments, Services
- ConfigMaps, Secrets, Volumes
- Networking, RBAC, and more

### `manifests/`
Organized YAML files for hands-on practice:
- Simple pod specs
- Deployments and ReplicaSets
- Services (ClusterIP, NodePort, LoadBalancer)
- ConfigMaps, Secrets, Volumes, Ingress

### `scripts/`
Shell scripts for local cluster setup and automation:
- Start/stop Minikube
- Auto-deploy test apps
- Clean up namespaces and resources

## Tools Used

- [Minikube](https://minikube.sigs.k8s.io/)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/)
- [Kind](https://kind.sigs.k8s.io/) 
- Cloud providers: AKS 