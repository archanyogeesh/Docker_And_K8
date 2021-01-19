# Docker_And_K8

Custom Cmd:

For client app : docker build -t archansy/dockerandk8clientapp:0.1 .

docker push archansy/dockerandk8clientapp:0.1

To get deployments:
kubectl get deployments

To get services:
kubectl get services 

Run Yml files
kubectl apply -f k8s

client docker 
Build:docker build -t archansy/dockerandk8clientapp:0.1
Push :archansy/dockerandk8clientapp:0.1

Server docker 
Build:docker build -t archansy/dockerandk8serverapp:0.1
Push :archansy/dockerandk8serverapp:0.1