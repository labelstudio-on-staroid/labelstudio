# Label Studio on Staroid

This project brings Label Studio (https://github.com/heartexlabs/label-studio) to Staroid (https://staroid.com).

Please take a look `.staroid` directory to see how it is integrated.


## Launch

[![Run](https://staroid.com/api/run/button.svg)](https://staroid.com/api/run)

To use ML models, launch a model first from below and then select the model on launch window

 * [text sentiment](https://staroid.com/g/labelstudio-on-staroid/text-sentiment/instances)

## Development

Run locally with [skaffold](https://skaffold.dev/) command on [minikube](https://minikube.sigs.k8s.io)

```
skaffold dev -f .staroid/skaffold.yaml --port-forward -p minikube
```
