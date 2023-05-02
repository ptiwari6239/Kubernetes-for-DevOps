
## Static Pod

- A static pod is a Kubernetes pod that is not managed by the Kubernetes API server or the Kubernetes controller manager.
- Instead, static pods are managed directly by the kubelet, which is the agent that runs on each node in a Kubernetes cluster.
- When the kubelet starts up, it reads a set of YAML or JSON files from a directory on the node's file system. These files describe the static pods that should be started on that node.
- The kubelet then creates and manages the static pods as if they were normal Kubernetes pods.
- If a static pod is deleted, the kubelet will automatically recreate it based on the YAML or JSON file on the node's file system.
- Static pods are useful for running system daemons or other low-level processes that need to be started automatically when a node starts up.
- Since static pods are not managed by the Kubernetes API server, they cannot be managed using Kubernetes commands like kubectl. Instead, they must be managed directly on the node's file system.
- 
- 
- 
- 