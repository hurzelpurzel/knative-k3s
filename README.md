# Knative on k3s


## k3s installation
- linuxmint
- k3s service change: k3s server --write-kubeconfig-mode=644 --disable=traefik 
- Skip datei für traefik anlegen /var/lib/rancher/k3s/server/manifests# touch traefik.yaml.skip

## knative installation
- serving:
https://knative.dev/docs/install/yaml-install/serving/install-serving-with-yaml/#prerequisites
- kourier ingress: https://knative.dev/docs/install/yaml-install/serving/install-serving-with-yaml/#install-a-networking-layer

- DNS: kubectl apply -f https://github.com/knative/serving/releases/download/knative-v1.19.6/serving-default-domain.yaml



## Task 1
https://knative.dev/docs/getting-started/first-service/

<pre>
curl  http://hello.default.192.168.124.133.sslip.io
</pre>
