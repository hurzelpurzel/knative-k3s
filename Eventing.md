# Knative Eventing

## p2p Verbindung

In this case a Source & a Sink is enough to connect to services

## fan-out publish/subscribe

If you watn to spreade one event to several subscriber a channel is needed

# inMemory Channel
kubectl apply -f https://github.com/knative/eventing/releases/download/knative-v1.19.5/in-memory-channel.yaml