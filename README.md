# CONFIGURATION_MANAGEMENT

![image](https://user-images.githubusercontent.com/16802411/140537162-474cf1be-ab24-4935-a269-e4f6274c0155.png)


Ansible is a software tool that provides simple but powerful automation for cross-platform computer support. It is primarily intended for IT professionals, who use it for application deployment, updates on workstations and servers, cloud provisioning, configuration management, intra-service orchestration, and nearly anything a systems administrator does on a weekly or daily basis. Ansible doesn't depend on agent software and has no additional security infrastructure, so it's easy to deploy.

Goals

Use Terraform to provision the infrastructure</br> from here ---> https://github.com/iliyab09/TerraformForAzure-IaC</br>
Create two environments: Staging and Production</br>
![StagProdPic](https://user-images.githubusercontent.com/16802411/140538232-6f5f8fe5-1f2d-4baa-819c-fd26cf3fb7ba.png)

Use Ansible to deploy the NodeWeightTracker application</br>
Both environments must be identical except for the size of the vms (production ones must be larger)</br>



Ansible playbook(s) to configure the servers created by terrafor. To achieve this we will need to provision environment.
