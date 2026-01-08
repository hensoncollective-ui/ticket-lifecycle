# IT Project: How to ping between VMs

![image alt](https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/29d60353ba800a67a640d2acb4e86c619078aac6/Screenshot%202026-01-08%201.08.23%20AM.png)

<h1>Microsoft Azure - IT Diagnostic Basics: How to Ping between IP addresses (with VM as an example) </h1>
This tutorial shows begginers in the IT world how to ping between virtual machines using "Wireshark" and "Microsoft Azure" as a medium.<br />



<h2>Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Windows Powershell (Built-in Admin System)

<h2>Operating Systems Used </h2>

- Windows 11 or 10</b> (21H2)

<h2>Steps</h2>

1. Access first Virtual machine (Microsoft Azure) via its public IP address in Remote Desktop
2. Access "Wireshark" protocol analyzer within Virtual Machine and access "Ethernet" readings. Type "icmp" in display filter
3. Recieve Private IP of second Virtual Machine (Microsoft Azure) and Access Windows Powershell within first Virtual Machine 
4. Type command "ping" followed by private IP of second VM in Powershell. Observe ICMP traffic in "Wireshark"

<h2>Tutorial (with photos)</h2>

![image alt](https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/84b7732706900e9fa7831df3917bff4f8a71a83f/image0%20(21).jpeg)

STEP 1: Access Microsoft Azure and navigate to Virtual Machines. Obtain Public IP address of first virtual machine(Windows) and access it via remote desktop. Access "Wireshark" application within virtual machine and observe "Ethernet" traffic.
</p>
<br />

![image alt](https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/e8417f6972455560e15d3191f5e5477f88edf743/image2%20(4).jpeg)

STEP 2: In display filter type "icmp" in Ethernet display. Obtain private IP address of second virtual machine(Linux) and open Windows Powershell inside of remote desktop of Windows virtual machine.
</p>
<br />

![image alt](https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/cea7667b4c18d6fd952aaa533b645bc22257bb77/image0%20(20).jpeg)
 
STEP 3: Within Windows Powershell type "ping" followed by private IP of second virtual machine (linux) then press "enter". Observe ICMP traffic within "Wireshark". You should be able to see traffic between your Windows and Linux Virtual machine when done correctly 
</p>
<br />
