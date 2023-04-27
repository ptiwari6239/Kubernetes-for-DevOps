## Init container

Init containers are specialized containers that are executed before the main containers in a Kubernetes Pod. Their purpose is to perform initialization tasks, such as downloading application dependencies or setting up configuration files, before the main container is started.
Init containers are defined in the Pod specification alongside the main containers, and are executed one at a time in the order they are defined. If an init container fails, Kubernetes will retry it a number of times, and will not start the main container until all init containers have successfully completed.

**Some use cases for init containers include:**
-   Downloading data or dependencies required by the main container
- Waiting for a service or resource to become available before starting the main container
- Performing security checks or setting up credentials before starting the main container

Init containers can be a powerful tool for ensuring that your Kubernetes applications start up smoothly and reliably, and can help to automate many common initialization tasks.