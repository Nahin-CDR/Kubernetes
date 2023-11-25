# kubernetes cluster


# Cluster:

A Kubernetes cluster is a set of physical or virtual machines (nodes) that run containerized applications.
Nodes can be categorized into two types: Master Nodes and Worker Nodes.

# Master Node:

The master node is responsible for managing the overall state of the cluster.
Components on the master node include:

# Kube-apiserver: 
Exposes the Kubernetes API, which is used to interact with the cluster.

# etcd: 
A distributed key-value store that stores the configuration data of the cluster.

# Kube-controller-manager: 
Manages controllers that regulate the state of the system.

# Kube-scheduler: 
Assigns work (containers) to nodes based on resource requirements and constraints.

# Worker Node:

Worker nodes are where the containers run. They host the applications and services.
Components on a worker node include:

# Kubelet: 
Communicates with the master node and ensures that containers are running in a Pod.
# Kube-proxy: 
Maintains network rules on nodes. It enables communication between Pods across the cluster.

# Container runtime: 
The software responsible for running containers (e.g., Docker, containerd).

# Pod:
The smallest deployable unit in Kubernetes.
A Pod represents a single instance of a running process in the cluster and can contain one or more containers that share the same network namespace.

# Controller:

Controllers are responsible for ensuring that the desired state of the system matches the actual state.
Examples of controllers include Deployments, StatefulSets, and DaemonSets.

# Service:
A Service provides a stable endpoint for accessing a set of Pods, allowing for load balancing and service discovery.
Namespace:

Namespaces are a way to divide cluster resources between multiple users or projects.
# Label:

Labels are key-value pairs attached to objects (e.g., Pods, Services) that are used to organize and select subsets of resources.
# Volume:

Volumes provide persistent storage to containers.
ConfigMap and Secret:

ConfigMaps and Secrets are used to decouple configuration artifacts from containerized applications.

# Visualize Kubernetes Cluster with e pictures flow

![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/64650f59-1d13-4e25-885c-27e8c0e531a9)

![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/2acc103a-374e-4aa4-9f6f-fbb38b6989c8)


![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/9bda9da6-bce2-4115-a4cf-c724d0eb519c)

![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/5bd3c916-4a17-40fd-afb2-ea3c14cb33a0)

![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/416c6fcc-9a1c-4fd7-899a-25bc884c7f27)

![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/7a08549b-6092-417f-849e-ec15497c4408)

![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/87141f18-6c31-41b8-97b0-536900ee0da9)


![image](https://github.com/Nahin-CDR/Kubernetes/assets/45636041/97785cca-30cb-487d-8b65-af47f56debf1)
