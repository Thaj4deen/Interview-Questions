# **AZURE CLOUD — SPOKEN VERSION**  

 1. **What Azure services have you used?**
   
    > I have worked with several Azure services in my projects.
    > I used Azure App Service to host web applications.
    > I worked with Azure Virtual Machines and Azure SQL Database.
    > I also used Azure Kubernetes Service, Storage Accounts, Monitor, and Key Vault.
##
 2. **How did you deploy a web application in Azure?**

    > I deployed applications using Azure App Service.
    > First, I created the App Service and configured runtime settings.
    > Then I deployed the code using Azure DevOps pipeline.
    > Finally, I configured domain and security settings.
##
 3. **If your web app is not working after deployment, how do you troubleshoot?**

    > First, I check application logs to see error messages.
    > Then I verify app settings and connection strings.
    > I restart the application and test again.
    > If needed, I check database connectivity and backend services.
##
 4. **What is a Resource Group in Azure?**

     > A Resource Group is a logical container in Azure.
     > It helps to group related resources together.
     > We can manage permissions and monitor costs easily.
     > It also helps to organize cloud resources properly.

##
 5. **How do resources in different Resource Groups communicate?**

     > Resource Groups do not communicate directly.
     > Resources inside them communicate through networking services.
     > We use Virtual Networks, VNet peering, or private IP addresses.
     > Communication depends on network configuration.

##
6. **How do you securely connect a web app to a database?**

    > We connect using connection strings in application settings.
    > Database access is controlled using firewall rules.
    > For better security, we use Private Endpoint and VNet integration.
    > We store credentials securely in Azure Key Vault.

##
7. **How do you securely connect a web app to a database?**

    > We connect using connection strings in application settings.
    > Database access is controlled using firewall rules.
    > For better security, we use Private Endpoint and VNet integration.
    > We store credentials securely in Azure Key Vault.

##
8. **What is Private IP configuration in Azure?**

    > Private IP is used for internal communication in Azure network.
    > It is assigned when we connect resources to a Virtual Network.
    > Azure automatically provides the private IP address.
    > It helps services communicate securely inside the network.

##
9. **What is the best way to connect an application to a database?**

    > The best way is using Private Endpoint with VNet integration.
    > It avoids public internet exposure.
    > This improves security and performance.
    > It is recommended for production environments.
    
##
10. **What is the difference between Public Cloud and Private Cloud?**

    > Public cloud is shared infrastructure provided by cloud companies.
    > It is cost-effective and easy to scale.
    > Private cloud is dedicated to one organization.
    > It provides more control and better security.
   
##
11. **What is Hybrid Cloud?**

    > Hybrid cloud is a combination of on-premises and public cloud.
    > Both environments are connected using secure network.
    > It helps organizations move gradually to the cloud.
    > It is useful for backup and disaster recovery.

##
12. **Have you worked on Hybrid Cloud?**

    > Yes, I worked in a hybrid cloud environment.
    > We connected on-premises servers to Azure using Site-to-Site VPN.
    > It created secure communication between both environments.
    > It was used for data transfer and backups.

##
13. **If you have a web application using a database, how will you integrate them?**

    > We connect them using connection strings in the application.
    > Database firewall rules allow the application to connect securely.
    > For better security, we use Private Endpoint.
    > Credentials are stored safely in Azure Key Vault.
    > This ensures secure and reliable communication.

##
14. **What is Network Security Group (NSG)?**

    > NSG is used to control network traffic in Azure.
    > It contains inbound and outbound security rules.
    > Rules allow or block traffic based on ports and IPs.
    > It protects virtual machines and subnets.
    > It improves network security.

##
15. **Difference between NSG and Azure Firewall?**

    > NSG works at subnet or VM level.
    > Azure Firewall works at network level.
    > Firewall provides advanced filtering and threat protection.
    > NSG is basic security, firewall is advanced security.
    > Firewall is used for centralized network protection.

##
16. **What is RBAC?**

    > RBAC means Role-Based Access Control.
    > It restricts access based on user roles.
    > Only authorized users can access resources.
    > It improves security and governance.
    > It is widely used in Azure.

##
17. **What is Azure Key Vault?**

    > Azure Key Vault is used to store secrets securely.
    > It stores passwords, certificates, and connection strings.
    > Applications access secrets securely without exposing them.
    > It improves application security.
    > It is commonly used in DevOps pipelines.

##
18. **What is Private Endpoint?**

    > Private Endpoint provides secure access to Azure services.
    > It connects services through private network.
    > Traffic does not go through public internet.
    > It improves security and performance.
    > It is recommended for sensitive applications.

##
19. **Difference between Azure Container Apps and AKS?**

    > Azure Container Apps is a serverless container service.
    > It is easy to use and requires less management.
    > AKS is a full Kubernetes service with more control.
    > AKS is better for complex applications.
    > Container Apps is suitable for simple microservices.

