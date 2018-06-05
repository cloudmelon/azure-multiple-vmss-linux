# Deploy a VM Scale Set of VMs with a custom script extension with multiple vmss in  Existing VNET with managed disks

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/cloudmelon/cloudmelonazurearm/blob/master/vmss-linux-master-slave-extension/azuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https://github.com/cloudmelon/cloudmelonazurearm/blob/master/vmss-linux-master-slave-extension/azuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>



## Solution overview and deployed resources

This template allows you to deploy a VM Scale Set of Linux VMs and create a new virtual network at the same time. These VMs have a custom script extension for customization and are behind a load balancer with NAT rules for rdp connections. 