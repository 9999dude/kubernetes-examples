# Kuberntes Sidecar init container Demo

## Prerequisites
- Kind installation and Kubernetes cluster creation: [kind](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)
```shell
$ brew install kind
$ kind create cluster --config kind-sidecar-k8s1.28.yaml
```

```shell
$ kubectl apply -f sidecars/job-sidecar.yaml
$ kubectl apply -f sidecars/deployment-sidecar.yaml
```