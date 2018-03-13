# Prerequisites for completing the hands-on-labs

## Docker

- [Docker for Windows](https://www.docker.com/docker-windows)
- [Windows Installation Guide](https://docs.docker.com/docker-for-windows/install/) 

or 

- [Docker for Mac](https://www.docker.com/docker-mac) 
- [Mac Installation Guide](https://docs.docker.com/docker-for-mac/install/) 

## Azure CLI

These hands-on labs require that you are running the Azure CLI version 2.0.27 or later. Run `az --version` to find the version. If you need to install or upgrade, see [Install Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli).

## kubectl CLI

To connect to the Kubernetes cluster from your client computer, use [kubectl](https://kubernetes.io/docs/user-guide/kubectl/), the Kubernetes command-line client.  

If you're using Azure CloudShell, kubectl is already installed. If you want to install it locally, run the following command: `az aks install-cli` (assuming you have Azure CLI installed from the previous step).

_Note: In order to access the Kubernetes dashboard, you will need to install kubectl locally._