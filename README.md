<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Folders With Read, Read-Write, and No Access
- Create A Security Group and Accounting Folder
- Test Connectivity to Folders
- Retest Connectivity to Folders After Controls Were Updated on the DC-1
<h2>Actions and Observations</h2>

<p>
  <img width="1440" alt="Screenshot 2023-11-29 at 1 20 49 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/404b3b37-43f4-479b-a67c-10f7cc007deb">



<img width="1440" alt="Screenshot 2023-11-29 at 1 20 56 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/76755f43-0023-4cd4-8837-3ae1acad118a">

<img width="1440" alt="Screenshot 2023-11-29 at 1 19 56 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/957b0e65-fcb0-42ed-afe8-0125a416f938">

<img width="1440" alt="Screenshot 2023-11-29 at 1 19 49 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/0220bfd3-2ed7-455b-ad4f-96eee28d90f5">
  
  </p>
<p>
In this lab, I first created files to test connectivity. I created a file with read access, write access, and no access. In a later portion of the lab, I created an Accounting folder. 
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2023-11-29 at 1 33 07 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/19dc854d-45c9-463a-86f5-8a99ccd57171">
<img width="1440" alt="Screenshot 2023-11-29 at 1 33 11 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/822ff45b-308c-443c-9abb-6f3ab73c91b2">

<img width="1440" alt="Screenshot 2023-11-29 at 1 33 30 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/4c6ecef1-05e0-4355-9aac-22dee19283dc">
<img width="1440" alt="Screenshot 2023-11-29 at 1 36 09 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/d962f0ed-6ff1-4a14-80e1-8fc4180d8ee8">

 <img width="1440" alt="Screenshot 2023-11-29 at 1 40 39 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/5bac8b4e-d8d5-4d13-aba3-e88862e4a0d8">
 <img width="1440" alt="Screenshot 2023-11-29 at 1 40 42 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/6074b0ac-c4d2-495a-92ac-756fc4abc438">

  </p>
<p>
I created a Security Group for the Accounting Department. Then I created a folder for the accounting department and added the security group to the accounting folder. 

  
</p>
<br />

<p>
<img width="1440" alt="Screenshot 2023-11-29 at 1 22 34 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/9db28dfc-d913-4f40-b449-9048f0fe15d6">

<img width="1440" alt="Screenshot 2023-11-29 at 1 22 46 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/591149b2-66da-44bd-8ded-bfbd285df8f9">

<img width="1440" alt="Screenshot 2023-11-29 at 1 22 59 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/c725b7b5-1caf-46e6-8eec-3beb706bc187">

<img width="1440" alt="Screenshot 2023-11-29 at 1 24 08 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/573f75ad-ce7e-4f1d-836a-be685aa25759">
<img width="1440" alt="Screenshot 2023-11-29 at 1 26 24 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/dc388475-7601-455f-9854-8cd997f2ec83">

<img width="1440" alt="Screenshot 2023-11-29 at 1 26 42 AM" src="https://github.com/Beth-Agbassekou/azure-network-protocols/assets/148320585/d32e4c3c-46d8-4d23-9564-b7a7eae3c676">
  
  </p>
<p>
There were two types of connectivity that I tested. I tested the first three folders in test 1 and test 2 I checked the connectivity to the accounting folder. After giving access to a user I logged in and checked the connectivity to the folder. I created some files and attempted to create files add files and test the connectivity of these folders. Some failed and I had to restart the client machine and I was able to access the Accounting folder. 


  
</p>
<br /># azure-network-protocols
