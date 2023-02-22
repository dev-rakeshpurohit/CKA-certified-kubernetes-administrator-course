# Commands

## pods
- kubectl get pods (List of Pods)
- kubectl run --help
- kubectl run nginx --image=nginx (new pod with the nginx image.)
- kubectl describe pod newpods-8gb2l (More detail about pod)
- kubectl get pods -o wide (pods with more details)
- kubectl delete pod webapp
- kubectl run redis --image=redis123 --dry-run=client -o yaml > redis.yaml (create YAML file from image name)
- kubectl create -f redis.yaml
- kubectl apply -f redis.yaml