# helm-charts
Various Helm charts for different Kubernetes deployments.

## Charts
* [authzed/spicedb](./charts/spicedb/README.md)

## Roadmap
1. Helm registry through GitHub pages so that clients can do the following (for example):
```
❯ helm repo update
❯ helm repo add jonwhitty https://jonwhitty.github.io/helm-charts
❯ helm upgrade --install -f values.yaml --set grpc.preshaerdKey="mysecret" spicedb .
```