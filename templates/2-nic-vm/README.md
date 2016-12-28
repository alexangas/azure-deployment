# Create a VM with 2 NICs

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Farangas%2Fazure-deployment%2Fmaster%2Ftemplates%2F2-nic-vm%2Ftemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Farangas%2Fazure-deployment%2Fmaster%2Ftemplates%2F2-nic-vm%2Ftemplate.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template creates:

* 1 virtual machine
* 2 network interfaces (NICs), front end and back end
* public IP address
* RDP connectivity
* load balancer
* associated storage accounts

It also provides many parameter options to allow a particular configuration.

Based on: https://github.com/Azure/azure-quickstart-templates/tree/master/201-1-vm-loadbalancer-2-nics
