## pod.yaml file commands
 kubectl apply -f pod.yaml
 kubectl delete -f pod.yaml
 kubectl exec -it -n dev my-pod -c nginx -- bash

## servcie.yaml file
 kubectl apply -f service.yaml
 kubectl get -svc -n dev
 kubectl get svc -n dev

 
