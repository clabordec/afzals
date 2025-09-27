<h1>Installing VMWare Workstation Player</h1>
This project outlines the installation of VMWare Workstation Player.<br />


<h2>Environments and Technologies Used</h2>

- VMWare Workstation Player


<h2>Operating Systems Used</h2>

- CentOS 7


<h2>High-Level Deployment and Configuration Steps</h2>

- Navigate to broadcom.com
- Register a account
- Navigate to the VMWare Dashboard
- Navigate to the Downloads section and download the latest version of VMWare.


<br>


<h1>Actions and Observations</h1>

## Installing VMWare Workstation Player
### Navigate to `broadcom.com`
<p>
<img src="https://github.com/user-attachments/assets/26095939-0ff3-42b4-b6e2-ccce8a83ba31" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click on `Support and Services`
<p>
<img src="https://github.com/user-attachments/assets/29a97785-3251-4912-829f-c98b452afb81" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click on the `Documents, Downloads and Support` drop down, then choose `Customer Support Portal`
<p>
<img src="https://github.com/user-attachments/assets/a0ff11e4-9d54-48bd-ab36-12e6fc4c88d2" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click on register, to create a new account
<p>
<img src="https://github.com/user-attachments/assets/bf84c7eb-643f-40ef-a0de-4f9e09532073" width="550" alt="Disk Sanitization Steps"/>
</p>

### Enter a valid email address, then verify that you are not a robot, then click Next 
<p>
<img src="https://github.com/user-attachments/assets/ce05de82-423b-4d86-9a16-7d36a8ec23b8" width="550" alt="Disk Sanitization Steps"/>
</p>

### Verify your email address, then click Verify & Continue
<p>
<img src="https://github.com/user-attachments/assets/429ba3c4-7c7c-443d-b520-fbf750edbb5c" width="550" alt="Disk Sanitization Steps"/>
</p>

### You'll then be navigated to the dashboard
<p>
<img src="https://github.com/user-attachments/assets/0d0ec8dc-415c-4216-9f5a-eefee18934f6" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to `My Downloads` on the dashboard, then click `HERE` to access all of the products from VMWare
<p>
<img src="https://github.com/user-attachments/assets/d4f22e70-914c-4721-96fe-69246834301b" width="550" alt="Disk Sanitization Steps"/>
</p>

### Type `VMware Work` in the search input box then click on the `VMware Workstation Pro` download link
<p>
<img src="https://github.com/user-attachments/assets/3de18737-080a-4374-8723-0e528657152a" width="550" alt="Disk Sanitization Steps"/>
</p>

### Download the latest version for your current OS you are using, in this case I will download the file on Windows
<p>
<img src="https://github.com/user-attachments/assets/1f4d4b7f-d3f0-4ded-8c41-01fd2f04ac9b" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click on the `Terms and Conditions` link, then click the checkbox, afterwards click on the download link
<p>
<img src="https://github.com/user-attachments/assets/f4c8c026-9216-49bd-910b-d030e9be7ec5" width="550" alt="Disk Sanitization Steps"/>
</p>

### The following message will appear, click `Yes` to process
<p>
<img src="https://github.com/user-attachments/assets/cf762fad-341c-4bdc-98fe-e7fcc7255674" width="550" alt="Disk Sanitization Steps"/>
</p>

### Fill in all highlighted fields, agree to the form, then click `Submit`
<p>
<img src="https://github.com/user-attachments/assets/d9c1e4ff-355b-48fc-b80c-ffe2fbbc8e5c" width="550" alt="Disk Sanitization Steps"/>
</p>

### You will be navigated back to the dashboard, click the download icon again and save the link to a file location
<p>
<img src="https://github.com/user-attachments/assets/bc5d2036-d809-47ca-8f84-ef0c80d8784d" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/5f67e303-2ea3-4456-9f1b-0c301bf05356" width="550" alt="Disk Sanitization Steps"/>
</p>


<br />


## Creating the security group
### In the USA OU, go to Users >> Right-click on the Accounting OU >> Click New > Click Group
<p>
<img src="https://github.com/user-attachments/assets/0d090446-9386-413e-ab6b-c6495d9d27f3" width="550" alt="Disk Sanitization Steps"/>
</p>

### Specify the name of the group, ensure that the group type is Security
<p>
<img src="https://github.com/user-attachments/assets/5a012fd7-772e-4d39-9223-40ae229c8eba" width="550" alt="Disk Sanitization Steps"/>
</p>

### Verify that the following group has been created
<p>
<img src="https://github.com/user-attachments/assets/1c97b9bb-b911-4b4f-ad08-ab8c158e1541" width="550" alt="Disk Sanitization Steps"/>
</p>

<br />

## Assiging the user to the group
### Right click on the Clerks security group, then click Properties
<p>
<img src="https://github.com/user-attachments/assets/02e3bbad-dee0-41e4-9a9d-5335567e4b98" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to the Members tab, then click Add
<p>
<img src="https://github.com/user-attachments/assets/7f5c9c74-b8e5-4b8b-8cd2-a204eb8f513a" width="550" alt="Disk Sanitization Steps"/>
</p>

### Enter the object name, in this case the user name, then click Check Names, the users full name along with their email address will appear in the object names input box, then click OK
<p>
<img src="https://github.com/user-attachments/assets/2c21d4b6-d7f6-4756-85b5-e86bb9419e04" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/20271d99-172d-44aa-8073-24b8334801a8" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Apply
<p>
<img src="https://github.com/user-attachments/assets/df78d16b-ecba-4056-b74b-2139ecb35081" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click OK
<p>
<img src="https://github.com/user-attachments/assets/1449ef56-0dc8-49e8-8b4a-f4d431d6e68f" width="550" alt="Disk Sanitization Steps"/>
</p>

<br />

## Verify the changes
### Right click on John Doe, then click Properties
<p>
<img src="https://github.com/user-attachments/assets/de9d1306-01b4-4a40-94e9-67a141f02368" width="550" alt="Disk Sanitization Steps"/>
</p>

### Go to the Members Of tab, and verify that the Clerks security group is in the tab
<p>
<img src="https://github.com/user-attachments/assets/d58eeaa2-4617-44aa-88e4-f438e13b0f5f" width="550" alt="Disk Sanitization Steps"/>
</p>

---

<br />


# End of Project

