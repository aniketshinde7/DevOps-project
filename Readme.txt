
minikube start (to start minikube)

minikube stop  (to stop minikube)

kubectl create deployment [NAMESPACE] --image=[image name]     (Create a kubernetes deployment)

kubectl get pods

kubectl expose deployment  [NAMESPACE] --type=LoadBalancer --port=[port]     (Create a kubernetes service type LoadBalancer)

minikube ip       (to get ip)

minikube dashboard    (its open the dashboard in browser)

minikube service [NAMESPACE] --url  (to get url)
