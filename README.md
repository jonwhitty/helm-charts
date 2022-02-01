# helm-charts
A repository containing Helm charts for different Kubernetes deployments.

## Charts
* [authzed/spicedb](./charts/spicedb/README.md)

## Installation
```
❯ helm repo add jonwhitty https://jonwhitty.github.io/helm-charts/
❯ helm repo update
❯ helm repo upgrade --install ... <release> jonwhitty/<chart>
```