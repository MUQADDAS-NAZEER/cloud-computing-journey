# 🌐 Lab 3: Create Azure Virtual Network (VNet)

## 📘 Introduction:

In this lab, I created a *Virtual Network (VNet)* in Microsoft Azure to learn how networking works in the cloud.  
A VNet is like a private network in the cloud that helps different resources (like VMs) communicate securely.

---

## 🧪 Steps Performed with Screenshots:

### ✅ Step 1: Search "Virtual Network" from Azure Portal
![step1-virtual-network-search](./step1-virtual-network-search.png)

---

### ✅ Step 2: Click on "Create" Button to Start Deployment
![step2-click-create](./step2-click-create.png)

---

### ✅ Step 3: Fill in the Basic Details of the VNet
- Name: MyLabVNet
- Subscription: Azure for Students
- Resource Group:lab3-rg
- Region: East Asia 

![step3-fill-basics](./step3-fill-basics.png)

---

### ✅ Step 4: Configure IP Addresses & Subnet
- Address space: 10.0.0.0/16
- Subnet name: Subnet1
- Subnet range: 10.0.1.0/24

![step4-ip-subnet](./step4-ip-subnet.png)

---

### ✅ Step 5: Leave Security Options Default
(DDoS, Firewall, Bastion – all left as default)

![step5-security-default](./step5-security-default.png)

---

### ✅ Step 6: Review + Create
- After validation, click "Create"

![step6-review-create](./step6-review-create.png)

---

### ✅ Step 7: Deployment Completed Successfully
- Azure shows deployment complete message

![step7-deployment-success](./step7-deployment-success.png)

---

### ✅ Step 8: VNet Overview
- Overview of Virtual Network configuration

![step8-vnet-overview](./step8-vnet-overview.png)

---

### ✅ Step 9: Check Subnet Under VNet
- Verify the Subnet1 is created

![step9-subnet-check](./step9-subnet-check.png)

---

### ✅ Step 10: View in Resource Group
- Go to Resource Group and see VNet listed

![step10-resourcegroup-view](./step10-resourcegroup-view.png)

---

## ✅ Lab Completed Successfully    
🔖 Task: Create Azure Virtual Network



