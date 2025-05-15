# creating-vms
Creating a Windows 10 virtual machine in Microsoft Azure

Creating a virtual machine in Microsoft Azure

You first want to open Microsoft Azure and click "virtual machines'


![image](https://github.com/user-attachments/assets/d5c8f5d3-c721-40e7-ade3-8dcbc7018529)


Now click "Create" and select "Azure virtual machine"

![image](https://github.com/user-attachments/assets/52e76096-2c94-49e8-b2af-fdab98ef43f9)

Select a resource group that you have created in this case mine is "RG-Network-Activities"

![image](https://github.com/user-attachments/assets/a3e845e7-2df9-4242-b2d7-47632938b0d0)


You then want to choose a name for your virtual machine in this case I just put "windows-vm" but it does not matter what name you choose really

![image](https://github.com/user-attachments/assets/14b65801-f3c9-49e2-824c-c1df2006528d)

Then now you can select the region you want (base it off of what region your resource group is under)
and choose "Windows 10 Pro, version 22H2" if you want to run a windows virtual machine

![image](https://github.com/user-attachments/assets/eb9db5b2-ad55-47f7-9bca-e6428ed04b88)

Now choose the size for the virtual machine

![image](https://github.com/user-attachments/assets/7e84839d-70b3-4ddb-84bf-5e15533ef4d9)

Then "Administrator account" and choose a username and password to remember (this will be needed when remotely connecting to the virtual machine) and don't forget to accept the rules about Windows Services in the checkbox!

![image](https://github.com/user-attachments/assets/dcde2df3-6edc-4d6c-b3f3-859717c36598)

Now, go to networking at the top

![image](https://github.com/user-attachments/assets/60a06dfb-5933-47bb-82a4-8b8f2d2c44a4)

Then, hover your mouse over create new under "virtual network" and click (create new)

![image](https://github.com/user-attachments/assets/ece42fb5-0d1f-43e9-a1ba-2415c359a189)

Choose any name for the virtual network, in this case I chose "Lab1-testVnet"

![image](https://github.com/user-attachments/assets/c11d41e8-8587-4ce8-84d3-cad0806e29bc)

After doing that click create and you should get a "validation passed" sign at the top of your screen

![image](https://github.com/user-attachments/assets/41eb25c3-9eb5-424a-a2d1-e591e094c0cf)

Go back to your resources group and click on the one you created

![image](https://github.com/user-attachments/assets/6ee2d278-6443-47aa-bf7a-985b5845875e)

All of the components of the virtual machine such as the disk, ip and other things should be created there

![image](https://github.com/user-attachments/assets/558fc8d2-685b-4a0a-b20d-17b3590ad0e1)

Go to the search bar again at the top and type in "virtual machines" and you should now have a fully functioning windows virtual machine!

![image](https://github.com/user-attachments/assets/6114e6af-9219-4b63-ba50-00247fca948b)
