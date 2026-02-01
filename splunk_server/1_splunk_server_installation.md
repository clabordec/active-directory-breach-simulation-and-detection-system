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
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/6da66e3c-e945-4035-8f2d-550bb1ee901a" />
</p>
<br />

### Name the VM as the following
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/1c3e8e06-ef59-4b00-812a-8b4bb892fed5" />
</p>
<br />

### Import the ISO file, skip the unattached installation for an easier installation process, then click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/875a7f7a-d376-4f52-a162-a6b88da3f51e" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/5001f68f-b4fa-4efa-83ff-df79aa04c24e" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/c8d86458-6c75-40a0-a54c-b1f759619fcc" />
</p>
<br />

### Set the VM to have 10 GB of memory and 2 CPU cores, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/117efa40-b963-4b7a-bc0f-6d26d1ef9c4e" />
</p>
<br />

### Set the storage space to 125 GB, click Next
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/046d2dc4-f78a-4bd3-95af-e1c82ca2a374" />
</p>
<br />

### Review the VM summary, then click Finish
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/0954dc08-e879-4031-aedd-b41d6df4f437" />
</p>
<br />


## Setting up the Splunk Server
### Power on the VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/560dc6ef-f3e3-46b9-b49d-68df063f4b18" />
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
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/8f4f0feb-e18a-4201-bfe2-9eb3a1fc34ac" />
</p>
<br />

### Update and upgrade all of the repositories to their latest version
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/40abe281-c583-470c-aefb-540d9ca74053" />
</p>
<br />


---


# End of Project





