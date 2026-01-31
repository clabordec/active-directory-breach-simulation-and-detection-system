<h1>Setting up the main network for all VMs within VWware Workstation</h1>

This project outlines the configuration of the main network in VMware Worstation Pro to assign to all VMs for this project.<br />

<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 11 (Host machine)

<h2>High-Level Deployment and Configuration Steps</h2>

- Change the main network ip address to `192.168.10.0` as shown in the diagram
- Set all VMs network adapters to the configured network

<br />

<h1>Deployment and Configuration Steps</h1>

## Setting up the network
### Within Workstation Pro, go to Edit then select Virtual Network Editor
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/2c6257a7-5a71-42c9-b486-644deda5abea" />
</p>
<br />

### Select "Change Settings"
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/a819e356-a614-4a14-bb2d-8794c4a837af" />
</p>
<br />

### Select the VMnet 8 network adapter and change the Subnet IP to the following, ensure that DHCP is enabled, then click Apply, then click OK
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/f7d50b52-4daf-419b-8520-b448754ea8f5" />
</p>
<br />

### Go to each VM and set the network adapter to the newly configured network adapter
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/8971875a-41c0-4ebc-90f5-58890c56c0d6" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/18c8ec49-f11b-4194-864b-425ccb24034b" />
</p>
<br />

### During extraction, move the folder to a different path, then click Extract
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/81842c89-5486-4bb5-a304-00aa18bf657c" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/797cdc85-56e0-4cbe-ab0d-5674e23e78b7" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/67578976-7e29-4b87-bfc6-3877255fb650" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/adda0881-09ff-476f-a645-1982a2e5c8fc" />
</p>
<br />

### Double click the folder than double click on the file ending in ".vmx", this will automatically install the VM on the hypervisor (i.e WMware Workstation Pro)
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/b65100ad-59df-42d8-be6b-c34a992d3476" />
</p>
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/8bf7e1af-93b0-4bb5-bc62-efe0747916e5" />
</p>
<br />

### Power on the VM
<p>
<img width="550" height="550" alt="image" src="https://github.com/user-attachments/assets/d1d79c51-0b29-4c0d-b339-93844dc58d97" />
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













