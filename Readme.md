## Welcome to the course - Developing Scalable Applications using Azure

### The below description is to guide you on the lab setup required for this course.

## List of softwares to be installed
* [Git](https://git-scm.com/downloads)
* [VS Code](https://code.visualstudio.com/)
* [Extentions](https://code.visualstudio.com/docs/editor/extension-marketplace) - c#, Azure Tools, Kubernetes, Helm, Docker, Git Lens
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/)
* [.NET SDK 6.x (LTS)](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
* [Docker Desktop](https://www.docker.com/products/docker-desktop)
* [Helm](https://helm.sh/docs/intro/install/) 
* [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
* [Storage Explorer](https://azure.microsoft.com/en-us/features/storage-explorer/)


## Prerequisites
* [Azure Free Trial](https://azure.microsoft.com/en-in/free/)  
#### This will be provided during the course. However, it is recommended to create your own account for self-learning.


## Create an Azure Resource Group
Login to Azure account using Azure CLI
```sh
az login
```

Set default Azure subscription
```sh
az account set --subscription ”<Your Subscription Name>”
```

Create Resource Group
```sh
az group create -n <your-name>-labs-appservice -l eastus --tags courselabs=azure 
```

Get the current default subscription using list 
```sh
az account list --query "[?isDefault]"
```
<img width="425" alt="image" src="https://user-images.githubusercontent.com/11691661/224709571-c02b2308-dad7-40e7-ac50-016dd3a6b2b0.png">








