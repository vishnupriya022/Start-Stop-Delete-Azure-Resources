### ☁️ Project 2: Start, Stop, and Delete Azure Resources (Free Tier)

### 📌 Project Objective

This project shows how to start, stop, and delete Azure resources using the Azure Portal. A virtual machine was created inside a resource group, then started and stopped to understand resource status. Finally, the resource group was deleted to avoid any cost.


### 🛡️ Cost Safety

Azure Free Account used

Ubuntu Server (Free OS)

Low-cost VM size

Resources deleted after practice

₹0 / £0 cost incurred

### 🔧 Tools Used

Microsoft Azure Portal

Azure Free Tier Account

GitHub for documentation

### 🧩 Step-by-Step Implementation

### ✅ Step 1: Create Resource Group


Resource Group Name: rg-azure-ops-demo

Region: UK South

### ✅ Step 2: Create Virtual Machine (Ubuntu – Free Tier)

VM Name: vm-ops-demo-01

Image: Ubuntu Server 20.04 LTS

Size: Standard B1s

Authentication: Password

✔️ VM successfully created

### ▶️ Step 3: Start Azure Virtual Machine

Go to Virtual Machines

Select: vm-ops-demo-01

Click Start 

Wait until status shows: Running

📸 Screenshot

### ▶️ Virtual Machine Running
![VM Running](vm-running.png)

VM status = Running

### ⏸️ Step 4: Stop Azure Virtual Machine

Select the VM

Click Stop

Confirm stop

Status changes to: Stopped (deallocated)

📸 Screenshot

### ⏸️ Virtual Machine Stopped
![VM Stopped](vm-stopped.png)

VM stopped status

💡 Stopping VM saves compute cost

### ❌ Step 5: Delete Azure Resources (Zero Cost)

Option 1: Delete Virtual Machine Only

Deletes VM

Other resources remain (disk, IP)

✅ Option 2: Delete Resource Group (Recommended)

Go to Resource Groups

Select: rg-azure-ops-demo

Click Delete Resource Group

Type resource group name to confirm

✔️ All resources deleted
✔️ No charges incurred

📸 Screenshot

### ❌ Resource Group Deleted
![Resource Group Deleted](resource-group-deleted.png)