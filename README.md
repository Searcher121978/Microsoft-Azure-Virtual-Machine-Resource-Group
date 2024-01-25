# Microsoft-Azure-Virtual Machine (VM)
Part 1 (Create a Virtual Machine) Azure virtual machines (VMs) can be created through the Azure portal. This method provides a browser-based user interface to create VMs and their associated resources.

1. Sign into Azure portal.
2. Enter virtual machines in the search.
3. Under Services, select Virtual Machines.
4. On the Virtual Machines page, select Create and then Azure virtual machine. The Create a Virtual Machine page opens.
5. Under Instance details, enter myVM for the Virtual machine name and choose Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 for the Image. Leave the other defaults.

![image](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/media/quick-create-portal/instance-details.png#lightbox)

On the right side, you see an example summary of the estimated costs. This updates as you select options that affect the cost, such as choosing Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 for your Image.

![image](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/media/quick-create-portal/windows-estimated-monthly-cost.png)

6. Under Administrator account, provide a username, such as azureuser and a password. The password must be at least 12 characters long and meet the defined complexity requirements.

![image](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/media/quick-create-portal/administrator-account.png)

7. Under Inbound port rules, choose Allow selected ports and then select RDP (3389) and HTTP (80) from the drop-down.

![image](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/media/quick-create-portal/inbound-port-rules.png)

8. Leave the remaining defaults and then select the Review + create button at the bottom of the page.

![image](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/media/quick-create-portal/review-create.png)

9. After validation runs, select the Create button at the bottom of the page.

![image](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/media/quick-create-portal/validation.png#lightbox) 

10. After deployment is complete, select Go to resource.

![image](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/media/quick-create-portal/next-steps.png) 

# Microsoft-Azure-Resource-Group
Part 2 (Create our Resources)
Create a Resource Group-A resource group is a container that holds related resources for an Azure solution. The resource group can include all the resources for the solution or only those you want to manage as a group.

1. Select Resource groups.
2. Select Create.
   
![image](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/media/manage-resource-groups-portal/manage-resource-groups-add-group.png#lightbox)

3. Enter the following values:

   - Subscription: Select your Azure subscription.
   - Resource group: Enter a new resource group name.
   - Region: Select an Azure location, such as Central US.
     
![image](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/media/manage-resource-groups-portal/manage-resource-groups-create-group.png#lightbox)

4. Select Review + Create
5. Select Create. It takes a few seconds to create a resource group.
6. Select Refresh from the top menu to refresh the resource group list, and then select the newly created resource group to open it. Or select Notification(the bell icon) from the top, and then select Go to resource group to open the newly created resource group.

![image](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/media/manage-resource-groups-portal/manage-resource-groups-add-group-go-to-resource-group.png#lightbox)

# List resource groups

1. To list the resource groups, select Resource groups. 
2. To customize the information displayed for the resource groups, configure the filters. The following screenshot shows the additional columns you could add to the display:

![image](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/media/manage-resource-groups-portal/manage-resource-groups-list-groups.png#lightbox)

# Open resource groups

1. Select Resource groups.
2. Select the resource group you want to open.

# Delete resource groups

1. Open the resource group you want to delete.
2. Select Delete resource group.

![image](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/media/manage-resource-groups-portal/delete-group.png#lightbox)

