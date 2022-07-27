# voting-app
> kubectl create -f voting-app-deploy.yaml \
  && kubectl create -f voting-app-service.yaml

# redis
> kubectl create -f redis-deploy.yaml \
  && kubectl create -f redis-service.yaml

# postgres
> kubectl create -f postgres-deploy.yaml \
  && kubectl create -f postgres-service.yaml

# worker-app
> kubectl create -f worker-app-deploy.yaml

# result-app
> kubectl create -f result-app-deploy.yaml \
  && kubectl create -f result-app-service.yaml
