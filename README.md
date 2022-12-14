<p align="center">
<img src="https://i.imgur.com/StEBVLU.png" alt="Traffic Examination"/>
</p>

<h1>Linux Command Analyzation using VPN</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Mircosft Remote Desktop
- Proton Virtual Private Network
- Powershell
- Windows Command Prompt

<h2>Operating Systems Used </h2>

- Ubuntu Server 20.04
- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Remote Desktop into VM
- Download and Install Proton VPN
- Ping Linux VM using Powershell
- Connect to Linux VM via SSH 
- Using Command Prompt type mulitple Linux commands

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/x6DvRKY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the host VM lookup the IP address of the host VM on whatismyipaddress.com.
</p>
<br />

<p>
<img src="https://i.imgur.com/zkFZ7Ak.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, download and install Proton VPN and connect to a VPN server out in another region/country.
</p>
<br />

<p>
<img src="https://i.imgur.com/c1OIKj5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After connecting to a VPN server out in another country lookup the IP address of the VM once again, however this time the IP should be different now that you've connected to the VPN.
</p>
<br />
