<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This is a beginner friendly tutorial to help you install the open-source help desk ticketing system osTicket. This tutorial is designed to be as simple as possible so that anybody should be able to follow along easily.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop Connection
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>List of Prerequisites</h2>

- Active Microsoft Azure subscription
- Stable internet connection

<h2>Installation Steps</h2>

<p>
1.	Create a resource group. 

Within Microsoft Azure, navigate to “Resource groups” via the search bar and select “Create.” Inside this resource group is where we will store our virtual machine that will run OsTicket.

This resource group can be named anything, however I recommend naming it something that will be easy to recognize if you have multiple resource groups. I will use the name “OsTicket-RG.”

Under resource details, select the region that is relevant to you. I am using “(Asia Pacific) Australia East”.

Select “Review and create” then “Create.”
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
2.	Create a Virtual Machine. 

Within Microsoft Azure, navigate to “virtual machines” via the search bar and select “Create -> Azure virtual machine.”

Under “Subscription -> Resource group” Select the resource group we just created.

Name the virtual machine. Again, the virtual machine can be named anything, however I recommend naming it something that makes it easily identifiable. I will be naming it “OsTicket-VM.”

Select your relevant region.

Under “image” select “Windows 10 Pro, Version 21H2 – x64 Gen2.”

Under “Size” select “Standard_E2s_v3 – 2 vcpus, 16GiB memory.”

Create a username and password. I will be using “Labuser” and “Password1234.”

Under “Licensing” tick the box “I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights.”

Select “Review and create -> create.”
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />


<p>
3.	Connect to the virtual machine via remote desktop connection.

Open remote desktop connection on your PC.

In Microsoft Azure, navigate to the virtual machine we just created and copy the Public IP address.

Paste the public IP address into remote desktop connection, then press “connect.”

Select “Different user” and input the credentials we used when creating the virtual machine being, “Labuser” and “Password1234.”
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
