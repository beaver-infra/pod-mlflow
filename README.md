# Pod MLFlow

A pod repository for mlflow to manage models lifecycle

## Prerequisite

Required

* [Python 3.8 or above](https://www.python.org/downloads/).
* [K8s single instance on dev](https://minikube.sigs.k8s.io/docs/start/)

## Setup

### Usew Helm - https://artifacthub.io/packages/helm/community-charts/mlflow

```
minikube start

helm repo add community-charts https://community-charts.github.io/helm-charts
helm repo update

helm install mlflow community-charts/mlflow

Follow the terminal instructions
```

