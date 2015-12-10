# Azure WebJobs Quickstart

Azure WebJobs provide an easy way to run background tasks on Azure App Service. The WebJobs SDK makes it easy to start jobs based on events like new Queue messages or new BLOBs.

Learn more about WebJobs:
 - [WebJobs Docs](http://aka.ms/webjobs-docs)
 - [WebJobs SDK GitHub](https://github.com/azure/azure-webjobs-sdk)
 - [WebJobs SDK Extensions GitHub](https://github.com/azure/azure-webjobs-sdk-extensions)

## Getting Started

1. Clone or download the repository
2. Open the solution with Visual Studio (2013/2015). Be sure to have the latest Azure SDK installed.
3. In the App.config, paste in your Azure Storage connection string for the following settings:
```
<add name="AzureWebJobsDashboard" connectionString="" />
<add name="AzureWebJobsStorage" connectionString="" />
```
4. Hit run to test locally - you'll see new Queue Messages created on a regular basis.
5. Right click on the solution and select "Publish as Azure WebJob" to publish to your App Service App (Web, Mobile, API, etc.)

## Contribute

Please follow the [Azure Contributor Guidelines](http://azure.github.io/guidelines.html). PR requests generally require you accept a CLA. Any issues with the SDK itself should created in the [WebJobs SDK GitHub](https://github.com/azure/azure-webjobs-sdk).

## License

[MIT](./LICENSE.txt)
