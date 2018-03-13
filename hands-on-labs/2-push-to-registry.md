# Challenge #2: Push image to Docker registry

## Description

Your goal is to push the Docker image from [Challenge #1](./1-dockerize.md) to a private Docker registry. In these labs, we will use Azure Container Registry, alternatively you could use DockerHub. 

Azure Container Registry allows you to store and manage images for all types of container deployments including DC/OS, Docker Swarm, Kubernetes, and Azure services such as App Service, Batch, Service Fabric, and others. It will allow you to efficiently manage a single registry replicated across multiple regions and eliminate ingress/egress charges by keeping your Docker registry in the same data center as your deployments. As Azure Container Registry is compatible with the open-source Docker Registry v2, you can use the same open-source Docker CLI tools you already know and the skills you have to efficiently interact with the registry.

## Success criteria

Everyone on your team must push a Docker image to your Azure Container Registry and you should verify that they exist in the registry when logging into the [Azure portal](https://portal.azure.com/).   
_Hint_: Use image tags to separate the images from each other. 

## References

[Deploy and use Azure Container Registry](https://docs.microsoft.com/en-us/azure/aks/tutorial-kubernetes-prepare-acr)  
[Azure Container Registry Documentation](https://docs.microsoft.com/en-us/azure/container-registry/)  
[Azure CLI Reference](https://docs.microsoft.com/en-us/cli/azure/get-started-with-azure-cli)

