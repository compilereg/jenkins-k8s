YAML file that creates
	1-jenkins pod that listens on port 80 for administration, and 50000 for building clients
	2-ClusterIP Service to expose the pod ports to the K8S cluster
	3-Ingress controller rule to publish the administration portal. Just change your hostname In the ingress controller object, change the host value in the spec.
