# IT Project: How to ping between VMs

![image alt](https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/29d60353ba800a67a640d2acb4e86c619078aac6/Screenshot%202026-01-08%201.08.23%20AM.png)

<h1>Microsoft Azure - IT Diagnostic Basics: How to Ping between IP addresses (with VM as an example) </h1>
This tutorial shows begginers in the IT world how to ping between virtual machines using "Wireshark" and "Microsoft Azure" as a medium.<br />



<h2>Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Windows Powershell (Built-in Admin System)
- Wireshark Application

<h2>Operating Systems Used in Example </h2>

- Windows 11 or 10</b> (21H2)
- Windows Virtual Machine Named: WOLFTWO [Public IP: 74.249.132.17] [Private IP: 10.0.0.5]
- Linux Virtual Machine Named: FOXTWO [Public IP:20.221.57.87] [Private IP: 10.0.0.4]
   
<h2>Steps Summarized</h2>

1. Create Two Virtual Machines (One Linux and One Windows) Obtain Public IP and Private IP of both
2. Access Windows Virtual Machine via Remote Desktop and Install "Wireshark" via browser inside of Windows Virtual Machine
3. Obtain Private IP address of Linux Virtual Machine and Access Wireshark within Windows Virtual Machine via Remote Desktop 
4. Within Wireshark Access Ethernet interface and type "icmp" in display filter and Access Windows Powershell inside of Windows Virtual Machine
5. Within Windows Powershell type command "ping" followed by Private IP address of Linux Virtual Machine. Press Enter
6. Observe ICMP traffic within Wireshark between Windows Virtual Machine and Linux Machine

<h2>Tutorial (with photos and video)</h2>

[Creating Virtual Machines in Microsoft Azure]((https://youtu.be/A_GV7h9aEAU?si=1OoYmuaLEXloH32I)

STEP 1: Create Virtual Machines (One Linux and One Windows) within Microsoft Azure. Put them within same network. Obtain Public IP and Private IP of both.
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
