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

### Create a new VM
<p>
<img src="https://github.com/user-attachments/assets/5e92e0dc-b8c2-49dc-91d0-31c3af26a5c8" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Name the following VM
<p>
<img src="https://github.com/user-attachments/assets/956fcc61-3d51-4ce1-98a6-2835a1b4593d" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Import the Windwos Server 2022 ISO file, skip the unattended installation, then click Next
<p>
<img src="https://github.com/user-attachments/assets/acd4c4ec-5d5e-4840-bf01-6758d96a2d09" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/22aa5114-5d0c-4802-ba6b-5767745c53f6" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/c2e0556a-c9b8-4478-bd43-f95d7667ff66" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Set the RAM to 12 GB and 2 CPU cores, click Next
<p>
<img src="https://github.com/user-attachments/assets/dd5bec97-596c-44f5-ad3c-b7f435bfdde0" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Set the storage space to be 120 GB, click Next
<p>
<img src="https://github.com/user-attachments/assets/48093f4a-edc1-4e18-8c12-6ff4aad1ea0d" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Review the changes, then click Finish
<p>
<img src="https://github.com/user-attachments/assets/cc77eeb9-1c64-4ab8-81b3-0bbfeda9e1de" width="550" alt="Disk Sanitization Steps"/>
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

### Press OK to exit and save the changes
<p>
<img src="https://github.com/user-attachments/assets/04262cfe-a604-468b-bf20-41ad3002dae1" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Power up the VM
<p>
<img src="https://github.com/user-attachments/assets/ea01a7d2-9472-409a-9cca-153c5bddd68f" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Before getting the Windows Boot Manager screen, click inside of the VM and rapidly press the Enter key, this will direct you to the Windows Boot Manager screen, once this screen appear press Enter to continue the Windows setup
<p>
<img src="https://github.com/user-attachments/assets/04aec41d-5641-42c5-a670-af2abfc84d69" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Leave the default language setup, then click Next
<p>
<img src="https://github.com/user-attachments/assets/147bc60d-2086-4156-a32a-1ac2e24af867" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Install the Windows Server 2022 operating system
<p>
<img src="https://github.com/user-attachments/assets/a34d543f-3502-4015-bcd5-d98833cc2682" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

<br>

## Setting up Windows Server 2022
### Select the second option to get the GUI version of Windows Server, click Next
<p>
<img src="https://github.com/user-attachments/assets/0b3736c5-1e6b-4771-898a-afae88c85476" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click on the checkbox to agree to the license terms, then click Next
<p>
<img src="https://github.com/user-attachments/assets/b0defa29-630b-4078-a6ae-ad89a667cfec" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Since this is a brand new OS, choose the custom install option, to install the operating system from scratch, click Next
<p>
<img src="https://github.com/user-attachments/assets/733ce0f4-5473-4079-8284-2702cf09ff86" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Confirm that the drive is set to the amount of GB that was assigned at the creation of the VM, this is where the OS will be installed, click Next once the information has been confirmed
<p>
<img src="https://github.com/user-attachments/assets/9db71b6b-8639-4be1-9956-647b9dd18528" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### The operating system is now in the process of installing, based on computer specs, this can take from 5-30 minutes
<p>
<img src="https://github.com/user-attachments/assets/51104caa-02f3-4c25-896c-3323b04019ab" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### After the installion has been completed, assign the password for the Windows Server OS, then click Finish
<p>
<img src="https://github.com/user-attachments/assets/59baaa82-08cf-4efc-a079-77385e81dce0" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click on hold keys CTRL + ALT + INSERT to enter the login screen for the VM
<p>
<img src="https://github.com/user-attachments/assets/09936bc1-5f0f-40c2-9f84-4b6d477f6dc9" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/e2bb39a8-e7e6-4837-8a5b-c62811030aab" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Enter the password
<p>
<img src="https://github.com/user-attachments/assets/d8d647df-dcf0-4c8f-b492-fe977045c27f" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Server Manager will automatically display once logged in, indicating a successful installation for Windows Server 2022
<p>
<img src="https://github.com/user-attachments/assets/ba24e222-4480-4ffe-8c02-907f44aa0beb" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

---

<br />


# End of Project
