# Label Studio on Staroid

This project brings Label Studio (https://github.com/heartexlabs/label-studio) to Staroid (https://staroid.com).

Go to [Instances](https://staroid.com/g/labelstudio-on-staroid/labelstudio/instances) to start a new instance.


## ML backend

[![Run](https://staroid.com/api/run/button.svg)](https://staroid.com/api/run)

To use ML backend, launch a ML backend first from the below and then select the instance on LabelStudio launch dialog

 * [text sentiment](https://staroid.com/g/labelstudio-on-staroid/text-sentiment/instances)

## Development

Run locally with [skaffold](https://skaffold.dev/) command on [minikube](https://minikube.sigs.k8s.io)

```
skaffold dev -f .staroid/skaffold.yaml --port-forward -p minikube
```
