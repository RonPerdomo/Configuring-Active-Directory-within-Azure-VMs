<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
This showcase is about deploying Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1-Setup Resources in Azure (Two Virtual Machines). One will operate as a Server with Active Directory installed. The other will be a Client computer connected to the Server and simulating different users with different credentials logging in.
- Step 2-Install Active Directory and create Admin and Normal user account.
- Step 3-Connect Client computer to the domain of the Server computer.
- Step 4-Use Powershell (copy and paste a script) to create a large number of users to simulate a large amount of users within an organization. Any one of those users can now use Client computer and log in with their credentials.

<h2>Screenshots Showcasing Results</h2>

<p> 
<h5>Two virtual Machines successfully created.</h5>
<img src="https://github.com/user-attachments/assets/59ba7b84-5ecb-4367-8264-e57382553ae3" height="80%" width="80%">
</p>
<p>
  <h5>Ensure Connectivity between the client and Domain Controller.</h5>
  <img src="https://github.com/user-attachments/assets/9cf470c0-f494-459c-b297-bbc4643fd341" height="65%" width="65%">
  <img src="https://github.com/user-attachments/assets/785130cd-7ffe-467d-96b8-f7a3865590b9" height="65%" width="65%">
</p>
<br />

<p>
  <h5>Installing Active Directory and creating Admin account</h5>
  <img src="https://github.com/user-attachments/assets/654cab4a-60cb-4a20-8462-94c88413460b" height="65%" width="65%"/>
  <img src="https://github.com/user-attachments/assets/acd68ea0-020f-49ee-b1c2-3f5efce0f1da" height="65%" width="65%">
</p>
<p>
  <h5>Joining Client 1 to Domain</h5>  
<img src="https://github.com/user-attachments/assets/5e5f6529-3f99-4ed7-8095-bc72f6c457b9" height="65%" width="65%">
</p>
<p>
  <h5>Used Powershell to create many users and logged into Client 1 computer with a random user that was created</h5>
<img src="https://github.com/user-attachments/assets/5ee9f1e1-a9b4-4b84-bc76-de1bb10b4d84" height="65%" width="65%"/>
<img src="https://github.com/user-attachments/assets/bf34b5ae-6ab2-41dd-a6ce-f93f79956bd7" height="65%" width="65%">
</p>
