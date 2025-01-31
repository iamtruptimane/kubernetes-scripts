## pod.yaml file commands
 1. kubectl apply -f pod.yaml
 2. kubectl get pods -o wide
 3. kubectl delete -f pod.yaml
 4. kubectl exec -it -n dev my-pod -c nginx -- bash

## servcie.yaml file
 1. kubectl apply -f service.yaml
 2. kubectl get -svc -n dev
 3. kubectl get svc -n dev

 
