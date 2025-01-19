# Node

- Node adalah tempat menjalankan pod
- Bisa memiliki banyak node
- Node bisa berupa VM atau bare metal
- Node dapat dikelompokan dengan node-pool (cloud)
- Setiap node akan memiliki kubelet, kube-proxy, dan container-runtime

`kubectl get node`

`kubectl get node -o wide`

`kubectl describe node <node_name>`