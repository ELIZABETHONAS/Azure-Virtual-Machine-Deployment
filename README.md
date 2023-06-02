# Azure-Virtual-Machine-Deployment
<p align="center">
<img src="https://i.imgur.com/zIJA8Ps.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>Virtual Machine - Creation</h1>
This project outlines the deployment of a Virtual Machine on two operating systems.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Resource Group

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Linux Ubutu

<h2>List of Prerequisites</h2>

-  An active Azure subscrption
-  A registered Resource Group (check previous project)

<h2>Installation Steps</h2>
<p>
<img src="https://imgur.com/aF8Likx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Create a Resource Group, check previous project https://github.com/ELIZABETHONAS/AZURE-RESOURCE-GROUP-AND-VIRTUAL-STORAGE-ACCOUNT  
</p>
<br />

<p>
<img src="https://imgur.com/JyE9Yt8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - Our Resource Group for this project is called "RGLAB" as illustrated above
 
<img src="https://imgur.com/x4jqk2S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
-  Using the search bar search for Virtual Machine
-  Create a Windows 10 Virtual Machine (VM)
   -  While creating the VM, name your Virtual Machine, for this project its VMONE
   -  While creating the VM, select the previously created Resource Group (RGLAB)
   -  While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet
   -  While creating the VM, select a region of choice
 
</p>
<br />   

<p>
<img src="https://imgur.com/CNnMQPF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 -  Deployment may take a few mintues.
 
<img src="https://imgur.com/h7FPKK0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

-  Confirm the successful creation of the first Virtual Machine, named "VMONE"
</p>
<br />

<p>
<img src="https://imgur.com/FdqWddb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
-  To create the second Virtual Machine, which is for Linux (Ubuntu)
   -  Identical steps taken for the VMONE can be adopted as well
   -  While creating the second VM, select and pay attention to the following steps:
   -  Select the previously created Resource Group and Vnet
   -  Name the second Virtual Machine as VMTWO
   -  Select the same region
   -  Select Ubuntu OS size and space

</p>
<br />   

<p>
<img src="https://imgur.com/mkLLda5.png" height="80%" width="80%" alt="Disk Sanitization Steps" 
</p>
<p>
 
-  Deployment may take a few mintues
 
-  Confirm the creation of the second Virtual Machine called "VMTWO" 
 
</p>
<br />

<p>
<img src="https://imgur.com/qg4ifBb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 -  To confirm the Network Uniformity on both VMs
 -  Type " Network Watcher" on the search bar
 -  Select Topology 
 -  Notice the topology and the resource created in the process of our VM creation i.e vnet, nsg (fire wall)
 -  It looks good.
 
<img src="https://imgur.com/A1ObN9y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


-  Congratulations you have successfully created two Virtual Machines on Windows and Linux
 
</p>
<br />

