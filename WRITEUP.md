# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I chose the web app service because of these reasons:

- Cost Efficiency: In many cases, Azure App Service can be more cost-effective than managing VMs directly, especially for applications with variable workloads. With App Service, you only pay for the resources you use, and there are no upfront costs for infrastructure provisioning.

- Simplified Deployment: Azure App Service provides a Platform-as-a-Service (PaaS) offering that abstracts away the underlying infrastructure management. This simplifies the deployment process, allowing developers to focus more on application development rather than infrastructure configuration.

- Integrated Services: Azure App Service integrates seamlessly with other Azure services such as Azure SQL Database, Azure Cosmos DB, Azure Storage, and Azure Active Directory. This enables you to build robust and scalable applications by leveraging various Azure services without the complexity of managing separate infrastructure components.

- High Availability: Azure App Service offers built-in high availability and fault tolerance features, including multi-region deployments and automatic failover. This helps ensure that your application remains available and resilient to failures, providing a better experience for users.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Well, I don't make and see this changing in the near future. Because it cost a lot of throrough planning.

### Azure errors

My repo stucked at releasing & launching. Although my github CICD for deployment passed all and logged as successful, I cannot access my app url.

![alt text](/my_images/azure-error-launching.png)


![alt text](/my_images/successful-deployment.png)