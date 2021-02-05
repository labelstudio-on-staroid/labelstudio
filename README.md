# Label Studio on Staroid

This project brings Label Studio (https://github.com/heartexlabs/label-studio) to Staroid (https://staroid.com).

Please take a look `.staroid` directory to see how it is integrated.


## Development

Run locally with [skaffold](https://skaffold.dev/) command on [minikube](https://minikube.sigs.k8s.io)

```
skaffold dev -f .staroid/skaffold.yaml --port-forward -p minikube
```
