# README

This README would normally document whatever steps are necessary to get the
application up and running.

```
docker build -t acant/kubernetes-rails-example:latest .
docker push acant/kubernetes-rails-example:latest

kubectl apply -f config/kube

kubectl get deployments

kubectl get pods

kubectl delete deployments kubernetes-rails-example-deployment

kubectl rollout restart deployment kubernetes-rails-example-deployment
```