##
20. **What is the most cost-effective way to deploy Azure applications?**

    > Using Platform as a Service like Azure App Service is cost-effective.
    > Serverless services reduce infrastructure costs.
    > Auto-scaling helps reduce unused resources.
    > Reserved instances save long-term costs.
    > Proper resource planning reduces expenses.

##
21. **What are the differences between Azure App Service and other compute services?**

    > Azure App Service is a Platform as a Service.
    > It manages infrastructure automatically.
    > Virtual Machines require manual server management.
    > AKS is used for container orchestration.
    > App Service is easier for web applications.

##
22. **What are different ways to deploy applications?**

    > Applications can be deployed using VMs, App Service, Containers, or Serverless.
    > VM gives full control but needs management.
    > App Service is easy and managed by Azure.
    > Containers are flexible and portable.
    > Serverless is cost-effective for event-based workloads.

##
23. **What is Serverless Computing?**

    > Serverless computing runs code without managing servers.
    > Cloud provider handles infrastructure automatically.
    > We pay only for execution time.
    > It scales automatically based on demand.
    > Azure Functions is an example.

##
24. **What is Event-Driven Architecture?**

    > Event-driven architecture uses events to trigger processes.
    > One service sends an event and another service reacts.
    > It improves scalability and flexibility.
    > It reduces direct dependency between services.
    > It is used in microservices systems.

##
25. **What are different types of storage in Azure?**

    > Azure provides Blob Storage, Disk Storage, File Storage, and Queue Storage.
    > Blob Storage is used for files and media.
    > Disk Storage is used for Virtual Machines.
    > File Storage is used for shared file systems.
    > Queue Storage is used for message communication.

##
26. **Have you used Messaging Queue services?**

    > Yes, I used Azure Service Bus and Storage Queues.
    > Messaging queues help different services communicate.
    > They support asynchronous processing.
    > They improve scalability and reliability.
    > It is commonly used in microservices architecture.

##
27. **What is Queue Storage?**

    > Queue Storage is used to store messages between services.
    > It helps applications communicate asynchronously.
    > Messages are processed one by one.
    > It improves system reliability.
    > It is used in distributed applications.

##
30. **When to use Blob Storage and Disk Storage?**

   > Blob Storage is used to store files, backups, and media content.
   > It is good for unstructured data.
   > Disk Storage is used for Virtual Machine operating systems.
   > It provides high performance for applications.
   > Disk storage is mainly used for compute workloads.

##
31. **Which monitoring tools have you used?**

    > I used Azure Monitor to track performance and availability.
    > I worked with Log Analytics to analyze logs.
    > I used Application Insights for application monitoring.
    > I also used Prometheus and Grafana for container monitoring.
    > These tools help detect issues quickly.

##
32. **What is Azure Monitor?**

    > Azure Monitor is used to monitor Azure resources.
    > It collects metrics and logs from applications and servers.
    > It helps to detect performance issues.
    > Alerts can be configured for failures.
    > It improves system reliability.

##
33. **What is Prometheus?**

    > Prometheus is an open-source monitoring tool.
    > It collects metrics from applications and containers.
    > It stores data as time-series metrics.
    > It is commonly used with Kubernetes.
    > It helps to monitor system performance.

##
34. **What is Grafana?**

    > Grafana is a visualization tool for monitoring data.
    > It connects with Prometheus and other data sources.
    > It displays metrics using dashboards.
    > It helps teams understand system health easily.
    > It improves monitoring visibility.

##
35. **What kinds of AD migrations have you worked on?**

    > Active Directory migration means moving users and systems to a new domain.
    > It can be on-premises to on-premises migration.
    > It can be on-premises to Azure AD migration.
    > It includes user accounts, groups, and policies migration.
    > Tools like ADMT are commonly used.

##
36. **What is Entra ID?**

   > Entra ID is the new name for Azure Active Directory.
   > It is used for identity and access management.
   > It helps manage users, groups, and permissions.
   > It supports single sign-on for applications.
   > It improves security and authentication.

##
37. **What are Managed Services you have experience with?**

   > Managed services are cloud services managed by provider.
   > I worked with Azure App Service and Azure SQL Database.
   > I also used Azure Kubernetes Service.
   > These services reduce infrastructure management effort.
   > They help focus more on application development.

##
38. **How to connect database from outside Azure?**

   > To connect database externally, we allow public access.
   > We configure firewall rules to allow specific IPs.
   > We can use VPN for secure connection.
   > Private Endpoint can also be used for security.
   > Authentication credentials are required.

##
39. **Disaster recovery planning in Storage Accounts?**

   > Disaster recovery ensures data safety during failures.
   > Azure provides geo-redundant storage for backup.
   > Data is replicated to another region automatically.
   > We can restore data if primary region fails.
   > It improves business continuity.
