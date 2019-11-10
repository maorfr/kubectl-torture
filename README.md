# kubectl-torture

A Kubernetes plugin to get all information from a Pod before deleting it.

[Install](https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/#installing-kubectl-plugins) the plugin and try it:

```
kubectl torture <pod>
```

A directory with the pod's name will be created with:
* Yaml pod manifest
* JSON pod manifest
* All container logs
