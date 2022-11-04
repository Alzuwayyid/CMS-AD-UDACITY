# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

APP SERVICE:
The avalibility in addition to cost and scalability is somehow differ a bit between the two; also because the app service already supports the runtime and have already configured enviorment, the saved time might be a huge factor here.

VM:
VM would be a perfect choisce for developers who built there app using a legacy framework (or unspoorted by app service), which needs manual configuration.

My Choice:
I chose App Service because the app is considered light-weight, and considering all the factors plus time, app service would be the best choice.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

APP Service:
If the app requires greater compute power, for instance complex UI or data analytics; I would switch to VM.

VM:
Configuring the VM and patching it with backup might be time consuming and there must be a human resource responsibile for that, giving cost and time I would switch to App Service
