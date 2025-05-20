# jarvis-apps

This repository contains the GitOps configuration to deploy my applications using Argo CD.

## Initial Step - Manual Application

Before automatic deployment takes over, you need to **manually apply** the following Argo CD resource once:

```bash
kubectl apply -f appsets/appset-app.yaml
