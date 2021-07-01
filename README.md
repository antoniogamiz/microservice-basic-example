# microservice-basic-example
Basic example for the first touch of a micro service project.


~~~
kubectl apply -f posts.yaml
kubectl get pods
kubectl exec -it [pod_name] [cmd]
kubectl logs [pod_name]
kubectl delete pod [pod_name]
kubectl apply -f [config file name]
kubectl desscribe pod [pod_name]
~~~

Recommended alias:
~~~
alias k = kubectl
alias dps="docker ps"
~~~

You will need this command to be run in every terminal you open: ([+info](https://minikube.sigs.k8s.io/docs/commands/docker-env/))

~~~
eval $(minikube docker-env)
~~~

**Important:** you need to build the container _after_ running that command _and_ from the same terminal.