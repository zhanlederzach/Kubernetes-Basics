# Kubernetes-Basics
Manifest-ingress.yaml includes second task with ingress.
Manifest.yaml includes 1 and 2 tasks without ingress, in order to run it port forwarding are needed to run.

## Run following to apply kubernetes manifest:
kubectl apply -f manifest.yml

## To run see deployment locally apply port forwarding on your machine:
- kubectl port-forward service/sa-homework-api 8000:8000 (for backend this port is used)

- kubectl port-forward service/sa-homework-web 3000:3000 (for frontend this port is used)

# Project description:
- ToDo app (CRUD, first task included)
- backend is on spring boot (kotlin)
- frontend is on react
