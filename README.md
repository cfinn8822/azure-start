# azure-start
<p align="center">
<img src="https://i.imgur.com/1DDZ4Ui.png" height="50%" width="50%" alt="Microsoft Azure Logo"/>
</p>
<p align="justify">
<h1>Microsoft Azure</h1>

This demonstration will show you how to get started and implement an Azure Account in order to do these labs in the future. We will learn how get free Azure account, Create a Resource Group, Storage account, and a Virtual Machine, as well as how to connect to it.

 
<h2>Requirements</h2>

 - Computer w/ Internet Connection
 - Credit Card (Required for free Azure credits)
 - Remote Desktop Connection (Windows) / Microsoft Remote Desktop (Mac)

<h2>Step Process</h2>

1) Create a FREE* Azure Account</h3>

Go to [https://azure.microsoft.com/en-us/free/](https://azure.microsoft.com/en-us/free/)
- Click "Start Free".
- Follow the prompt to create an account.
  - You WILL need to put in your credit card information to receive the free $200 worth of Azure credits!
    <div> It will not charge you, <b>but only lasts for 30 days!</b>
- Once completed, click on <a href="https://portal.azure.com/">Go to the Azure Portal (portal.azure.com)</a>.

<img src="https://i.imgur.com/FklBT6F.jpg" height="50%" width="50%" alt="Azure Free Account"/>

2) Create a Resource Group

 - In the Search Box at the top header, type and select "Resource groups"
 - If "Resource groups" is already listed on the front page, then you can simply click on it, rather than manually searching.

<img src="https://i.imgur.com/gza489d.jpg" height="50%" width="50%" alt="Azure Step 2-1"/>

- Click "Create" on the top left menu, OR simply press "Create resource group" in the center box (assuming you don't have one yet).

<img src="https://i.imgur.com/5Jo1cEg.jpg" height="50%" width="50%" alt="Azure Step 2-2"/>

 - Name your "Resource group" to whatever you want for this example i am using (RG-01).
 - Change the "Region" to a location that is closest to you for this example uses ((US) West US 3).
 - Skip everything else and click "Review + Create" on the lower left, which you should have "Validation passed" on the next page.
 - Click "Create"

<img src="https://i.imgur.com/eXw16Ga.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/JiGaNQS.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

3) Create a Storage Account

 - In the Search Box at the top header, type and select "Storage accounts".
 - If "Storage accounts" is already listed on the front page, then you can simply click on it, rather than manually searching.

<img src="https://i.imgur.com/6Z51Uld.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

 - Click on "Create Storage account".

<img src="https://i.imgur.com/pY1QkBp.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

 - Use the same resource group that was just created for this example use (RG-01).
 - Create a unique name for the storage account that hasn't already been taken for this example use (labsaname).
 - Choose the same region for this example use ((US) West US 3).
 - Skip everything else and click "Review", then "Create".

<img src="https://i.imgur.com/uhzsXAJ.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/6Yoibis.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

4) Creating a Virtual Machine

 - In the Search Box at the top header, type and select "Virtual machines"
 - If "Virtual machines" is already listed on the front page, then you can simply click on it, rather than manually searching.

<img src="https://i.imgur.com/vv4dvFh.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

 - Click "Create", then select "Azure Virtual Machine"

<img src="https://i.imgur.com/lmEIHGq.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

  - Use the same resource group for this example use (RG-01).
  - Name your virtual machine however you want for this example use (VM1).
  - Use the same region for this example use ((US) West US 3).
  - Choose your "Image" for this example use (Windows 10 Pro, version 22H2 - x64 Gen2).
  - Choose a "Size" for this example use (Standard_E2s_v3 - 2 vcpus, 16 GiB memory).
  - Create any username and password of your choice for this example use the username (labuser).
  - Check the "Licensing" checkbox.
  - Click "Review + create".
   
    - Once validation passed, click "Create".

<img src="https://i.imgur.com/6kpfbT9.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/oI9c0ZD.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/thpxToh.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

5) Connect to the Virtual Machine via Remote Desktop

 - Go to your Virtual Machine that was just created and COPY the public IP address (located on the right side).

<img src="https://i.imgur.com/gOV25tN.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

 - Press the Windows Key or Start Button, type and select "Remote Desktop Connection".
 - Input the virtual machine's Public IP Address and click Connect.
 - Enter the username and password from Step 4 above, then click OK.

<img src="https://i.imgur.com/uZV87aH.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

 - A prompt will appear about the identity cannot be verified; just press "YES".

<img src="https://i.imgur.com/vSfMzLC.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

 - Toggle any settings you want, then click "Accept".( for the purpose of this i am toggling all off)

<img src="https://i.imgur.com/0lvbSip.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

- CONGRATULATIONS! You have created your first virtual machine within Azure!

<img src="https://i.imgur.com/h3w6mmC.png.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

!!!Complete!!!

