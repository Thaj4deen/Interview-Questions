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
