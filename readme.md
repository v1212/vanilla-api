# Vanilla API App


[Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview) allows you to easily build Javascript apps in minutes. Use this repo with the [Add an API to Static Web Apps with Azure Functions](https://docs.microsoft.com/azure/static-web-apps/add-api?tabs=vanilla-javascript) article to build and customize a new static site.

This repo is used as a starter for a _very basic_ web application with an API.

// This is SWA site in dedicated euap dm1


{
  "id": "/subscriptions/ab3c8876-0530-4f20-833d-ab75771fa1b6/resourceGroups/jianw-swa-testrg/providers/Microsoft.Web/staticSites/dswa-jianw-euapdm1-test1",
  "location": "Central US EUAP",
  "name": "dswa-jianw-euapdm1-test1",
  "properties": {
    "allowConfigFileUpdates": true,
    "areStaticSitesDistributedBackendsEnabled": false,
    "backendRegion": {
      "regionName": null,
      "status": "Ready"
    },
    "branch": "dswa-euapdm1",
    "contentDistributionEndpoint": "https://content-euapdm1.infrastructure.1.azurestaticappscanary.net",
    "customDomains": [],
    "databaseConnections": [],
    "defaultHostname": "blue-sky-0cd408a22.1.azurestaticappscanary.net",
    "enterpriseGradeCdnStatus": "Disabled",
    "keyVaultReferenceIdentity": "SystemAssigned",
    "linkedBackends": [],
    "prettyName": null,
    "prettyNameHostname": null,
    "prettyNameStatus": null,
    "privateEndpointConnections": [],
    "provider": "GitHub",
    "publicNetworkAccess": null,
    "repositoryUrl": "https://github.com/v1212/vanilla-api",
    "stableInboundIP": "20.228.56.169",
    "stagingEnvironmentPolicy": "Enabled",
    "stagingEnvironmentRegion": null,
    "targetResourceGroupResourceId": null,
    "trafficSplitting": {
      "environmentDistribution": {
        "default": 100
      }
    },
    "trialExpirationTimeUtc": null,
    "userProvidedFunctionApps": null
  },
  "resourceGroup": "jianw-swa-testrg",
  "sku": {
    "name": "Dedicated",
    "tier": "Dedicated"
  },
  "type": "Microsoft.Web/staticSites"
}
