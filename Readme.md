Useful commands:
* get pods:
```bash
  kubectl get pods
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
