# Web API Hello World

deploying a simple web api.

# things to remember

1. You need to update the Azure service principal details in github secrets section. 
1. delete your azure resources immediately after done with learning.
1. every time this workflow runs, it will create a new web app. so, you need to change the web app name every time you run it. 

# sample azure service principal

```
{
  "clientId": "",
  "clientSecret": "",
  "subscriptionId": "",
  "tenantId": "",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
```

# YAML file

You can create the resource group in your azure portal as per the name below or whatever name you create. Same with location. Keep location as it is, or, pick a location. Obviously, you need the subscription id and also the web app name.

```
env:
  RESOURCE-GROUP: devops_sep30
  LOCATION: centralindia
  TEMPLATE-FILE: infra/webapp.bicep
  SUBSCRIPTION-ID: enter-your-sub-id-here
  WEBAPP-NAME: web-app-name-here
```

# SKU

You can see about all available, SKUs, here, https://azure.microsoft.com/en-us/pricing/details/app-service/windows/#pricing 

# references

1. https://microsoftlearning.github.io/AZ-2008_DevOps_Foundations_Core_Principles_Practices/Instructions/Labs/03-implement-ci-cd-with-github-actions-and-iac-with-bicep.html

# book a session with me

1. [calendly](https://calendly.com/jaycodingtutor/30min)

# hire and get to know me

find ways to hire me, follow me and stay in touch with me.

1. [github](https://github.com/Jay-study-nildana)
1. [personal site](https://thechalakas.com)
1. [upwork](https://www.upwork.com/fl/vijayasimhabr)
1. [fiverr](https://www.fiverr.com/jay_codeguy)
1. [codementor](https://www.codementor.io/@vijayasimhabr)
1. [stackoverflow](https://stackoverflow.com/users/5338888/jay)
1. [Jay's Coding Channel on YouTube](https://www.youtube.com/channel/UCJJVulg4J7POMdX0veuacXw/)
1. [medium blog](https://medium.com/@vijayasimhabr)