
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>

</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)


<h2>Operating Systems Used </h2>

- Windows 11</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>
- Setup and install
- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Remote Desktop Protocol</h2>

<p>


<img width="3825" height="1653" alt="1os" src="https://github.com/user-attachments/assets/846aab68-8990-4fe3-a330-42c709874f14" />

<img width="3771" height="1662" alt="3os" src="https://github.com/user-attachments/assets/b7adb32f-94e0-482a-b151-168250a82b08" />
<p>
In this example, I deployed a Windows virtual machine in Microsoft Azure. Using the Remote Desktop Protocol and the VM's public IP address
 was able to establish remote access.
 
</p>
<br />
<br />

<h2>OsTicket zip file and web server setup</h2>
<img width="3564" height="2016" alt="4os" src="https://github.com/user-attachments/assets/fbfd62dc-909e-462f-9107-dfebabb4b999" />
<img width="3519" height="1983" alt="5os loop back address no web server" src="https://github.com/user-attachments/assets/e4603c7c-18f1-43fc-beeb-b8378766dae2" />

<img width="3477" height="2007" alt="6os install enable IIS in windows" src="https://github.com/user-attachments/assets/e2243d8c-353c-4fed-9c50-1000908d74ee" />
<img width="3453" height="2034" alt="7os verify web servers active" src="https://github.com/user-attachments/assets/68b5f8f7-f8f2-42e2-9339-929c3d116233" />
<p>
In this example, I downloaded the required osTicket zip files. I used a loopback address to verify that there is no web server. Installed and 
 enabled ISS in Windows. Verified web servers were active. 
</p>

<br />
<br />
<h2>Installation of files required for osTicket deployment</h2>
<img width="3240" height="1956" alt="8os install php manager" src="https://github.com/user-attachments/assets/9953ec40-3ad9-4fa7-855a-651946d85662" />
<img width="3444" height="1992" alt="9os install rewrite module" src="https://github.com/user-attachments/assets/e9fd2892-4764-4f74-b180-02c0bcae6424" />

<img width="3405" height="2031" alt="14os open iis as admin" src="https://github.com/user-attachments/assets/b57464cc-199a-4d63-b2e6-49cfee7eda32" />
<img width="3468" height="2025" alt="15os register php " src="https://github.com/user-attachments/assets/1048f5ff-4aa1-41f9-8b0b-e44c227b8a82" />
<p>
In this example, I configured IIS on the Windows Azure VM to support PHP-based applications.
Installed PHP Manager and the IIS URL Rewrite Module, opened IIS Manager with administrative privileges, and registered PHP with IIS in preparation for deploying osTicket.
</p>
<br />
<br />
<h2>Completed osTicket installation</h2>
<img width="3477" height="2037" alt="17os open heidi create session" src="https://github.com/user-attachments/assets/c4313fbc-0fe2-4a67-b43c-aa17b831409a" />
<img width="3339" height="2049" alt="18os osticket install complete" src="https://github.com/user-attachments/assets/42ed0b75-156d-4e47-86f3-1bdb7c54f8fb" />
<p>
In this example, I installed HeidiSQL and configured the database environment required for osTicket using HeidiSQL and established the necessary database connection. 
Completed the osTicket installation on the Windows Server VM hosted in Microsoft Azure.
</p>

</p>



<p>






<h2>Lifecycle Stages</h2>

<p>

<img width="3705" height="2019" alt="intake iosticket" src="https://github.com/user-attachments/assets/5f9c1868-b05b-46c0-bc31-23359423b210" />


</p>
<p>
Intake - A user named
</p>
<br />

<p>
<img width="3543" height="1305" alt="osticket assign" src="https://github.com/user-attachments/assets/f55d5ad6-5cd3-4b0e-a373-688bd917bd0d" />

</p>
<p>Assignment and Communication - John, the help desk agent, reviews the ticket and escalates it to the SysAdmin department for further investigation. 

</p>
<br />

<p>
<img width="3702" height="1947" alt="working issue osticket " src="https://github.com/user-attachments/assets/abc7febb-85ed-4c9b-a902-3c22f194bd55" />


</p>
<p>
 Working the Issue - Jane, a SysAdmin, investigates the issue and attempts to restore service by restarting the online banking system's backend server. The ticket is updated to document the troubleshooting process.
</p>
<img width="3663" height="1986" alt="resolution osticket" src="https://github.com/user-attachments/assets/2f95b04a-7f03-4e89-9f11-238b3c5ad564" />

<p>
Resolution - Jane successfully restarts the backend server and restores the online banking system. After confirming with Karen that the service is working properly, the issue is resolved, and the ticket can be closed.
</p>


<br />
