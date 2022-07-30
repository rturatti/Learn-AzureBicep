# Learn-AzureBicep
Repository to learn Azure Bicep

Deploying Azure StorageAccount and ServiceApp with Azure Bicep.

### Variables
| prod | nonprod|

 ```az deployment group create \
  --template-file main.bicep \
  --parameters environmentType=nonprod
```