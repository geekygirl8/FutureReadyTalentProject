# FutureReadyTalentProject
HealthBot mainly detects Heart Problems and mental health of the Patient



# Deploy Reference Architecture for Microsoft Healthcare Bot 
This GitHub repo. contains the ARM template for deploying Health Bot reference architecture.

# Contents
heartbotdeploy.json, README.md, mental_health_screener_questions.json

# Prerequisites

1. A GitHub Account to clone and/or fork this repository.

2. An Azure Resource Group with Owner Role permission. All Azure resources will be deployed into this resource group.

3. A Health Bot instance. Refer to Create your first Healthcare Bot quickstart in the Health Bot documentation.

4. Review the ARM template azuredeploy.json before proceeding. Update the resource configuration parameters to meet your requirements.

5. (Optional) The following CLI tools are preinstalled in Azure Cloud Shell. In case you are planning to use a workstation or a VM to deploy the ARM template, install the CLI tools before proceeding. Links for downloading the tools are provided in the next section.

    1. Azure CLI
    2. GitHub CLI

# Reference Architecture

1. The aim of this reference architecture is multifold.

2. Help customers quickly deploy Microsoft Health Bot and Cognitive Services resources in Production region on Azure.

![DeployArch-v10](https://user-images.githubusercontent.com/68231592/147698640-981427f2-d1ab-498b-b8e4-9284de1d0a3f.jpg)

# Deploy ARM Template to provision Health Bot resources

# 1. Follow the steps below to deploy the Health Bot resources on Azure.

Review and update template parameters in the azuredeploy.parameters.json file

Refer to the table below for a description of the template parameters. Configure the values as per your requirements.

![Template Parameters](https://user-images.githubusercontent.com/68231592/147698976-3a1bc590-b499-4330-afa7-74a0a347c20d.png)

# 2. Login to Azure

https://azure.microsoft.com/en-in/features/azure-portal/

# 3. Verify Azure Resources

Login to the Azure portal. Confirm all resources were provisioned in the resource group correctly.

# Deployment of Azure Health Bot


![AzurePortal1](https://user-images.githubusercontent.com/68231592/147699317-2fadcf90-2241-4c5b-92ae-6103dbf67c90.png)

![AzurePortal2](https://user-images.githubusercontent.com/68231592/147699357-19bd8961-ec5d-400a-bade-b69423316c80.png)

![AzurePortal3](https://user-images.githubusercontent.com/68231592/147699374-1e5f58e0-4761-4f90-b1da-2555848d7112.png)

# Azure Health Bot Service Portal


![AzureHealthBotServicePortal1](https://user-images.githubusercontent.com/68231592/147699564-832bc622-8def-4595-b2df-188d63e803d2.png)

![AzureHealthBotServicePortal2](https://user-images.githubusercontent.com/68231592/147699581-2f54137c-5996-45da-abf7-cd7b3a437b0a.png)

# Azure Health Bot Workspace

![AzureHealthBotWorkspace](https://user-images.githubusercontent.com/68231592/147699607-970f3122-34bd-4ff8-9d5e-32aa9ede569c.png)

# Azure HeartBot Feedback

![Output13](https://user-images.githubusercontent.com/68231592/147699686-6e1fc28a-1709-4e8c-8c74-772d211ca009.png)

![Output14](https://user-images.githubusercontent.com/68231592/147699706-1b1835c0-3b7b-430e-b693-c1efb286ae41.png)

![Output15](https://user-images.githubusercontent.com/68231592/147699734-05bc995b-7062-451a-9883-3b8502491b8b.png)

# Azure Health Bot Json File

![Screenshot (408)](https://user-images.githubusercontent.com/68231592/147699775-a5a2ecdd-9a69-4767-9cf8-9181be6fcb80.png)

# Azure Health Bot Report 

![AzureHealthBotReport](https://user-images.githubusercontent.com/68231592/147699806-dd148662-613c-47dc-8347-9eca2044a5f5.png)



# Conclusion

The Health Bot Service is a cloud platform that empowers developers in Healthcare organizations to build and deploy their compliant, AI-powered virtual health assistants and health bots, that help them improve processes and reduce costs. In this project, the Heart Bot is mainly comes from the Azure Health Bot. The Health Bot Service is ideal for developers in IT departments of healthcare organizations such as providers, pharmaceutical companies, tele-medecine providers, and health insurers. This Heart Bot mainly explains to the patients about the heart problems on various symptoms,complications, causes and risk factors etc.

# Thank You
