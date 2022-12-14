# Formula1-DataFactory


## What does the Formula1 pipeline do ?
...

## How to get this pipeline to work ?

1. Running the pipeline of Formula1-Terraform, you can find a Azure Data Factory under your resource group.
2. Open the Data-Factory and clone this repository into ADF and all pipeline should be ready to work.
3. Make sure the service-principal has enough permission over key-vault to GET the secrets from keyvault and share it with DataFactory (Keyvault-> Access Configuration)
4. Make sure Data Factory is connected to Databricks as one of the steps is clearing the data
