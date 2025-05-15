# creating-vms
Creating a Windows 10 virtual machine in Microsoft Azure

Creating a virtual machine in Microsoft Azure

You first want to open Microsoft Azure and click "virtual machines'


![image](https://github.com/user-attachments/assets/f519cca9-292c-4b0b-a075-55bece111023)




Now click "Create" and select "Azure virtual machine"

![image](https://github.com/user-attachments/assets/ce7f1a21-4a5b-49b2-89a0-b88cb5b85242)


Select a resource group that you have created in this case mine is "RG-Network-Activities"

![image](https://github.com/user-attachments/assets/9d9c9e39-1955-41fa-af45-5f62bd921249)



You then want to choose a name for your virtual machine in this case I just put "windows-vm" but it does not matter what name you choose really

![image](https://github.com/user-attachments/assets/d6783aed-5d85-4a97-959d-d68b1721bb85)


Then now you can select the region you want (base it off of what region your resource group is under)
and choose "Windows 10 Pro, version 22H2" if you want to run a windows virtual machine

![image](https://github.com/user-attachments/assets/bc380d2c-649a-47e1-bb79-d9fe4470df8e)


Now choose the size for the virtual machine

![image](https://github.com/user-attachments/assets/6bbae703-1241-4d4c-afe9-832f149093a3)


Then "Administrator account" and choose a username and password to remember (this will be needed when remotely connecting to the virtual machine) and don't forget to accept the rules about Windows Services in the checkbox!

![image](https://github.com/user-attachments/assets/b0b2a477-a42b-4bbf-b497-8bc6e8031b12)


Now, go to networking at the top

![image](https://github.com/user-attachments/assets/6879a7d8-91b9-488f-91eb-3c32aaac3b39)


Then, hover your mouse over create new under "virtual network" and click (create new)

![image](https://github.com/user-attachments/assets/b2aad0f5-545d-4a41-bdf2-f049cbc9d9af)


Choose any name for the virtual network, in this case I chose "Lab1-testVnet"

![image](https://github.com/user-attachments/assets/7b38a92b-b408-4d1b-bf82-d0ed6661399a)


After doing that click create and you should get a "validation passed" sign at the top of your screen

![image](https://github.com/user-attachments/assets/075b4ad1-2951-4262-bfb7-9bc8f3e195b8)


Go back to your resources group and click on the one you created

![image](https://github.com/user-attachments/assets/76686fe0-2854-4188-a2ac-cf25c09f66f8)


All of the components of the virtual machine such as the disk, ip and other things should be created there

![image](https://github.com/user-attachments/assets/5b2b95cd-cc4d-4cb0-badb-f2668cb16fd3)


Go to the search bar again at the top and type in "virtual machines" and you should now have a fully functioning windows virtual machine!

![image](https://github.com/user-attachments/assets/3fd76170-037d-447d-a9e1-39237c939690)

