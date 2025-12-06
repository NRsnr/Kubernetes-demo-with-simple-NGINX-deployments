# Kubernetes-demo-with-simple-NGINX-deployments
This repository includes manifest files for a simple bird-themed Kubernetes project.   The pods and deployments  were designed to run simple nginx containers in conjunction with config maps with customized HTML.  

There are four deployments: cardinals, ducks, blue jays, and penguins.  Each deployment is designed for three pod replicas.  The species label is used for the deployments.

The loadbalancer-service.yaml file is a service manifest of type LoadBalancer.  This service exposes TCP port 80 and uses the family label "birds" to recognize the pods that will be load balanced.  
