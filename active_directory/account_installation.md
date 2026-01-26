## Installing and setting up Active Directory
### Within Server Manager, go to Manage >> Add Roles and Features
<p>
<img src="https://github.com/user-attachments/assets/28842a3d-154e-43de-8485-3e4d7836935b" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/229024e4-d715-47fe-b00a-397feac98cac" width="550" alt="Disk Sanitization Steps"/>
</p

### Choose `Role-based or featured-based installation` then click Next
<p>
<img src="https://github.com/user-attachments/assets/ba425c71-0bc1-4645-b55c-3bad7ebe6023" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Choose `Select a Server from the server pool` then click Next
<p>
<img src="https://github.com/user-attachments/assets/1d508688-b8e0-43db-a52a-8e8acf41fca1" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Add the following Roles then click Next
<p>
<img src="https://github.com/user-attachments/assets/5e94bdbc-4f27-4062-a93e-64ca55c5f3b7" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Make sure that Group Policy Management is checked then click Next
<p>
<img src="https://github.com/user-attachments/assets/f307695c-87e9-4564-9ce1-3b1cb2590804" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/77959899-5038-4fa1-8016-40075507d483" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/04518211-0b0a-44f9-82c1-9745446b0fa6" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/79ff65e1-449a-4786-851b-acbb813cb05a" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Select the following Role services, then click Next
<p>
<img src="https://github.com/user-attachments/assets/e221127b-cde8-4160-97aa-eed641ccb889" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/076e5d5f-5a86-4ff1-99d7-4d11f068e8f1" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### By default the following services will be check, click Next
<p>
<img src="https://github.com/user-attachments/assets/4206d866-4581-478d-8497-2900766c3929" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Install after review all of the Roles and Features
<p>
<img src="https://github.com/user-attachments/assets/0f1faa61-9f8b-4054-a55b-89aa8d2472d8" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


## Promoting the server as a Domain Controller
### Once the installation for AD DS has been completed click on `Promote this server to a domain controller`
<p>
<img src="https://github.com/user-attachments/assets/f248377a-3ec0-4b51-80a3-e6bbc657cc39" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />


### Under `Select the deployment operation` choose `Add a forest`
<p>
<img src="https://github.com/user-attachments/assets/8476ea97-8ec8-48ff-9bea-b7f090215362" width="550" alt="Disk Sanitization Steps" />
</p>
<br />


### Provide a domain name, in this case I will use `chaan.com` as the domain name, then click Next
<p>
<img src="https://github.com/user-attachments/assets/51e51975-7f49-4e2e-957e-620849c6b0b0" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Be sure to keep the `Forest Function Level` and `Domain Function Level` set to Windows Server 2016, and enter a secure password for the domain, then click Next
<p>
<img src="https://github.com/user-attachments/assets/76448cce-6dde-4b46-8512-4557912893b8" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/67fc6372-8d5d-4996-b6d9-60edaa365f82" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### The NetBIOS domain name will appear as the domain name without the `.com`, click Next
<p>
<img src="https://github.com/user-attachments/assets/b20f1ea0-1b84-4f67-8ea1-e83431ad1177" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/bbe830c7-bc35-40ea-9299-2687120c77ba" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Next
<p>
<img src="https://github.com/user-attachments/assets/1a773e7e-90d4-4455-af36-9b8ef2dc2019" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Click Install
<p>
<img src="https://github.com/user-attachments/assets/23f51a4c-d07d-46a4-af6a-f7801a605595" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Once the installation is complete, you will be prompted with the following message, the VM will automatically sign out in 5-10 seconds depending in Internet speed
<p>
<img src="https://github.com/user-attachments/assets/376f6be1-e617-4c12-97de-2bc27d839d24" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Enter in the password that was created for the domain
<p>
<img src="https://github.com/user-attachments/assets/59b1c7bc-eb2c-4323-9b33-1e12f18c5d3f" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

### Go to Server Manager, then click on Tools, you will see all of the features for Active Directory, along with others that was installed
<p>
<img src="https://github.com/user-attachments/assets/fed75294-b6e8-4c8c-b997-9e6c71d95a49" width="550" alt="Disk Sanitization Steps"/>
</p>
<br />

