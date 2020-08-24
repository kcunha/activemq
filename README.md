#instructions

#1
minikube -p karen.dev start

#2
kubectl apply -f activemq-deployment.yaml

#3
kubectl apply –f k8s-activemq-service.yml
