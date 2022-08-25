# Azure-DevOps-AKS

This is the repo which contains sample dotnet code along with docker file and simple kubernetes deployment yaml files to start with Azure DevOps.

### Step  1:
Create project in Azure DevOps under your organization

### Step 2: 
Create ACR, kubernetes cluster in Azure portal

### Step 3:
Create required service connections between Azure DevOps portal and Azure services

### Step 4:
Create a service connetion for github if you wanted to use source repo from Github
(or)
You can import or push contents to Azure DevOps repos if you wanted to manage source code locally

### Step 5:
Set up CI and CD pipeline
Please refer to the pipeline defination that is attached with this repo.
I am will be updating both single stage and multi stages pipelines definations after 31/08/2022, you can refer as per your use.

### Step 6:
Once CICD pipelines are executed , go to AKS in azure portal and copy paste the public IP of service to see the output.

### Step 7:
Do some changes in source code (preferably in index.cshtml file) and see if CI/CD is triggered automatically and you can see the new output in AKS

Do watch the video in Cloudnloud youtube for detailed explaination for the same

Happy learning!!

