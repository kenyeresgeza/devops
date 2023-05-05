# Kubernetes YAML examples

YAML file examples to use Kubernetes.

## Description

Some examples how to create Pods, Deployments or Services in Kubernetes.

## Getting Started

### Dependencies

* Kubernetes cluster or equivalent environment (e.g. minikube)
* kubectl

### Running examples

#### Create Pod

* Create a simple Pod
```
kubectl create -f create_pod.yaml
```

* Create a Pod with healthcheck probes
```
kubectl create -f create_pod_with_exec_and_http_probes.yaml
```
```
kubectl create -f create_pod_with_tcp_probe.yaml
```

#### Create Deployment

* Create simple Deployment and ReplicaSet
```
kubectl create -f create_deployment.yaml
```

#### Create ReplicaSet

* How ReplicaSet and Pods
```
kubectl create -f create_replicaset.yaml
```

#### Create Service

* Create simple Service
```
kubectl create -f create_service.yaml
```
* Create Service and Deployment
```
kubectl create -f create_service_and_deployment.yaml
```

#### Create Ingress

* Create Ingress object to access Service
```
kubectl create -f create_ingress.yaml
```

## Author

Kenyeres Géza
https://hu.linkedin.com/in/g%C3%A9za-kenyeres-17341631

