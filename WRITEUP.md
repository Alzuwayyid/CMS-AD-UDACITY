# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

APP SERVICE:
The costs, scalability, and availability for a CMS app deployed through a App Sevice are reasonable. The avalibility in addition to cost and scalability is somehow differ a bit between the two; also because the app service already supports the runtime and have already configured enviorment, the saved time might be a huge factor here.
When choosing similar compute power, the app service costs less than the VM.
Azure App Service has constraints in terms of scalability. Azure VMs are preferred for apps, which have the scope to expand for the future.


VM:
The costs, scalability, and availability for a CMS app deployed through a VM are also reasonable. VM would be a perfect choisce for developers who built there app using a legacy framework (or unspoorted by app service), which needs manual configuration.
VM Would cost more, but there is a plenty of room for customization

My Choice:
I chose App Service because the app is considered light-weight, and considering all the factors plus time, app service would be the best choice.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

APP Service:
If the app requires more compute power, for instance data analytics or live streaming, the cost will increase rapidly. Also if there was functionality that is not supported by Azure, this would be a roadblock for sure. Not being able to configure the underlying server might results a blocker in the future.

VM:
Configuring the VM and patching it with backup might be time consuming ,and there must be a human resource responsibile for that, giving cost of providing training and hiring more human resource, app service would be a bette choice given it's nature of taking of the configuring-headache.
