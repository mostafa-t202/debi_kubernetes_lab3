1- How many DaemonSets are created in the cluster in all namespaces? 

 

2- what DaemonSets exist on the kube-system namespace? 

 

3- What is the image used by the POD deployed by the kube-proxy DaemonSet 

Image:      registry.k8s.io/kube-proxy:v1.30.0 

4- Deploy a DaemonSet for FluentD Logging. Use the given specifications. Name: elasticsearch Namespace: kube-system Image: k8s.gcr.io/fluentd-elasticsearch:1.20 

 

 

5- Deploy a pod named nginx-pod using the nginx:alpine image with the labels set to tier=backend. 

 

6- Deploy a test pod using the nginx:alpine image. 

 

7- Create a service backend-service to expose the backend application within the cluster on port 80 

 

8- try to curl the backend-service from the test pod. What is the response 

 

9- Create a deployment named web-app using the image nginx with 2 replicas 

 

10- Expose the web-app as service web-app-service application on port 80 and nodeport 30082 on the nodes on the cluster 

 

11- access the web app from the node 

 

 

 

12- How many static pods exist in this cluster in all namespaces? 

 

13-On which nodes are the static pods created currently? 

Worker node 
