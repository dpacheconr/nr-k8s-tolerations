# nr-k8s-tolerations

```
NAMESPACE=newrelic
kubectl create namespace $NAMESPACE ; helm upgrade --install newrelic-bundle ./nri-bundle  \
 --namespace=$NAMESPACE \
 -f ./nri-bundle/values.yaml
```
