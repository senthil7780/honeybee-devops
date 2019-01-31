#Please run the below docker-compose command to get the images built

docker-compose build

#if you are running minikube please start the k8s

minikube start


#Please run the following command to start the pods

kubectl create -f elasticsearch-service.yaml,fluentd-service.yaml,kibana-service.yaml,nginx-service.yaml,elasticsearch-deployment.yaml,fluentd-deployment.yaml,fluentd-claim0-persistentvolumeclaim.yaml,kibana-deployment.yaml,nginx-deployment.yaml,nginx-claim0-persistentvolumeclaim.yaml

#To check the pod status

kubectl get pods