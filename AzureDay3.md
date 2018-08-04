## Exercise 1:
* Create a Virtual Network and a subnet in Azure.
* Create a Network Security Group that allows port 22 and port 80 and attach this NSG to the subnet.
* Launch a Ubuntu 16.04 VM with Managed disk inside the VNet created earlier. Create a new NSG that allows port 22 and port 80 and attach it to the VM.
* SSH into the VM and install apache web server in it. Try accessing the web page by navigating your browser to the public IP of the VM.
* Remove the port 80 from the subnet NSG and try accessing the web page. * Add the port 80 again to the subnet NSG.
* Remove the port 80 from the VM NSG and try accessing the web page. Add the port 80 again to the VM NSG.
---

* The page is accessible with the New NSG created on port 80
* When removed the port 80 from Subnet NSG - page not accessible on port 80
* Added back port 80 to the subnet NSG and removed the VM NSG on port 80
* Still able to access the page on port 80
