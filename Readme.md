Useful commands:
* get pods, namespaces, pvcs, services:
```bash
  kubectl get pods -n <namespace>
  kubectl get pvc -n <namespace>
  kubectl get services -n <namespace>
  ```
* apply changes:
```bash
  kubectl apply -f <file>
  ```
* get logs of a pod:
```bash
  kubectl logs <pod-name>
  ```
* get logs of all container in a pod:
```bash
  kubectl logs <pod-name> --all-containers=true
  ```
