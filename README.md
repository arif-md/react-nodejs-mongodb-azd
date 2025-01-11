# Initialize, provision resources and deploy app to Azure using AZD
## Prerequisites
* VS Code
* VS Extension: Azure Developer CLI
* Install azd from Powershell
    - powershell -ex AllSigned -c "Invoke-RestMethod 'https://aka.ms/install-azd.ps1' | Invoke-Expression"
## Initialize new app
* F1 => Azure Developer CLI (azd): Initialize app (init) => select a template => React Web App with Node.js API and MongoDB on Azure
## Provision and deploy the app resources
* Terminal => azd auth login
* F1 => Azure Developer CLI (azd): Package, Provision and Deploy(up)
