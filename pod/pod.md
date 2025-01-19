# Pod

- Pod adalah unit terkecil di kubernetes
- Satu pod bisa lebih dari satu container
- Setiap pod memiliki satu IP Address
- Pod sifatnya ephemeral

`kubectl apply -f <file_name>`

`kubectl describe pod <pod-name>`

`kubectl get pod`

`kubectl port-forward <local_port>:<host_port>`

`kubectl exec -it <pod_name> -c <container_name> -- /bin/sh`