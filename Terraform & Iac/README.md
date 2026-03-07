# **TERRAFORM & INFRASTRUCTURE AS CODE — SPOKEN VERSION**  

1. **What is Infrastructure as Code (IaC)?**

    > Infrastructure as Code means managing infrastructure using code.
    > Instead of manual setup, we write configuration files.
    > These files create servers, networks, and databases automatically.
    > It reduces human errors and saves time.
    > It also allows version control and easy automation.

##
2. **What is Terraform?**

    > Terraform is an Infrastructure as Code tool.
    > It is used to provision cloud resources automatically.
    > It supports multiple cloud providers like Azure and AWS.
    > We write configuration using HCL language.
    > It helps to manage infrastructure efficiently.

##
3. **What is Terraform State File?**

    > Terraform state file stores current infrastructure details.
    > It tracks which resources are created and managed.
    > Terraform uses it to plan future changes.
    > Without state file, Terraform cannot track resources properly.
    > It is very important for infrastructure management.

##
4. **Where do you store Terraform State File?**

    > I store Terraform state file in remote backend.
    > Usually, I use Azure Storage Account for this.
    > It helps team members collaborate easily.
    > It also provides state locking to avoid conflicts.
    > Remote storage improves security and reliability.

##
5. **What is Terraform Plan and Apply?**

    > Terraform Plan shows what changes will happen.
    > It compares existing infrastructure with new configuration.
    > Terraform Apply actually creates or updates resources.
    > Plan helps to avoid mistakes before execution.
    > Apply performs the real deployment.

##
6. **Difference between ARM Templates and Terraform?**

    > ARM Templates are native to Azure cloud.
    > Terraform supports multiple cloud platforms.
    > Terraform is easier to write and manage.
    > ARM templates use JSON which is complex.
    > Terraform is better for multi-cloud environments.

##
7. **How do you manage Terraform state file in CI/CD pipeline?**

    > Terraform state file should be stored in remote backend.
    > I use Azure Storage Account for remote storage.
    > It supports state locking to avoid conflicts.
    > Team members can collaborate easily.
    > It improves security and reliability.
