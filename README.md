
# Setting up a local Apache Kafka instance for testing

This is by far the easiest I have found and saves you ton of time. 

## The Docker way

Once you have cloned the repo just spin it up!

cd ./docker-compose

```
cd ./docker-compose

docker-compose up -d
```

## The Kubernetes Way

### pre-requisites

- kubernetes in local environmet (kind, docker, minikube)

Once you have cloned the repo just spin it up!

```
cd ./k8s

kubectl apply -f zookeeper.yaml

kubectl apply -f kafka.yaml

```