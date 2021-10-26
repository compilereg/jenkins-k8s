YAML file that creates
	_ jenkins pod that listens on port 80 for administration, and 50000 for building clients
	_ ClusterIP Service to expose the pod ports to the K8S cluster
	_ Ingress controller rule to publish the administration portal. Just change your hostname In the ingress controller object, change the host value in the spec.
