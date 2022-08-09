# Lab 2: Manage Linux VMs with the Azure CLI

Task: 

1. Create resource group
2. Create virtual machine
3. Connect to VM
4. Understand VM images
5. Understand VM sizes
6. VM power states
7. Management tasks


Notes:
Quickstart: Create a Linux VM

https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-manage-vm
Quickstart for Bash in Azure Cloud Shell

https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart


1. I created a new resource group by clicking on the create resources, inputing the right details and following as illustrated. 
2. I created a new virtual machine. "Created a new VM.png"
3. I connected to my VM using the cloud shell (bash)  
4. Understand VM images
   I created a VM image that can be used when creating a virtual machine 
5. Understand VM sizes
    This is to underlying performance of a processor. While attempting to resize size to this- Standard_DS4_v2, I got a response- (OperationNotAllowed) Operation could not be completed as it results in exceeding approved Total Regional Cores quota.
    I however tried a new size- Standard_B1ms and it worked. 
6. I understand what the VM power state is about can be view by using this command az vm get-instance-view \
7. Management Task: Under this, i performed:
   1. Get IP address: 
   2. Start virtual machine
   3. Stop virtual machine
   4. Stop virtual machine
   5. Then, i deallocated it to stop the billing

