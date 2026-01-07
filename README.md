# IT Project: How to ping between VMs
<p align="center">
<img//blob:chrome-untrusted://media-app/4a5c8d90-80ee-4f0a-85b7-30df165b0e07 
</p>

<h1>Microsoft Azure - IT Diagnostic Basics: How to Ping between IP addresses (with VM as an example) </h1>
This tutorial shows begginers in the IT world how to ping between virtual machines using "Wireshark" as a medium.<br />

- ###

<h2>Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Windows Powershell (Built-in Admin System)

<h2>Operating Systems Used </h2>

- Windows 11 or 10</b> (21H2)

<h2>Steps</h2>

- Access first Virtual machine (Microsoft Azure) via its public IP address in Remote Desktop
- Access "Wireshark" protocol analyzer within Virtual Machine and access "Ethernet" readings. Type "icmp" in display filter
- Recieve Private IP of second Virtual Machine (Microsoft Azure) and Access Windows Powershell within first Virtual Machine 
- Type command "ping" followed by private IP of second VM in Powershell. Observe ICMP traffic in "Wireshark"

<h2>Tutorial (Detailed)</h2>

<p>
(https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/main/image0%20(21).jpeg?raw=true)
<p>
Access Microsoft Azure and navigate to Virtual Machines. Obtain Public IP address of first virtual machine and access it via remote desktop. Access "Wireshark" application within virtual machine and observe "Ethernet" traffic in app.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In display filter type "icmp" in Ethernet display. Obtain private IP address of second VM and open Windows Powershell inside of first VM.
</p>
<br />

<p>
![image alt][(https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/2cd3d4fe5dc54f04f86aedec5705460850f03a07/image0%20(20).jpeg0)</p>
<p>
  Within Windows Powershell type "ping" followed by private IP of second VM then press "enter". Observe icmp traffic within "Wireshark".
</p>
<br />
