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
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/7f59aa6b-8ebf-4f9b-9a4b-3615266ffb1d" />
</p> 
<br />

### Enter in the IP address for Google in the DNS section
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/79eb201f-8e73-44b2-b37c-2a705048a0b4" />
</p>
<br />

### Enter in the default gateway
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/6d49c78d-e06c-459b-871b-3f3981dd69ca" />
</p>
<br />

### Save the changes by holding the "Shift" key then double press the "Z" key, the following confirmation message will appear
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/01c09786-f213-47fb-b269-161ae1ef798a" />
</p>
<br />

### Run the following command to apply the changes: `sudo netplan apply`
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/4880fa72-fdf3-4ab6-8221-573a2a69e661" />
</p>
<br />

### Run the following command to check the new ip address for the server: `ip -c a`, `-c` means to see the addresses in color
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/0a4eca8d-8d6f-4624-b418-c24050274a99" />
</p>
<br />

---

<br />

# End of Project













