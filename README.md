# voting-app-kubernetes-v1

## Create PODs (voting-app) :

1. kubectl create -f voting-app-pod.yml

2. kubectl get pods

## Create Service:

3. kubectl create -f voting-app-service.yml

## List of Service:

4. kubectl get services

5. Login GCP and leftside check "Discovery & Load Balancing"

   LoadBalancer only comes on public cloud. Now will get external ip address.

6. kubectl get services

   showing external ip address
   
## Redis

1. kubectl create -f redis-pod.yml

2. kubectl get pods

3. kubectl create -f redis-service.yml

4. kubectl get services

   See the IP(ie) internal cluster-ip.

## Postgres

1. kubectl create -f postgres-pod.yml

2. kubectl get pods

3. kubectl create -f postgres-service.yml

4. kubectl get services

   See the IP(ie) internal cluster-ip.

## Worker-app

1. kubectl create -f worker-app-pod.yml

2. kubectl get pods

## Result-app

1. kubectl create -f result-app-pod.yml

2. kubectl create -f result-app-service.yml
   
   [ creating load balancer ]
   
## Url:

[ root_ip ]  see the result app now.
   
   
 




