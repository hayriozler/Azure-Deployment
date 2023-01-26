# Do you need to deploy an application to Azure?  I am going to try to explain step by step which components or services you need and how they can automatically deploy it

 1. ***Infrastructure***
    1. **Network**
       1. [NSG(Network Security Groups)](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/nsg.md)
       2. [virtual Network](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/vnet.md)
       3. [Subnets](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/subnet.md)
       4. [VNet Peering](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/vnetpeering.md)
       5. [Route tables](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/routetable.md)
       6. [Traffic Managers](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/azuretrafficmanager.md)
       7. [Gateways](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/gateway.md)
       8. [Certifications](https://github.com/hayriozler/Azure-Deployment/blob/master/Infrastructure/certificate.md)
    2. **Azure Kubernetes cluster**
       1. [Azure container registry](https://github.com/hayriozler/Azure-Deployment/blob/master/Kubernetes/acr.md)
       2. [AKS](https://github.com/hayriozler/Azure-Deployment/blob/master/Kubernetes/aks.md)
    3. **DNS**
       1. [DNS zones](https://github.com/hayriozler/Azure-Deployment/blob/master/Kubernetes/dnszone.md)
    4. **Key vaults**
       1. [Storing secrets and certifications](https://github.com/hayriozler/Azure-Deployment/blob/master/KV/keyvaults.md)
    5. **Data Stores (Optional)**
       1. [Databases(SQL Azure databases)](https://github.com/hayriozler/Azure-Deployment/blob/master/DataStore/sql.md)
       2. [Redis](https://github.com/hayriozler/Azure-Deployment/blob/master/DataStore/redis.md)
    6. **Azure policies (Optional)**
    7. **Monitoring Services (Optional)**
 2. ***Application API Deployment***
    1. **Step-by-step API Deployment to AKS**
    2. **Use Configmap for certification and user database secrets**
 3. ***Front-End Deployment***
    1. **Step-by-step Web Framework deployment into AKS**
