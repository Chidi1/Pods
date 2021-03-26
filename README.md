# Pods

Build the app or run the following command to create the deployment (Note: Download and install docker engine): 
 
kubectl create -f deployment.yaml 
The deployment creates 1 replicated Pods, indicated by the replicas field. 
The Pod template’s specification: spec field, indicates that the Pods run one container, nginx, which runs the nginx Docker Hub latest image.
