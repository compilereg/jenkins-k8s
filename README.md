# Jenkins-K8S:
YAML file that create
 *  A namespace called jenkins
 * jenkins pod that listens on port 80 for administration, and 50000 for building clients in jenkins namespace.
 * ClusterIP Service to expose the pod ports to the K8S cluster in jenkins namespace.
 * Ingress controller rule to publish the administration portal. Just change your hostname In the ingress controller object, change the host value in the specin jenkins namespace.

# Requirments:
  * Any kubernetes cluster
  
# Usage:
  * git clone https://github.com/compilereg/jenkins-k8s.git
  * cd jenkins-k8s
  * kubectl create -f jenkins.yml
