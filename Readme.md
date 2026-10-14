						Kubernetes Project-1
1. Create KIND Cluster:
	Kubernetes needs a cluster to run applications.
•	Control Plane manages the cluster.
•	Worker Node runs your application.
Without a cluster, there is nowhere to deploy the Notes App.

2. Create Namespace: Namespaces organize resources.Instead of mixing everything in the default namespace

3. Create Deployment: So that it manages pods automatically
	1.set repicas to 2
	2. pulled the docker image
	3.created the pod
	4.assiged the labels to identify resources

4.Created Service: To provide a stable ip
5.Exposed the service using nord port

WorkFlow:
User sends the request and the Kubernetes cluster receives it. Every node has kube-proxy, which creates network rules on each node. These rules know which Pods belong to a Service, such as Pod-A running on port 3000 and Pod-B running on port 3001. Using these rules, the reques is routed through the Service to the correct Pod.


	


