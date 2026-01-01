I created two yaml files service and pod to run them you need to run the command 
kubectl apply -f pod.yaml
and kubectl apply -f service.yaml
To open the software online you need to write the command: minikube service streamlit-service
These yaml files build a pod and a fixed IP for the software for easy connection