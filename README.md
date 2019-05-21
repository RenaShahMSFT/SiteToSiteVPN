<span style="font-size:larger;">Site To Site Instructions</span> 

# Overview
## Topology Diagram – with a Visio diagram
### Topology description
![VPN topology](./images/site2sitetopology.png)
## Prerequisites 
* You already have a storage account
* List of compatible devices – Link to list of compatible devices
* List of subnets- what DC are you planning to connect to – Link to the mapping
* Have access to the network appliance  that is intended to route to Azure
* Have atleast 1 client machine that is connected to the network appliance
## Steps
### Step 1 – Deploy ARM template
* Screenshot of ARM template
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-site-to-site-vpn%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-site-to-site-vpn%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

* Description table of each parameter with example values
* Template Buttons
### Step 2 – Configure Onprem network appliance that performs the IKEV2 (This is top be done by IT Admin/Network Admin)
### Step 3 – Mount to test that connection works
### Step 4 – Persistent mount for reboots
### Conclusion