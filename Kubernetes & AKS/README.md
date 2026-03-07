# **KUBERNETES & AKS — SPOKEN VERSION**  

1. **What is Kubernetes?**

    > Kubernetes is a container orchestration platform.
    > It helps to manage, deploy, and scale containerized applications.
    > It automatically handles load balancing and self-healing.
    > If a container fails, Kubernetes restarts it.
    > It is widely used for microservices architecture.
##

2. **What is Azure Kubernetes Service (AKS)?**

    > AKS is a managed Kubernetes service provided by Azure.
    > Azure manages the control plane and cluster maintenance.
    > We only manage worker nodes and applications.
    > It reduces operational overhead and saves time.
    > It is used to deploy containerized workloads easily.

##
3. **What is a Pod in Kubernetes?**

    > A Pod is the smallest deployable unit in Kubernetes.
    > It contains one or more containers.
    > Containers inside a pod share network and storage.
    > Pods are used to run applications in the cluster.
    > If a pod fails, Kubernetes creates a new one.

##
4. **What is a Node in Kubernetes?**

    > A Node is a worker machine in Kubernetes cluster.
    > It can be a virtual machine or physical server.
    > Nodes run pods and containerized applications.
    > Each node is managed by the Kubernetes control plane.
    > Multiple nodes form a cluster.

##
5. **What is a Cluster in Kubernetes?**

    > A Cluster is a group of nodes working together.
    > It includes control plane and worker nodes.
    > The control plane manages cluster operations.
    > Worker nodes run application workloads.
    > Clusters ensure high availability and scalability.

##
6. **What is a Node Pool in AKS?**

    > Node Pool is a group of nodes with same configuration.
    > It helps to separate different types of workloads.
    > For example, system workloads and user workloads.
    > Each node pool can have different VM sizes.
    > It improves resource management.

##
7. **How do you troubleshoot Pod failures?**

    > First, I check pod status using kubectl get pods.
    > Then I check logs using kubectl logs command.
    > I describe the pod to see events and errors.
    > I check resource usage like CPU and memory.
    > If needed, I restart or redeploy the pod.

##
8. **What is Service in Kubernetes?**

    > A Service exposes pods to internal or external traffic.
    > It provides a stable IP address and DNS name.
    > Even if pods change, service remains constant.
    > It helps applications communicate reliably.
    > There are different service types like ClusterIP and LoadBalancer.

##
9. **What is Ingress in Kubernetes?**

    > Ingress manages external access to services.
    > It provides HTTP and HTTPS routing.
    > It helps to expose multiple services using single IP.
    > It supports load balancing and SSL termination.
    > It improves traffic management.

##
10. **How do you achieve Zero Downtime Deployment in Kubernetes?**

    > I use rolling updates strategy in deployments.
    > New pods are created before old pods are terminated.
    > Multiple replicas ensure application availability.
    > Readiness probes check pod health before traffic routing.
    > This ensures users experience no downtime.

##
11. **What happens if Node fails?**

    > If a node fails, pods running on that node stop.
    > Kubernetes automatically reschedules pods on healthy nodes.
    > This ensures application availability.
    > Auto-scaling can add new nodes if required.
    > It provides high availability.

##
12. **How do you scale applications in Kubernetes?**

    > Applications are scaled by increasing pod replicas.
    > We can scale manually or automatically.
    > Horizontal Pod Autoscaler adjusts replicas based on CPU usage.
    > This helps to handle high traffic.
    > It improves performance and reliability.

##
13. **If Kubernetes services go down, how do you troubleshoot?**

    > First, I check pod status using kubectl commands.
    > Then I check logs to find error messages.
    > I verify node health and resource usage.
    > I check network and service configuration.
    > If needed, I restart or redeploy services.

##
14. **How do you design Multi Node Pool in AKS?**

    > In AKS, node pools are used to separate workloads.
    > I create one pool for system workloads.
    > Another pool is created for user applications.
    > Each pool can have different VM sizes.
    > This improves performance and resource management.

##
15. **How do you fix deployment issues in production?**

    > First, I check application and pod logs.
    > I verify recent code changes and configuration.
    > I check resource usage like CPU and memory.
    > If needed, I rollback to previous stable version.
    > Then I monitor application after fix.

##
16. **How do you restrict Namespace access?**

    > Namespace access is controlled using RBAC.
    > Roles and RoleBindings define user permissions.
    > Only authorized users can access resources.
    > We assign permissions at namespace level.
    > This improves cluster security.

##
17. **What is HPA and difference between HPA and VPA?**

    > HPA stands for Horizontal Pod Autoscaler.
    > It increases or decreases number of pods based on load.
    > VPA stands for Vertical Pod Autoscaler.
    > It increases CPU and memory of existing pods.
    > HPA scales out, VPA scales up.

##
18. **What is a DaemonSet?**

    > DaemonSet ensures one pod runs on every node.
    > It is used for monitoring and logging agents.
    > When a new node is added, pod is created automatically.
    > It helps run background services on all nodes.
    > Example: Log collectors.

##
19. **What is StatefulSet?**

    > StatefulSet is used for stateful applications.
    > It provides stable network identity to pods.
    > Each pod gets persistent storage.
    > Pods are created and deleted in order.
    > It is used for databases.

20. **How to configure pod communication in AKS?**

    > Pods communicate through Kubernetes Services.
    > Each service gets a stable Cluster IP.
    > Pods use DNS names to talk to each other.
    > Network policies control traffic between pods.
    > This ensures secure communication.

21. **Explain KEDA configuration**

    > KEDA stands for Kubernetes Event Driven Autoscaling.
    > It scales pods based on external events like queue length.
    > It works with metrics from Kafka, Azure queues, etc.
    >  We define triggers and scaling rules in YAML.
    > KEDA helps scale workloads efficiently.

22. **Experience in managing TLS certificates in AKS**

    > Yes, I have managed TLS certificates in AKS.
    > Certificates secure application traffic using HTTPS.
    > We store certificates as Kubernetes secrets.
    > Ingress controller uses them for secure routing.
    > Cert-manager helps automate certificate renewal.
