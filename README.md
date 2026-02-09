# *k8s tasks:-*
### *1) MCQ's*
Q1] what is the smallest unit that kubernetes deploys?
```
A. Node 
B. Pod
C. Service
D. Container
```

Ans: **C. Pod**

Q2] which kubernetes object used to expose pods to network traffic?
```
A. Pod
B. Deployment
C. Service
D. Namespace
```

Ans: **C. Service**

Q3] which service type is used only for internal communication inside the cluster?
```
A. Nodeport
B. Loadbalancer
C. ClusterIp
D. Externalname
```

Ans: **C. ClusterIp**

Q4] you want to access an application using <NodeIp>:<Port>,which service type should you use?
```
A. ClusterIp
B. Nodeport
C. Loadbalancer
D. Headless
```

Ans: **B. NodePort**

Q5] which Service type is mainly used in cloud environments to expose application externally?
```
A. ClusterIp
B. Nodeport
C. Loadbalancer
D. Externalname
```

Ans: **C. Loadbalancer**

Q6] A Pod is deleted accidentally. which Pod type can automatically recreate it?
```
A. Stanalone Pod
B. Static Pod
C. pod managed by deployment
D. init Pod
```

Ans: **C. Pod managed by deployment**

Q7] which Pod type is used to run initialization tasks before the main container starts?
```
A. Sidecar Pod
B. init Pod
C. static Pod
D. Multi-container Pod
```

Ans: **B. init pod**

Q8] Containers inside the same Pod communicate using:
```
A. Different IP addresses
B. Service only
C. Same IP addresses
D. External Loadbalancer
```

Ans: **C. Same Ip addresses**

Q9] which service assign a stable internal IP address automatically?
```
A. Node port
B. Loadbalancer
C. Cluster ip
D. Externalname
```

Ans: **C. Cluster ip**

Q10] you create a service, but traffic is not reaching the Pod. What is the most common reason?
```
A. Wrong image 
B. Lable missmatch
C. Pod crash
D. Node failure
```

Ans: **B. Label missmatch**

Q11] which kubernetes component provides DNS-based service discovery?
```
A. Kubelet
B. Kube-proxy
C. CoreDNS
D. Scheduler
```

Ans: **C. CoreDNS**

Q12] you want a Pod to always run on a specific Node. which Pod type is used?
```
A. init pod
B. Sidecar pod
C. Static pod
D. Ephemeral pod
```

Ans: **C. Static Pod**

Q13] which service type exposes a fixed Port on every node?
```
A. ClusterIp
B. Nodeport
C. Loadbalancer
D. Externalname
```

Ans: **B. Nodeport**

Q14] you want Pods inside the cluster to access an application using a DNS name. which service type should you use?
```
A. Nodeport
B. Loadbalancer
C. ClusterIp
D. Externalname
```

Ans: **C. ClusterIp**

Q15] which command shows the IP address of a Pod?
```
A. kubectl get nodes
B. Kubectl logs Pod
C. Kubectl get pods -o wide
D. kubectl describe service
```

Ans: **C. Kubectl get pods -o wide**

Q16] you create a loadbalancer service in a local cluster. what usually happens?
```
A. External IP is assigned immediately
B. External IP stays pending
C. Pod is deleted
D. Service creation is fails
```

Ans: **B. Externam IP stays pending**

Q17] which Pod type is commonly is used to support a main application with logging or monitoring?
```
A. init Pod 
B. Standalone Pod
C. Sidecar Pod
D. Static Pod
```

Ans: **C. Sidercar Pod**

Q18] which service field desides which Pods receive traffic?
```
A. Ports
B. type
C. Selector
D. Metadata
```

Ans: **C. Selector**

Q19] which command is used to list all services in a namespace?
```
A. Kubectl get Pods
B. Kubectl get svc
C. Kubectl describe Pod
D. Kubectl logs svc
```

Ans: **B. Kubectl get svc**

Q20] Two Pods in the same namespace want to communicate. what is the recommended kubernetes way?
```
A. Use Pod IP directly
B. Use Service name
C. Use Node IP
D. Use External IP
```

Ans: **B. Use Service name**

### *2) Practical Assignment* ### 

#### *Deployment Details:*
- Deployment Name: mydeploy
- Replicas: 3
- Image: nginx

#### *Service Details:*
- Service Name: myservice
- Service Type: Nodeport

#### *Application Access URL:*
```
http://13.51.158.228:30578
```
---
#### *Command Output:*
![](/img/Screenshot%202026-02-09%20231552.png)

---
#### *Browser Output:*
![](/img/Screenshot%202026-02-09%20231718.png)