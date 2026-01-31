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

---

<br />

# End of Project













