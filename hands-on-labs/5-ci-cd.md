# Challenge #5: Set up a CI/CD pipeline towards your cluster

## Description

Until now, all deployments towards the Azure Container Service (AKS) cluster have been done manually. Your goal now is to set up a CI/CD pipeline using your preferred CI/CD tool (Visual Studio Team Services, Jenkins, TeamCity etc.) to automate the building of Docker images and the deployment to the cluster. 

## Success criteria

The team should work together to set up a continuous integration pipeline that builds the Docker image and pushes is to the Azure Container Registry. 

The team should work together to set up a continuous delivery pipeline that creates a new deployment in Azure Container Service (AKS). You need to ensure that the Kubernetes manifest file containing the deployment is available as an artifact from your CI-build so that you are able to create a new deployment.  

_Hint: Take a look at the best-practice CI/CD architectures below_   
- [CI/CD for Containers (using VSTS)](https://azure.microsoft.com/en-us/solutions/architecture/cicd-for-containers/)   
- [Container CI/CD using Jenkins and Kubernetes on Azure Container Service (AKS)](https://azure.microsoft.com/en-us/solutions/architecture/container-cicd-using-jenkins-and-kubernetes-on-azure-container-service/)

## References

[Continuous deployment with Jenkins and Azure Container Service](https://docs.microsoft.com/en-us/azure/aks/jenkins-continuous-deployment)  
[Creating a CI/CD pipeline on Azure Container Services with Kubernetes and Visual Studio Team Services](https://dgkanatsios.com/2017/05/29/creating-a-cicd-pipeline-on-azure-container-services-with-kubernetes-and-visual-studio-team-services/)  
[VSTS: Implement continuous deployment of your app using Kubernetes to Azure Container Service](https://docs.microsoft.com/en-us/vsts/build-release/apps/cd/azure/deploy-container-kubernetes)


