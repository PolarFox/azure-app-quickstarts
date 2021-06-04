# Azure Functions C# quickstart template

Starting point for Azure Functions C# with consumption plan.
Does not use slots.

* Copy files from this path to your project.
* Fix *deployment/azure-pipeline.yml*
  * functionName: Your Azure Function App resource name.
  * functionPath: Relative path to your C# AzFunc project
  * azureSubscription parameter in AzureFunctionApp@1 Task: Your Azure Service Connector from DevOps

<https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/deploy/azure-function-app?view=azure-devops>

<https://docs.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints?view=azure-devops&tabs=yaml>
