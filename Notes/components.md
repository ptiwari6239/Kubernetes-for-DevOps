# components of kubernetes

### Pods
- smallest unit of k8s
- abstraction over container
- ususally 1 application per pod
- each pod gets its own ip address
### Service
- permanent ip address
- lifecycle of pod and service not connected
### configMap
- external configuration of application 
### Secrets
- used to store secret data
- base64 encoded
### Deployment
-  blueprint for pod
- we create deployments
- abstraction of pods