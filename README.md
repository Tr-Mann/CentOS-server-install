CentOS is a free open-source alternative to Red Hat Enterprise Linux. CentOS offers much of the same function of its upstream counterpart and it supports many of the same tools which makes it a very popular choice for practicing or implementing enterprise-grade Linux distributions. 

To setup CentOS you must first download one of the many images they provide from their site: https://centos.org/download/

Then after downloading the file we can begin the installation, in this case we are using a virtual machine in VMware Workstation Pro.

LAB03_Server Install contents:

Create a new VM:

 ![image](https://github.com/user-attachments/assets/08ac5f76-beb5-4869-a33c-64b8bffe3558)


Select typical:

 ![image](https://github.com/user-attachments/assets/fa100130-b2dd-4f48-a235-ecea9166db5b)


Install OS later:

 ![image](https://github.com/user-attachments/assets/12e03774-0798-4014-a054-a573d2ba11ac)


Select CentOS:

 ![image](https://github.com/user-attachments/assets/9438c31c-d5ee-48ae-b3ea-587889dde448)


Give the VM a meaningful name:

 ![image](https://github.com/user-attachments/assets/40027591-b0de-477f-9e42-8ba383d58837)

Configure disk size for VM: 

 ![image](https://github.com/user-attachments/assets/5d55577e-96a4-4059-8a57-45b109ae1740)


Click customize hardware:

 ![image](https://github.com/user-attachments/assets/736b31b3-d761-47f7-8671-3f55cc4b0987)

Set the memory which the VM will have access to I used 2GB since that’s what’s recommended from the site:

 ![image](https://github.com/user-attachments/assets/88f0488f-5ad5-4fba-bf96-e7ed2038adef)



Configure CPU resources the VM will have access to:
 
![image](https://github.com/user-attachments/assets/a29d5a34-0afe-4a15-adb7-8716ad47450c)

Now CentOS is in our list of VMs but does not have any ISO file to install onto it so we need to add the ISO file:

 ![image](https://github.com/user-attachments/assets/86f03ee7-bec4-4cb9-8d33-cb573fd05f91)

In the VM settings add the ISO file:

 ![image](https://github.com/user-attachments/assets/4d6eb253-db6f-4d20-8b9e-ae3ad4a34862)


Now we can start the VM and select install CentOS to begin installing:

 ![image](https://github.com/user-attachments/assets/02ef2f2e-7427-4e1e-954e-4d3a04c394ab)


We are now in the installer so we can follow along with the steps it provides:

 ![image](https://github.com/user-attachments/assets/74c048f5-e62b-4c8b-a296-4b2650fda6d4)

Now we need to set up a user since otherwise no user will be able to login:

 ![image](https://github.com/user-attachments/assets/3a67df30-38d1-4fc7-af94-1016529a9dda)

I’m setting up a user called user01 with the password password:

 ![image](https://github.com/user-attachments/assets/721d22db-fbdf-455e-acac-906b1c21dc8f)

Now we’ll setup the disk partitioning for this install:

 ![image](https://github.com/user-attachments/assets/76423061-b81a-4740-bcaa-31d06e8488f0)


Now we have all of the necessary things setup to install so we can begin the installation:

 ![image](https://github.com/user-attachments/assets/671dd577-4759-4370-a165-b077a1c616b8)


Now that the installation is complete we should be able to reboot and login to the newly installed OS:

 ![image](https://github.com/user-attachments/assets/9eb11758-b5d2-44df-ab26-86bbb500d100)

We can now login using our user we made earlier:

 ![image](https://github.com/user-attachments/assets/43997487-d393-4744-a85d-fe5b58feee60)


And see the desktop for this new OS:

 ![image](https://github.com/user-attachments/assets/9cbcab2f-cdb9-4e38-85c8-9251281ab07f)

