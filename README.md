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

[Creating Virtual Machines in Microsoft Azure](https://youtu.be/A_GV7h9aEAU?si=1OoYmuaLEXloH32I)

STEP 1: Create Virtual Machines (One Linux and One Windows) within Microsoft Azure. Put them within same network and choose proper "Image" choosing either a Windows model or Ubuntu (for Linux). Set Password access(Optional for security purposes). Obtain Public IP and Private IP of both. (LINK ABOVE)
</p>
<br />

[Accessing Windows Virtual Machine via Remote Desktop](https://youtu.be/t8guR79pr-s?si=J_re5wnz8rZt3p-N)

STEP 2: Access Windows Virtual Machine (WOLFTWO) via Remote Desktop using public IP address and insert login info with password guidelines setup in Virtual machine creation process. (LINK ABOVE)
</p>
<br />

![image alt](https://github.com/hensoncollective-ui/IT-Project-How-to-ping-between-Virtual-Machine/blob/30e7e568ea156b0caa3c7a36afc6d9dc824f7038/image0%20(22).jpeg) 

STEP 3: After accessing Windows Virtual Machine (WOLFTWO), open browser and navigate to (https://www.wireshark.org) and install Wireshark application within remote desktop. Open Wireshark after installation. 

[Accessing and Observing Ethernet Traffic within Wireshark](https://youtu.be/74HQrzIbYUs?si=ehI27kLov4AFt0Jg)

STEP 4: Within Wireshark access Ethernet interface to view traffic on network. In the display filter type "icmp" and press enter, as we will use this filter to observe the ping results between Windows Virtual Machine (WOLFTWO) and Linux Virtual Machine's (FOXTWO) later using the latters Private IP address within Windows Powershell. (LINK ABOVE)
<br />
