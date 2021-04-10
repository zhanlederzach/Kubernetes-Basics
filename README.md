# Kubernetes-Basics
## Run following to apply kubernetes manifest:
kubectl apply -f manifest.yml

## To run see deployment locally apply port forwarding on your machine:
- for backend this port is used: 
kubectl port-forward service/sa-homework-api 8000:8000

- for frontend this port is used: 
kubectl port-forward service/sa-homework-web 3000:3000 


# Project description:
- ToDo app (CRUD, first task included)
- backend is on spring boot (kotlin)
- frontend is on react
