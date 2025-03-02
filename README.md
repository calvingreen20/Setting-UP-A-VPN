# Vitual Private Network (VPN)
<p align="center">
<img src="https://i.imgur.com/MntON5Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>VPN - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation ousing a VPN.<br />

<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>STEPS INCLUDED</h2>

- STEP 1 - Locate Local IP
- STEP 2 - Setting Up VM Using Azure
- STEP 3 - Locating IP Through VM (USA)
- STEP 4 - Connecting to VPN Through VM
- STEP 5 - Locating IP Through VPN (Romania)

<h2>Installation Steps</h2>

STEP 1 - Locate your own personal IP address by going to "www.whatismyipaddress.com" which will be able to show you your local IP address. We will use this later as well. 

<p>
<img src="https://i.imgur.com/fg0UMSd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next we will set up a virtual machine on Azure. 
  
</p>
<br />

STEP 2 - Go to www.portal.azure.com and find Virtual Machines. Looking at the Virtual Machine set up page. For the Username and Password you can create your custom information, just record it personally.

<p>
<img src="https://i.imgur.com/LJDX7HN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


STEP 3 – Log Into the VM and Find IP Address
<p>
Once inside the VM, open a web browser and navigate to https://whatismyipaddress.com/. View the IP information displayed and record it in Notepad or on a piece of paper for later reference.

  
</p>
<br />
<p>
<img src="https://i.imgur.com/U8oYcH8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/A9ImZA5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  
</p>
<br />

STEP 4 – CONNECTING TO VPN (Free Version)

Using the local computer go to protonvpn.com and create a free account. Once you are logged into your account, copy the URL from the Proton VPN website and then paste the URL to the VM web browser. 

  
</p>
<br />


<p>
<img src="https://i.imgur.com/3F9qrfb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Once you have logged into your Proton VPN account on the VM, you will select “Downloads” and choose to download the “Windows” version. Once the application Proton VPN is installed we will log in using the credentials we used when setting up a free account on Proton VPN. Then connect to the VPN through the installed app.   
  
</p>
<br />

<p>
<img src="https://i.imgur.com/JUHvXj5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

On the left hand side of the VPN you can select a country where you want your VPN to be, the image below shows the VPN being connected to an IP in Romania.  
  
</p>
<br />

<p>
<img src="https://i.imgur.com/YFG04T4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next we will look at the IP again using the VM browser now that we have connected the VPN to Romania. The website www.whatismyipaddress.com shows yet another IP address using the VPN from Romania. This is quite amazing.
  
</p>
<br />


<p>
<img src="https://i.imgur.com/USp1fLc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Looking at this exercise we see that we have utilized 3 different IP addresses just from your local computer to connect to the internet.
Home IP (USA): 98.206.162.176
Virtual Machine IP (USA): 172.210.176.67
Virtual Machin IP VPN (Romania) 185.177.126.152

  
</p>
<br />
If you no longer need the VM, ensure to remove it from the Asure account for unwanted charges.

END OF TUTORIAL
