<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/@MarkwheelReach)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (VM)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- osTicket Installation files
- Heidi SQL

<h2>Installation Steps</h2>


<p>
A screenshot showing how to create a virtual machine in Microsoft Azure can be found below.
We are setting up and labeling our virtual machine as osticket-vm in this example. This will act as the cornerstone for effectively hosting and managing osTicket.
</p>
<p>
<img src="https://i.imgur.com/w7P1BjA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
We utilize our PC's Remote Desktop Connection program to access the virtual machine once it has been configured in Microsoft Azure. 
We download the osTicket installation files straight to the virtual machine after logging in. 
By doing this, the virtual machine is ready for the installation procedure and all required files are there.
</p>
<p>
<img src="https://i.imgur.com/IDcF14c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
The Common Gateway Interface (CGI) and Internet Information Services (IIS) must then be enabled.
To accomplish this, launch your computer's Control Panel. Choose Turn Windows Features On or Off from the left-hand panel after selecting Uninstall or Change a Program. 
Find and choose the Internet Information Services (IIS) box in the Windows Features menu. Check the option for CGI after expanding World Wide Web Services and then Application Development Features. 
To save your modifications, click OK. Windows will then install the required updates.

</p>
<p>
<img src="https://i.imgur.com/txunFmu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Next step is install all the exe files inside the osTicket-Installation-Files folder, 
to Follow the More Detailed installation please watch the Video Demonstration link Above this guide..
Below Screenshot is where we are done installing osTicket. 
</p>
<p>
<img src="https://i.imgur.com/flXTThg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

