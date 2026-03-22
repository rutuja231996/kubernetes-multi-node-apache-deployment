# kubernetes-multi-node-apache-deployment
k8s kubernetes multi node apache cluster

[Master]
   |
[Worker1] ---- [Worker2]
      \        /
       Apache Pod


       
# Multi-Node Kubernetes Apache Deployment

This project demonstrates deploying an Apache web server on a multi-node Kubernetes cluster.

## 🚀 Setup

* 1 Master Node
* 2 Worker Nodes
* Kubernetes cluster initialized using kubeadm

## 📦 Deployment

* Deployed an Apache pod (`apache-pod`) on the cluster
* Verified pod is running successfully

## 🌐 Key Achievement

* Accessed the Apache web server from multiple worker nodes
* Demonstrated Kubernetes cluster networking across nodes

## 🔧 Commands Used

```bash
kubectl get nodes
kubectl get pods -o wide
kubectl exec -it apache-pod -- /bin/bash
```

## 📌 Learning Outcomes

* Understanding Kubernetes architecture (Master + Worker nodes)
* Pod deployment and lifecycle
* Cluster networking
* Cross-node communication

## 🧠 Conclusion

This project validates that Kubernetes enables seamless communication between nodes in a cluster, allowing workloads to be accessed regardless of where they are running.

