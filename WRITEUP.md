# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Azure App Service was used here for convenience as we can quickly build, deploy, and scale the CMS web app on a fully managed platform.
The platform is fully managed for operational and monitoring tasks. thus we can focus more on the features of the application itself without 
worrying about the operation and the infrastructure

The cost of app-service could be a little bit disadvantageous as we are always paying for the service plan, even if the application isn’t running.
 app service allows usage of up to maximum of 14GB of memory and 4 vCPU cores per instance. which is more than enough to this application due to simplicity as
 it doesn't required computation power or more memory.
 also app service offers high availability, auto-scaling and support of both Linux and Windows environments.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* On the other hand, Azure Virtual Machines is detailed as "*It provides on-demand, high-scale, secure, virtualized infrastructure *". You can create Linux and Windows virtual machines. It gives you the flexibility of virtualization for a wide range of computing solutions—development and testing, running applications, and extending your datacenter. It’s the freedom of open-source software configured the way you need it.
Azure Virtual Machines provides on-demand, high-scale, secure, virtualized infrastructure. Thus, I might choose this option
when I need the flexibility of virtualization, more controlled testing for the running applications, or when I need  to extending the CMS datacenter. 
as it is easier with VM to configure the application the way I need it.
