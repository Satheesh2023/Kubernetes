# Kubernetes
Kubernetes automates operational tasks of container management and includes built-in commands for deploying applications, rolling out changes to your applications, scaling your applications up and down to fit changing needs, monitoring your applications, and more—making it easier to manage applications.

**OVERVIEW** :

For examle Kubernetes cluster has 1 master node and 2 worker nodes, managing and running containerized applications.

**Master Node Components** :

API Server: Front-end for the Kubernetes control plane.
Scheduler: Assigns Pods to nodes based on resource needs.
etcd: Stores the entire cluster's state.
Controllers: Ensure desired state and scaling.
CCM (Cloud Controller Manager): Integrates with the cloud provider for managing resources.

**Worker Node Components** :

Kubelet: Manages Pod lifecycles.
Kube-proxy: Manages network traffic.
Container Runtime: Runs containers (e.g., Docker).
How It Works:
API Server handles requests and coordinates communication.
Scheduler assigns Pods to worker nodes.
Kubelet and Kube-proxy ensure Pods run and network traffic flows.
etcd keeps track of the cluster state.
