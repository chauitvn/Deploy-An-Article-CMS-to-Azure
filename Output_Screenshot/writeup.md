# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

*I opted for the web app service over a virtual machine for several reasons:*

- *Cost-Effectiveness: Web app services are more cost-effective than virtual machines.*
- *Maintenance and Setup: Web apps eliminate the labor-intensive maintenance and intricate processes of VM setup, which demands comprehensive security configurations.*
- *Deployment Efficiency: Web apps not only offer a more user-friendly development experience but their integration with platforms, such as GitHub, greatly streamlines the deployment process.*
- *Reliability & Availability: While web apps and VMs might seem comparable in availability, VMs have the potential to compromise reliability due to additional user configurations and associated risks. With VMs requiring occasional restarts and OS maintenance, a web app is likely to offer better uptime.*
- *Scalability: The web app aligns perfectly with my current needs and allows for easy future scaling, saving both money and time compared to a VM.*

*Conclusion: Taking into account factors like cost, scalability, reliability, and workflow efficiency, the web app service emerged as the optimal choice for my project's specifications.*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

* I might contemplate using a virtual machine if it offered:*
- *More straightforward, "plug-and-play" templates for web app services.*
- *Seamless integration for continuous deployment.*

*This stands in contrast to the PAS web app services on Azure, which provide:*
- *eamless integration of changes and deployments from sources like GitHub.*

Given the effort involved in setting up a virtual machine — ensuring its security and keeping it current — I don't foresee a change in this perspective in the near future.