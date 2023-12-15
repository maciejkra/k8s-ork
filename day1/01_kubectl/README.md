Do this first!

```sh
kubectl config current-context
kubectl config get-contexts
```

info:
```sh
kubectl cluster-info
```

Really verbose

```sh
kubectl get pods -v=9
```

## Useful stull

Instal konfig plugin and import configuration
```sh
kubectl krew install konfig
kubectl konfig import -s <file>
```