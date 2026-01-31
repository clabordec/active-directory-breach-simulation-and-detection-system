<h1>Setting up the static IP address for the splunk server</h1>

This project outlines setting up the proper addressing for the splunk server.<br />

<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Ubuntu 24.04 64-bit

<h2>High-Level Deployment and Configuration Steps</h2>

- Log into the server
- Change the address type to static
- Assign a new IP address: `192.168.10.10`
- Assign the DNS server IP address as the following: `8.8.8.8`
- Assign the default gateway to the following: `192.168.10.1`
- Save the changes

<br />

<h1>Deployment and Configuration Steps</h1>

## Setting up the IP addresses
### Log into the splunk server
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/a3af9c59-0bdf-46f6-aec6-8a6462c28396" />
</p>
<br />

### Run the following command to edit the file for the addressing to the server: `sudo vim /etc/netplan/50-cloud-init.yaml`
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/73c2081a-0e92-49be-b5a6-c098d59fd416" />
</p>
<br />

### Once in the file set the IP address as the following: `192.168.10.10/24` the `/24` means a subnet mask of `255.255.255.0`
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/7556ad98-1738-49ba-8a9b-e9651afd9d83" />
</p> 
<br />

### Enter in the IP address for Google in the DNS section
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/54754e43-5d27-4b46-b0a3-a45af0da63a2" />
</p>
<br />

### Enter in the default gateway
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d6f6ad17-a535-4627-bddd-8241dab9b50d" />
</p>
<br />

### Save the changes by holding the "Shift" key then double press the "Z" key, the following confirmation message will appear
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/4a4ff1ce-bd96-4bf8-8945-6169e0cc970c" />
</p>
<br />

### Run the following command to apply the changes: `sudo netplan apply`
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/4880fa72-fdf3-4ab6-8221-573a2a69e661" />
</p>
<br />

### Enter the credentials, then hit "Enter" on the keyboard to log into the VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/1e555a31-7ca4-4916-b2eb-78512cf1a2d0" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b5839423-d2b8-419a-be93-f85df6aa3fa5" />
</p>
<br />

---

<br />

# End of Project













