# CONFIGURATION_MANAGEMENT

Goals

Use Terraform to provision the infrastructure</br> from here ---> https://github.com/iliyab09/TerraformForAzure-IaC</br>
Create two environments: Staging and Production</br>
![StagProdPic](https://user-images.githubusercontent.com/16802411/140538232-6f5f8fe5-1f2d-4baa-819c-fd26cf3fb7ba.png)

Use Ansible to deploy the NodeWeightTracker application</br>
Both environments must be identical except for the size of the vms (production ones must be larger)</br>

![image](https://user-images.githubusercontent.com/16802411/140537162-474cf1be-ab24-4935-a269-e4f6274c0155.png)


Ansible playbook(s) to configure the servers created by terrafor. To achieve this we will need to provision environment.
