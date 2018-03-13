# Challenge #3: Deploy application to an AKS cluster

## Description

In the previous challenges, you packaged your application into a container image and this image was uploaded to Azure Container Registry. Your goal in this challenge is to deploy the container onto an Azure Container Services (AKS) cluster. 

Azure Container Service (AKS) manages your hosted Kubernetes environment, making it quick and easy to deploy and manage containerized applications without container orchestration expertise. It also eliminates the burden of ongoing operations and maintenance by provisioning, upgrading, and scaling resources on demand, without taking your applications offline.

## Success criteria

The team should work together to create a Kubernetes manifest file referencing the image container in your Azure Container Registry. The manifest must include a deployment and a load balancer. The application should be deployed to an Azure Container Service (AKS) cluster using the manifest file and you should be able to access the application.

## References

[Example Kubernetes manifest file](https://github.com/Azure-Samples/azure-voting-app-redis/blob/master/azure-vote-all-in-one-redis.yaml)  
[Run applications in Azure Container Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/tutorial-kubernetes-deploy-application)  
[Kubernetes deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)  
[Kubernetes services](https://kubernetes.io/docs/concepts/services-networking/service/)  

Other useful resources:

[Kubernetes documentation](https://kubernetes.io/docs/home/?path=users&persona=app-developer&level=foundational)  
[kubectl overview](https://kubernetes.io/docs/reference/kubectl/overview/)  
[Azure CLI reference](https://docs.microsoft.com/en-us/cli/azure/get-started-with-azure-cli?view=azure-cli-latest)


