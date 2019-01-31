#Please run the below docker-compose command to get the images built

docker-compose build

#if you are running minikube please start the k8s

minikube start


#Please run the following command to start the pods

kubectl create -f ./k8s/elasticsearch-service.yaml,./k8s/fluentd-service.yaml,./k8s/kibana-service.yaml,./k8s/nginx-service.yaml,./k8s/elasticsearch-deployment.yaml,./k8s/fluentd-deployment.yaml,./k8s/fluentd-claim0-persistentvolumeclaim.yaml,./k8s/kibana-deployment.yaml,./k8s/nginx-deployment.yaml,./k8s/nginx-claim0-persistentvolumeclaim.yaml

#To check the pod status

kubectl get pods