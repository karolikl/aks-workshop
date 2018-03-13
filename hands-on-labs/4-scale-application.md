# Challenge #4: Scale your application

## Description

As you now have an application running on Azure Container Service (AKS), we will have a look at how you can scale your application to support a variance in load. 

The goal of this challenge is to change your cluster's capacity for hosting workloads by scaling the number of Azure VM nodes running in the cluster. You should also configure autoscaling for your pods to adjust the number of pods in a deployment depending on CPU utilization.

## Success criteria

The team should work together to manually scale the number of Azure VM nodes running in the cluster. 

The team should work use horizontal pod autoscaling to configure your container to request 20% CPU. If the CPU utilization exceeds 40%, increases the number of pods to a maximum of 5.

## References

[Scale application in Azure Container Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/tutorial-kubernetes-scale)  
[Horizontal Pod Autoscaler Walkthrough](https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale-walkthrough/)  

Other useful resources:

[Kubernetes documentation](https://kubernetes.io/docs/home/?path=users&persona=app-developer&level=foundational)  
[kubectl overview](https://kubernetes.io/docs/reference/kubectl/overview/)  
[Azure CLI reference](https://docs.microsoft.com/en-us/cli/azure/get-started-with-azure-cli?view=azure-cli-latest)


