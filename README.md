<h1>SIEM Lab</h1>

<h2>Description</h2>
In this lab, I create a simple home Security Operations Center in Azure. I set up a Windows virtual machine as a honeypot, expose it to the public internet to attract genuine attack traffic, and then send the resulting logs to a central Log Analytics Workspace. These logs are then integrated with Microsoft Sentinel for analysis, allowing me to query and visualize attack data, as well as create a real-time attack map that displays attacker positions. The project is designed for practical experience in log analysis, threat detection, and SOC operations in a real-world cloud environment.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Microsoft Azure</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Walk-through:</h2>

<p align="center">
Booting up with Server 2019: <br/>

Setting up the first VirtualBox with Server 19. This will act as the Domain Controller.

![Image](https://github.com/user-attachments/assets/bfc1e23f-4edd-48ec-a3fd-5a716c1db07a)
