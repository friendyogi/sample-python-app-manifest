# Sample Python App

The repository contains Kubernetes manifests that defines the deployment of the
[sample application](https://github.com/friendyogi/sample-python-app).

To deploy the application manually run the following command:

```
kubectl create namespace gitops-yogesh
kubectl apply -f . -n gitops-yogesh
```

To test the application `curl http://localhost:80/` or `curl http://gitops-demo-service`

