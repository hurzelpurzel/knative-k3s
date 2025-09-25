
# NATS Server
```
kubectl create ns nats

helm repo add nats https://nats-io.github.io/k8s/helm/charts/
helm upgrade --install nats nats/nats -n nats

```
# Knative nats extention

```
kubectl apply -f https://github.com/knative-extensions/eventing-natss/releases/download/knative-v1.18.3/eventing-jsm.yaml

kubectl apply -f cm.yaml -n knative-eventing
```


#  