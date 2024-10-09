Kubernetes Ingress : 


Why Ingress :

1 .Kubernetes serices did not have enterprise level load balancing capabilities which are security and good load balancing capabilities without these no body moves to kubernetes.

** Enterprise & Load Balancer Capabilities :

-> Sticky Sessions 

-> TLS load balancing

-> path based Load Balancing

-> Host Based Load Balancing

2 **. If we are creating a sevice of type load balancer mode ,then for each load balancer service type IP address cloud provider will charges us. 

** minikube addons enable ingress : which will install ingress controller on minikube cluster

** we need ingress controller to execute ingress resource.

** we have to update IP address and domain name in /etc/hosts file to reach requests into the domain, if we are in minikube cluster.
