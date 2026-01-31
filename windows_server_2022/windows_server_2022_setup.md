<h1>Installing and setting up Windows Server 2022 in VMware Workstation Pro</h1>
This project outlines the installation and set up of Windows Server 2012 along with the installation and management of Active Directory within VMware Workstation Pro 17.<br />


<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows Server 2022

<h2>High-Level Deployment and Configuration Steps</h2>

- Download Windows Server 2022
- Create a new VM
- Set the OS to Windows and the Version Server 2022
- Name the following VM: `CLABORDECDC`
- Import the Windows Server 2022 file into the VM
- Install Windows Server 2022

<br>
<br>


<h1>Deployment and Configuration Steps</h1>

## Installing and setting up Windows Server 2022
### Go to a search browser and type on the following `windows server 2022 iso download` choose the highlighed link
<p>
<img src="https://github.com/user-attachments/assets/8b4ec958-9a33-4684-ad29-01ca6860cf1c" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click on the `64-bit edition` download, based on your network speed, this may take between 5-30 minutes
<p>
<img src="https://github.com/user-attachments/assets/e02ed9d9-ed8c-4074-9173-873bc0eab825" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Save the ISO in any location, in this case I have saved the ISO to the following location, I've also renamed the ISO image:
<p>
<img src="https://github.com/user-attachments/assets/1626d3d0-a726-4de8-80e9-73476cde68dd" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Open VMware Workstation Pro and create a new VM
<p>
<img src="https://github.com/user-attachments/assets/cc525cd1-4138-4a4b-84db-7d0f720788ba" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/b99d9086-cb9f-47e6-b9d6-6677b41b1386" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### To aviod any issue with the VM starting up successfully, choose `I will install the operating system later.` radio option, then click next
<p>
<img src="https://github.com/user-attachments/assets/600e745f-0ce4-4dbc-abf7-bf99e481a92d" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Select `Microsoft Windows` as the OS, and `Windows Server 2022` as the version, click Next
<p>
<img src="https://github.com/user-attachments/assets/defaccac-cc49-4621-996c-f5e958ee37c9" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Nme the VM as the following, click Next
<p>
<img src="https://github.com/user-attachments/assets/defea001-4118-4936-ab6f-56af1d479e80" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Since this server will hold Active Directory and other important resources, give the VM 115 GB of storage, this virtual disk will be stored into a single file for better performance when running the VM, click Next
<p>
<img src="https://github.com/user-attachments/assets/96982e9e-9308-4573-a041-f343f884bc4e" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Review the specs of the VM, then click finish
<p>
<img src="https://github.com/user-attachments/assets/cec2c399-fc08-43cc-906c-9a30b716928e" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Edit the VM settings
<p>
<img src="https://github.com/user-attachments/assets/614ae9fa-3efe-496d-95b4-21c400a111c3" width="550" height="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Set the Memory to 10 GB
<p>
<img src="https://github.com/user-attachments/assets/b85d4ac8-9055-4795-8687-71184bbaff06" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Import the Windows Server 2022 ISO file 
<p>
<img src="https://github.com/user-attachments/assets/0e3888f2-cd65-4ea5-bce1-25984e3fc528" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/a688c8cc-9193-4427-a917-4354a7fd29d4" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/8fa21a74-3972-4aee-99fa-479fdc9ee515" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Once the VM is powered on, click within the VM and rapidly press space bar or any key of your choosing until you see the following, then hit enter
<p>
<img src="https://github.com/user-attachments/assets/673de096-0f20-48aa-9ece-1defee174ec9" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/5a2f044b-79d7-4c62-a745-a7ad0d71afce" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Install now
<p>
<img src="https://github.com/user-attachments/assets/e437c752-91c3-4064-8cc8-2583498a19c8" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Choose the `Windows Server 2022 Standard Evaluation(Desktop Experience)` to have a Graphical User Interface(GUI) for the VM, then click Next
<p>
<img src="https://github.com/user-attachments/assets/f0a85cc3-4c76-47a8-8e67-7bd8b1502449" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Go through the Mircosoft Software License Terms, click the checkbox to agree then click Next
<p>
<img src="https://github.com/user-attachments/assets/29749b67-470e-4e6b-a355-8703bf4f7a69" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Since this is a brand new VM with a brand new OS, choose the custom option to create a new OS
<p>
<img src="https://github.com/user-attachments/assets/150f1f9f-6ed7-467b-adf2-4589a65d9e66" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Ensure that the storage is correct, then click Next
<p>
<img src="https://github.com/user-attachments/assets/2386fa37-4f0d-4dec-9da3-5e05c38b45ba" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Depending on your network speed, the process of installing the OS can take between 5-30 minutes
<p>
<img src="https://github.com/user-attachments/assets/6ff01d6e-89c6-46b6-9d01-6a1e63f24900" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Once the OS has been installed, input a password, be sure to remember the password, or you will need to re-install the OS if you forget it, then click Finish
<p>
<img src="https://github.com/user-attachments/assets/1c4d5835-9756-47b6-b92a-e715181386a6" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### After inputting the new password, press Ctrl+Alt+Insert to unlock the Windows Start Screen within the VM
<p>
<img src="https://github.com/user-attachments/assets/f8a8e5ad-710b-47b6-978f-fe4a9e39d4bb" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Enter the new password
<p>
<img src="https://github.com/user-attachments/assets/ed45f5f3-75f0-45de-b840-9ece2dfd4d4a" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Once logged in, Server Manager will be the first application that will open
<p>
<img src="https://github.com/user-attachments/assets/8c57e57d-62a4-419d-a2b7-97162208121a" width="550" alt="Disk Sanitization Steps"/>
</p>

---

<br />


# End of Project
