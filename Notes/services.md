## Services in k8s

Kubernetes Services are an abstraction layer that provide a way to expose and access groups of pods (containers) running within a Kubernetes cluster, to the network.</br>

---
### ClusterIP
This is the default type of service, which provides a stable IP address within the cluster to access a set of pods. This service is accessible only within the cluster, making it suitable for internal communication between services
</br>

### NodePort
This service exposes a pod to the outside world by mapping a static port on each node in the cluster to the service. This enables external access to the pods in the set via the node's IP address and the assigned port.</br>

### LoadBalancer
his service creates an external load balancer that routes traffic to a set of pods in the cluster. This is typically used in cloud environments to expose services to the internet.

### ExternalName
 This service maps a service to an external DNS name, which can be used to access an external service from within the cluster.


 [watch this video to understand](https://www.youtube.com/watch?v=T4Z7visMM4E)
 
---
---