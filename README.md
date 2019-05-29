# Setup Kubernetes HA Cluster

This repository provides Ansible playbooks to setup Kubernetes HA cluster. The playbooks are mainly inspired by kubeadm documentation.


**Notice**: Debian/Ubuntu Only


## Variables

```yaml
---
docker_version: 18.06.3
kubeadm_version: 1.14.0
kubelet_version: 1.14.0
kubectl_version: 1.14.0
kubernetes_version: 1.14.0

pod_network_cidr: 10.244.0.0/16
#apiserver_endpoint: internal-elb.k8s.local:6443
apiserver_endpoint: 127.0.0.1:6443
```


## LICENSE

MIT License
