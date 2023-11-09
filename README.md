# Argo applications GKE labs

## Cloud Diplomats ArgoCD Applications

### Applications

#### Base

- **base/cloud-diplomats**: Contains cloud-diplomats workloads deployed by the ArgoCD applications.

#### Overlay

Environments folders that inherit from base folder. It uses [kustomize](https://github.com/kubernetes-sigs/kustomize) to allow environment based customization.

### ArgoCD Applications

#### Base

- **base**: Contains ArgoCD Applications

#### Overlay

Environments folders that inherit from base folder. It uses [kustomize](https://github.com/kubernetes-sigs/kustomize) to allow environment based customization.
