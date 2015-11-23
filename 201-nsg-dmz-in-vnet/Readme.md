This template creates a VNet with 3 Subnets, Frontend, App Subnet and Database subnet. It also creates three Network Security groups one per each subnet. It cretaes DMZ rules for the App Subnet to expose endpoints to the Internet. It secures the App Subnet and the DB subnet with appropriate rules. It blocks Outbound Internet access to VMs in App and DBSubnets. It opens up DB Subnet only on the DB port to App Subnet.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://github.com/yalued/azure-quickstart-templates/blob/master/201-nsg-dmz-in-vnet/azuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
