ref:
https://kubernetes.io/docs/tutorials/stateful-application/basic-stateful-set/

https://kubernetes.io/docs/tutorials/stateful-application/cassandra/

```sh
kubectl exec -ti nginx-stsf-0 -- curl localhost
kubectl exec -ti nginx-stsf-0 -- curl nginx-stsf-1.stsf-service
kubectl exec -ti nginx-stsf-0 -- curl nginx-stsf-1.stsf-service.default.svc.cluster.local
```
*Pods in a StatefulSet have a unique ordinal index and a stable network identity.*

# Worth Checking
https://github.com/zalando/postgres-operator

https://cloud.google.com/blog/products/databases/to-run-or-not-to-run-a-database-on-kubernetes-what-to-consider
