# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

\*Cost

- App Service: App Service costs are determined based on factors such as number of instances, compute resources, and additional features such as auto-scaling
- VM: The cost of virtual machines in Azure is determined based on factors such as the selected VM size, storage, network, and operating system. We pay for the compute and storage resources associated with the VM

\*Scalability

- App Service: App Service provides built-in autoscaling, allowing your application to scale or shrink automatically. Like it will automatically rebuild when they update the source code
- VM: Scaling virtual machines in Azure requires manual intervention. We are forced to configure and manage load balancers, create or delete VM instances

\*Availability

- App Service: App Service provides a high level of availability with built-in features such as automatically updating the operating system and underlying infrastructure management platform and ensuring the service is always highly available.
- VM: Availability of virtual machines depends on our individual configuration and management.

\*Workflow

- App Service:App Service simplifies the deployment and management of web applications. We can deploy applications directly and quickly from Git or Azure DevOps, CI/CD or deploy pre-built containers
- WM:We have more control over the infrastructure. We can install and configure the necessary software suite, manage virtual networks, and be flexible in customizing the environment (size, storage, network, ...)
  .
  .
  .
  .
  .

==> I choose deloy by App Service. Because the cost of App Service, we only need to pay for the resources (the right to use CPU, memory, ...) and the management service. As for VMs, we have to pay for virtual server resources, VM configuration, memory, hard drive and operating system.

APP_URL: https://dinhtvhm-article.azurewebsites.net/home
