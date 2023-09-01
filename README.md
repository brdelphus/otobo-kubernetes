# otobo-kubernetes
OTOBO repository for Kubernetes

Please take a look at persistent files and check disk sizes
to match your needs.

Common commands:

Apply deployments (container):
kubectl -n UsedNamespace apply -f Config/yaml/. 

Delete deployments (containers)
kubectl -n UsedNamespace delete -f Config/yaml/. 

Show pods, pvc, pv:
kubectl -n UsedNamespace get pods
kubectl -n UsedNamespace get pvc
kubectl -n UsedNamespace get pv

Delete pods and volumens
kubectl -n UsedNamespace delete pod podname
kubectl -n UsedNamespace delete pvc pvcname
kubectl -n UsedNamespace delete pv pvname
