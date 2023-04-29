## DaemonSet 

- n Kubernetes, a DaemonSet is a controller object that ensures that a specific Pod is running on all or a subset of nodes in a cluster. It is used for running a single copy of a Pod on each node in the cluster, and for ensuring that a specific Pod is always running on every node in the cluster.
- When a DaemonSet is created, Kubernetes creates a Pod on every node that matches the selector specified in the DaemonSet manifest. The DaemonSet controller then monitors the nodes and ensures that the Pod is always running on the appropriate nodes. If a new node is added to the cluster, the DaemonSet controller will automatically create a new Pod on that node.
- DaemonSets are commonly used for running monitoring agents, logging agents, or other system daemons that need to run on every node in a cluster.


[watch this](https://www.youtube.com/watch?v=6I4WgCvlXy8)
---
--- 