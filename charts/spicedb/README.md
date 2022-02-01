# spicedb
A Helm chart to manage a Kubernetes based deployment of [authzed/spicedb](https://github.com/authzed/spicedb).

## Installation
```
❯ helm upgrade --install -f values.yaml --set grpc.presharedKey="mysecret" spicedb .
```
installs (by default) a 3 node spicedb cluster with defaults and dispatching enabled.