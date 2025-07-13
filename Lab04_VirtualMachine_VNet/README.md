# 💻 Lab 4: Create Virtual Machine inside Azure Virtual Network (VNet)

## 📘 Introduction

In this lab, I created a *Windows Server 2022 Virtual Machine* and connected it to my existing *Virtual Network (MyLabVNet)* and *Subnet (Subnet1)*.  
This setup helps isolate the VM inside a secure private network and supports RDP connectivity through a public IP.

---

## 🧪 Steps with Screenshots

### ✅ Step 1: Open Azure Portal & Search for Virtual Machines  
![step1-search-vm](./step1-search-vm.png)

---

### ✅ Step 2: Click "Create" and Select "Azure Virtual Machine"  
![step2-click-create-vm](./step2-click-create-vm.png)

---

### ✅ Step 3: Fill Basic Details  
- Subscription: Azure for Students  
- Resource Group: MyResourceGroup  
- VM Name: MyVNetVM  
- Image: Windows Server 2022  
- Size: B1s (Free Tier)  
- Username: Muqaddas  
- Password: ********

![step3-fill-vm-basics](./step3-fill-vm-basics.png)

---

### ✅ Step 4: Configure Networking  
- Virtual Network: MyLabVNet  
- Subnet: Subnet1  
- Public IP: Enabled  
- NSG: Basic with RDP (Port 3389)

![step4-networking-vnet](./step4-networking-vnet.png)

---

### ✅ Step 5: Leave Default Settings  
(Management, Security, Monitoring untouched)

![step5-default-settings](./step5-default-settings.png)

---

### ✅ Step 6: Review and Create  
- After validation passed  
- Click "Create"

![step6-review-and-create](./step6-review-and-create.png)

---

### ✅ Step 7: Deployment Completed  
- Azure confirms successful VM deployment

![step7-deployment-complete](./step7-deployment-complete.png)

---

### ✅ Step 8: Connect via RDP  
- Open VM Overview → Click "Connect"  
- Download RDP file and login

![step8-connect-rdp](./step8-connect-rdp.png)

---
### ✅ Step 9: View in Resource Group  
- Confirm the VM is listed in MyResourceGroup

![step9-inside-vm](./step9-view-resourcegroup.png)

---
✅ Status: Completed Successfully
