FROM mcr.microsoft.com/azure-functions/node:3.0

ENV AzureWebJobsStorage 'DefaultEndpointsProtocol=https;AccountName=storageaccountlogicb531;AccountKey=NWAgx26+8eybzIAAi2fb/0eawpqTXDbUy1QfoireXzQd7Qx3uFCn9Ntj86fsqVXnVcXp6ZaCONMH8yGyDJ+hFw==;EndpointSuffix=core.windows.net'
ENV AZURE_FUNCTIONS_ENVIRONMENT Development
ENV AzureWebJobsScriptRoot=/home/site/wwwroot \
     AzureFunctionsJobHost__Logging__Console__IsEnabled=true \
     FUNCTIONS_V2_COMPATIBILITY_MODE=true

COPY . /home/site/wwwroot

RUN cd /home/site/wwwroot