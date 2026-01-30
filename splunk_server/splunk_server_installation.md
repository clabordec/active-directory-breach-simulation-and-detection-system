<h1>Installing and setting up Splunk Server in VMware Workstation Pro</h1>

This project outlines the installation and set up of Splunk Server to injest data, and run searches throughout the server.<br />

<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Ubuntu 24.04

<h2>High-Level Deployment and Configuration Steps</h2>

- Go to the offical Ubuntu website
- Go to the products tab and select Ubuntu Server
- Download the latest Ubuntu Server, in this case Ubuntu 24.04.3
- Create a VM
- Install the downloaded Ubuntu Server onto the VM
- Create the following credentials to log into the server:
    - Username: clabordec
    - Password: jnvevfjekvejvn8328282932yvubib3f2
- Run the following command to update and upgrade all of the repositories in the server:
    - sudo apt-get update && sudo apt-get upgrade -y

<br />

<h1>Deployment and Configuration Steps</h1>

## Installing and Setting up the Splunk Server
### Go to `Ubuntu.com`
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/69b73ed4-9f15-47c0-878e-0f3baa3918d9" />
</p>
<br />

### Go to the Products drop down menu, then click on Ubuntu Server
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/279ea809-06f4-4093-ac1d-ec873d157f82" />
</p>
<br />

### Click on "Download Ubuntu Server"
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/76f77297-c2ed-4024-9afa-964ecf2e3609" />
</p> 
<br />

### Download the latest version of Ubuntu
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/3451f249-b4e4-48f1-af3b-92807cc7f5cf" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/4dbfeab2-6751-46d3-9a59-e52602e747c7" />
</p>
<br />

### Move the file to a different location
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/47c03a1e-3cec-4e6a-892c-80dcf6000578" />
</p>
<br />

### Create a new VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/69889c42-0a43-4f20-907b-738c3351ef41" />
</p>
<br />

### To create the VM faster and easier, choose the "Typical" radio option
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/3cc8d027-ffeb-4ad0-9c45-46a19b85bffb" />
</p>
<br />

### The OS will be installed after the VM is created, this is to aviod any issues with installing the OS, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/587c3c7f-ed8b-49c5-8f98-3acf24f930bf" />
</p>
<br />

### The Guest OS will be Linux and the version will be Ubuntu 64-bit, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/dd89692b-8966-49e3-a8aa-c048ad0bab73" />
</p>
<br />

### Name the following VM `Splunk`, then click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b7131f0d-2c95-43d7-aa69-0b4557e476a9" />
</p>
<br />

### Give the following VM 125 GB and store the virtual disk into one single file for better performance. click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/3a3dc709-737d-4faf-9d68-e373b9740736" />
</p>
<br />

### Click Finish
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/a683ff3a-b1a0-4448-8f60-40fdfe67ff6c" />
</p>
<br />

### Edit the virtual machine settings
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/1fa512c6-2974-481d-a2b9-c71bfcd0b91f" />
</p>
<br />

### Set the RAM for the VM to 10 GB 
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b8617a64-8bb6-4476-970a-acb2145bb7c1" />
</p>
<br />

### Insert the ISO file into the VM 
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/480f4bca-b767-413f-b9fc-e3c8ba90d747" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/67dd060f-28b4-4a76-b48e-38c6d3afcdd7" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/9d1548ab-a920-4004-acca-03cb96ed746c" />
</p>
<br />

### Click OK to save the changes
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/16a92662-fe73-4d95-b380-de0c95e14411" />
</p>
<br />

## Setting up the Splunk Server
### Power on the VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d64b43f4-ccce-43d6-a24a-b5a8cd78b1a1" />
</p>
<br />

### Install the Ubuntu Server
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/e5b679fe-e368-488a-a64f-80f7991a0c2a" />
</p>
<br />

### Select "English" as the language, press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5346ae1f-6b79-4835-bac0-ccd9081a0c0a" />
</p>
<br />

### Set the layout and variant to "English", press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/09609c36-332a-4f13-8931-5e55bd69d11a" />
</p>
<br />

### Select the full installation of Ubuntu server, press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b334ffa4-aa5d-4dcd-a569-c503ffe2eb91" />
</p>
<br />

### Contiune without network, press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/c2fc63b4-0dd7-4e55-babc-0192a9299437" />
</p>
<br />

### A proxy address is not needed for this VM, press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b23ec774-0bca-48f2-b865-cd7e84101e34" />
</p>
<br />

### Press done
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/6c826303-2ed0-4a11-9b28-93adbd4ef7dd" />
</p>
<br />

### Use the down arrow key to hover over the Done button, press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d96d6173-9bd0-4796-bc90-06d7d96a3bcb" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/aa28a195-6134-42da-9429-c98fea4c3bdb" />
</p>
<br />

### Review the file system summary, press Enter if changes are correct
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/8ecad618-188c-4973-910a-c4f5c03f110f" />
</p>
<br />

### Arrow down to the Contiune button and press Enter 
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/c630079e-e12f-4d64-9287-7abbeb55347a" />
</p>
<br />

### Create the credentials for the splunk server, arrown down to the Done button then press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/24ddae53-d1c9-499f-99f0-c182ba86448e" />
</p>
<br />

### Ubuntu Pro is not needed for this VM, press Enter to continue
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/18a8987c-3418-4c85-95a7-a7d67dd7a43f" />
</p>
<br />

### Arrow down, then press Done to continue
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/dd58046a-773e-41f2-8317-3abf71774d58" />
</p>
<br />

### Arrow down, then press Done to continue
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/2edd53b7-db02-4544-81cd-5a0aa5ab365b" />
</p>
<br />

### The OS is now installing
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/9752d909-9b90-41d1-a7f8-107bbd5b422e" />
</p>
<br />

### Once the OS has finished installing, arrow down to the reboot the server, then press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/52750707-55a6-4e0b-84cf-b5c6225a0a35" />
</p>
<br />

### A failed message for unmountiung the CDROM will appear, go ahead and press enter to continue to the login screen
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/22862889-02b9-40e1-8c16-d67e17f58465" />
</p>
<br />

### Enter in the credentials
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/9752d909-9b90-41d1-a7f8-107bbd5b422e" />
</p>
<br />

### Update and upgrade all of the repositories to their latest version
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/9752d909-9b90-41d1-a7f8-107bbd5b422e" />
</p>
<br />

### Once the following screen is displayed, press Enter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/9752d909-9b90-41d1-a7f8-107bbd5b422e" />
</p>
<br />

---


# End of Project



