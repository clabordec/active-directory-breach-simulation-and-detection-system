<h1>Installing and setting up Windows 11 Enterprise in VMware Workstation Pro</h1>

This project outlines the installation and set up of Windows 11 Enterprise.<br />

<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 11 Enterprise

<h2>High-Level Deployment and Configuration Steps</h2>

- Install and set up Windows 11 Enterprise onto the VM

<br />

<h1>Deployment and Configuration Steps</h1>

## Installing and setting up Windows 11 Enterprise
### Go to a search browser and type in `download windows 11` and choose the highlighted link
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/34ae62ce-3fde-4c41-8d22-16e475cbe24d" />
</p>
<br />

### Scroll down to `Download Windows 11 Disk Image (ISO) for x64 devices`, select `Windows 11 (multi-edition ISO fro x64 devices)` in the dropdown menu, then click Confirm
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/27c625d6-addd-450a-a60d-7b4eba39cdb7" />
</p>
<br />

### After confirming the ISO image, select the language for the OS, then click Confirm
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/cfd0d851-86a3-4eb4-b222-665009a752ed" />
</p> 
<br />

### After confirming the language for the OS, download the ISO image
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/9c028bba-5c3f-47b6-991e-17aacfde21b6" />
</p>
<br />

### Once the ISO file has downloaded completely, choose a file path to store the file
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/7cea3983-6c3f-43d4-a82d-db5f769a9cf4" />
</p>
<br />

### Create a new VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d47e4623-54c1-4326-91d5-4eae751ab043" />
</p> 
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/95ea9f7a-dbcf-4b91-aa1d-e320cb78a317" />
</p> 
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/f19d3eb7-d723-4926-a7a0-36e78843c533" />
</p> 
<br />

### Choose Microsoft Windows, version Windows 11 x64, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b25e555c-62bc-42a4-936b-ebb06e1e5be1" />
</p>
<br />

### Name the VM, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/32199238-065a-4322-a931-70354c46bcf7" />
</p>
<br />

### Create a password to encrypt the VM, uncheck "Remember the password on this machine in Credential Manager"
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/80340be5-5478-4388-b3f4-ab6dffed503a" />
</p> 
<br />

### Once the following is unchecked, the "Remember Password not select" popup screen will display, select OK, then click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5005d437-6be5-44b3-bacd-5bf366a092fc" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/956a6d4d-c404-4e05-bc89-a5d9001c09fc" />
</p>
<br />

### Set the storage to 85 GB, the virtual disk will be stored into a single file for better performance
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/630f2f2a-a0b2-4438-be34-1a227e5574ab" />
</p> 
<br />

### Review the settings, then click Finished
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/ef65c727-ee91-4dda-9e81-b61e73e12be0" />
</p> 
<br />

### Select the newly created VM and click "Edit virtual machine settings"
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/fc6c4587-b11e-4fad-bd06-cc3e0943aa33" />
</p>
<br />

### Set the Memory to 8 GB
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/6580eee9-ec00-43fd-9c5e-3f2d65dbf0ea" />
</p>
<br />

### Implement the ISO file into the VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/151062e3-aebc-4d69-8fd2-80e2aca4d509" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b964e4d6-1f44-44f9-a1cd-adf6dba81e44" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/a3fbb913-588f-4b64-b539-0ae363974f1c" />
</p>
<br />

### After making the following changes, click OK
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/6ba40673-312f-45f8-9ae8-3156dfe28a8d" />
</p>
<br />

### Power on the VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/603efaa0-4557-4bae-83e3-41925a76b76d" />
</p>
<br />

### English should be the default language as it was set at the beginning of the download, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/c07a73d2-1ed4-4312-b3eb-2f0b22fced09" />
</p>
<br />

### Set the keyboard method to US, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/e2686883-b492-4d12-9fe4-4eb223ffc420" />
</p>
<br />

### Since this is a new installation, choose the "Install Windows 11" radio option
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/372c4261-3119-47c7-9b11-4c521a5176ed" />
</p>
<br />

### Select "I don't have a poduct key"
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/795b003d-78a4-4d65-9510-a771820171ea" />
</p>
<br />

### Select "Windows 11 Pro N", this is to ensure the client machine can conect to the domain
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/7ef3115f-8ebe-4d1f-9e5d-8a9e73c28167" />
</p>
<br />

### Accept the license terms
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/19f905a9-7831-4c32-8581-67ff872cfbd9" />
</p>
<br />

### Review the storage for the VM, once everything is verified, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/7a9ac8bc-970d-442a-8182-b63693b072f2" />
</p>
<br />

### Install the operating system
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/458554d5-e267-46d9-baba-b308823d411b" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d7e3552f-33bd-4770-941f-c57428bba9e2" />
</p>
<br />


## Setting up Windows 11
### Once the installation is complete, select United States as the region for the OS
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/c3b5f1d9-b37a-4f47-bf39-887a072ee2d3" />
</p>
<br />

### Select the keyboard layout as US
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b75d70d7-4f4b-4bcb-a4f1-2c3bd2fd4028" />
</p>
<br />

### Skip the second keyboard layout feature as this is optional
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/7637aa43-8948-4e8b-851b-659468292cd3" />
</p>
<br />

### For this project, select "set up for personal use", then click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/2335d231-64d9-4c23-aa1b-b84840fd4317" />
<br />

### The following operating system has been successfully installed and configured
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/aa03d967-4f3d-4501-91e5-5d21347f0f1a" />
<br />

---

<br />

# End of Project























