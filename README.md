1- How many DaemonSets are created in the cluster in all namespaces? 

 <img width="652" alt="1" src="https://github.com/user-attachments/assets/8cb00013-917f-4891-ac34-0ec6c9f0c30e">


2- what DaemonSets exist on the kube-system namespace? 

 <img width="653" alt="2" src="https://github.com/user-attachments/assets/bd1e4e71-ac25-4879-b617-3faae4afa301">


3- What is the image used by the POD deployed by the kube-proxy DaemonSet 
<img width="653" alt="3" src="https://github.com/user-attachments/assets/f6ffe621-3bd4-46a8-8f37-13d56c62a964">


Image:      registry.k8s.io/kube-proxy:v1.30.0 

4- Deploy a DaemonSet for FluentD Logging. Use the given specifications. Name: elasticsearch Namespace: kube-system Image: k8s.gcr.io/fluentd-elasticsearch:1.20 

 <img width="659" alt="4 5" src="https://github.com/user-attachments/assets/b42be209-d417-447a-b7ff-0bc2b9fdc087">
<img width="645" alt="4 4" src="https://github.com/user-attachments/assets/64a895e4-0bf5-492e-b717-c663dfa3fa0b">
<img width="650" alt="4 3" src="https://github.com/user-attachments/assets/b0de02a1-78a4-4196-8712-407faaf82b8f">
<img width="657" alt="4 2" src="https://github.com/user-attachments/assets/054384c2-de2c-4f9e-b39b-fb30838fd343">
<img width="650" alt="4 1" src="https://github.com/user-attachments/assets/406a8226-cee1-4b55-9004-df891b2e0d13">


 

5- Deploy a pod named nginx-pod using the nginx:alpine image with the labels set to tier=backend. 
<img width="652" alt="5 4" src="https://github.com/user-attachments/assets/bead6e13-b3fb-4e74-9f45-e9e2aeeccdce">
<img width="654" alt="5 3" src="https://github.com/user-attachments/assets/e0a1bab9-1819-4917-9f14-8c2d91ba0ba2">
<img width="652" alt="5 2" src="https://github.com/user-attachments/assets/7a92b42c-39ce-4d19-b24f-01ad0549c058">
<img width="655" alt="5 1" src="https://github.com/user-attachments/assets/f37aa9e0-64d9-4b48-af44-18e4127f0534">

 

6- Deploy a test pod using the nginx:alpine image. 

 <img width="656" alt="6 4" src="https://github.com/user-attachments/assets/5d544b78-4cff-43ed-95d6-a4ef50309e06">
<img width="655" alt="6 3" src="https://github.com/user-attachments/assets/f62588e9-a0c8-4e53-b3ad-4b2afe7832e4">
<img width="653" alt="6 2" src="https://github.com/user-attachments/assets/62ad53b0-6d44-40b1-9829-aa2ef5141cff">
<img width="652" alt="6 1" src="https://github.com/user-attachments/assets/af9c1f38-950c-42c2-9a2d-366d41f0319f">


7- Create a service backend-service to expose the backend application within the cluster on port 80 

 <img width="652" alt="7 4" src="https://github.com/user-attachments/assets/781c83fe-981b-4468-86ec-772979251034">
<img width="651" alt="7 3" src="https://github.com/user-attachments/assets/90c40116-9682-4cdd-aec1-85e014ecd87c">
<img width="650" alt="7 2" src="https://github.com/user-attachments/assets/d99420bd-1a98-4fae-9ec8-a7b04139403b">
<img width="653" alt="7 1" src="https://github.com/user-attachments/assets/b9e29082-8504-426f-b9a3-a990955defc1">


8- try to curl the backend-service from the test pod. What is the response 
<img width="658" alt="8" src="https://github.com/user-attachments/assets/f4e326e1-eab5-4dfe-9e4d-014895e8f606">

 

9- Create a deployment named web-app using the image nginx with 2 replicas 

 <img width="656" alt="9 4" src="https://github.com/user-attachments/assets/1882de07-1c03-4df7-867a-1f3027caabb3">
<img width="661" alt="9 3" src="https://github.com/user-attachments/assets/a498889f-3b0a-46b3-9ab7-c81257b07a29">
<img width="658" alt="9 2" src="https://github.com/user-attachments/assets/407236cc-9f18-45a4-8877-c54a77a7cae5">
<img width="652" alt="9 1" src="https://github.com/user-attachments/assets/16d40967-dfa6-4672-953a-bab814abbb01">


10- Expose the web-app as service web-app-service application on port 80 and nodeport 30082 on the nodes on the cluster 

 <img width="655" alt="10 3" src="https://github.com/user-attachments/assets/ab607d31-0464-45e0-990c-42483ea37e98">
<img width="659" alt="10 2" src="https://github.com/user-attachments/assets/fca39c1d-eb8f-4be2-952d-185bb3f5aa47">
<img width="652" alt="10 1" src="https://github.com/user-attachments/assets/9dec5b99-2b1d-477a-9649-1bb91c4eebe6">


11- access the web app from the node 

 <img width="659" alt="10 4" src="https://github.com/user-attachments/assets/0bdf2ef5-0d5d-40fc-ad4a-36d9a34d9ab1">
 


 

 

12- How many static pods exist in this cluster in all namespaces? 

 <img width="651" alt="12" src="https://github.com/user-attachments/assets/816fa6ce-8e46-4c70-bfc2-e603821c3f28">


13-On which nodes are the static pods created currently? 

Worker node 
