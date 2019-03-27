Odoo on Kubernetes
---

#####
Running Odoo on MicroK8s:

Install MicroK8s https://microk8s.io/

Enable persistent storage: 
```
microk8s.enable storage
```
Apply YAML config: 
```
microk8s.kubectl apply -f microk8s/odoo.yaml
```
