# EX---4-ORACLE-VM-VIRTUAL-BOX-INSTALLATION--
# Virtualization
## AIM:
To install Oracle VM VirtualBox, a free and open-source hosted hypervisor, on a computer system,enabling the creation and management of virtual machines for running multiple operating systems on a single host machine
## EQUIPMENTS REQUIRED:
●Hardware: PCs
●Software: Oracle VM ware  , CENT OS 
●A system with Oracle VM VirtualBox installed.  At least 4 GB RAM and 20 GB free disk space.
●  Kali Linux ISO image, which can be downloaded from the official website.

## Procedure:
Step 1: Download VirtualBox

 Go to the VirtualBox official website: VirtualBox Downloads  Choose the appropriate version for your operating system:
 
 Windows hosts (for Windows users)
 
 macOS hosts (for Mac users)
 
 Linux distributions (for Linux users)
 
Step 2: Install VirtualBox (Windows/macOS)

For Windows:

1.Open the downloaded installer ( VirtualBox-x.x.x-xxxx-Win.exe ).

2.Follow the setup wizard:  Click Next.

 Select the installation location (default is recommended).
 
  Choose the components you want to install and click Next.
  
 The installer may show a warning about network interfaces; allow it to proceed by clicking Yes.
 
3.Click Install and allow the process to complete.

Step 3: Verify the Installation

1.Launch VirtualBox from the desktop or start menu.

2.The VirtualBox Manager should open, showing options to create and manage virtual machines.

Step-by-Step Installation Guide:

Step 1: Download Kali Linux ISO

1.Go to the Kali Linux download page.

2.Download the Kali Linux ISO file.

 Choose between 32-bit or 64-bit depending on your system (most systems are 64-bit).  Download the Installer version for a full installation.
 
Step 2: Open Oracle VM VirtualBox

1.Launch VirtualBox on your computer.

<img width="1920" height="1080" alt="Screenshot 2025-08-24 173912" src="https://github.com/user-attachments/assets/de65a5b1-255b-4d41-a7b2-a37b8eb7ca4e" />

Step 3: Create a New Virtual Machine

1.In VirtualBox, click on the New button to create a new virtual machine.

2.Name and Type Settings:

 Name: Give a name like "Kali Linux".
 
 Type: Select Linux.
 
 Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO version you downloaded.
 
3.Click Next to proceed.

Step 4: Allocate Memory (RAM)

1.Choose how much RAM to allocate to your virtual machine.

  Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
  
2.Click Next.

Step 5: Create a Virtual Hard Disk

1.Select Create a virtual hard disk now.

2.Click Create.

Step 6: Select Hard Disk File Type

1.Choose VDI (VirtualBox Disk Image).

2.Click Next.

Step 7: Storage on Physical Hard Disk

1.Select Dynamically allocated (so the disk will grow as needed).

2.Click Next.

Step 8: Allocate Storage Space

1.Set the hard disk size. Kali Linux requires at least 20 GB of storage.

  You can increase this if you plan to install many additional tools later.
  
2.Click Create.

Step 9: Configure Kali Linux ISO

1.Select the VM from the list in VirtualBox and click Settings.

2.Navigate to Storage from the side menu.

3.Under Controller: IDE, click the Empty CD icon.

4.On the right, click the CD icon next to Optical Drive and choose Choose a disk file....

5.Locate and select the Kali Linux ISO you downloaded.

6.Click OK.

Step 10: Start the Virtual Machine

1.In VirtualBox, click Start to boot up your Kali Linux virtual machine.

Step 3: Create a New Virtual Machine

1.In VirtualBox, click on the New button to create a new virtual machine.

2.Name and Type Settings:

 Name: Give a name like "Kali Linux".
 
 Type: Select Linux.
 
 Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO 
 
 version you downloaded.
 
3.Click Next to proceed.

Step 4: Allocate Memory (RAM)

1.Choose how much RAM to allocate to your virtual machine.

  Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
  
2.Click Next.

Step 5: Create a Virtual Hard Disk

1.Select Create a virtual hard disk now.

2.Click Create.

Step 6: Select Hard Disk File Type

1.Choose VDI (VirtualBox Disk Image).

2.Click Next.

Step 7: Storage on Physical Hard Disk

1.Select Dynamically allocated (so the disk will grow as needed).

2.Click Next.

Step 8: Allocate Storage Space

1.Set the hard disk size. Kali Linux requires at least 20 GB of storage.

  You can increase this if you plan to install many additional tools later.
  
2.Click Create.

Step 9: Configure Kali Linux ISO

1.Select the VM from the list in VirtualBox and click Settings.

2.Navigate to Storage from the side menu.

3.Under Controller: IDE, click the Empty CD icon.

4.On the right, click the CD icon next to Optical Drive and choose Choose a disk file....

5.Locate and select the Kali Linux ISO you downloaded.

6.Click OK.

Step 10: Start the Virtual Machine

In VirtualBox, click Start to boot up your Kali Linux virtual machine
<img width="1920" height="1080" alt="Screenshot 2025-08-24 174421" src="https://github.com/user-attachments/assets/392bd6ad-e994-499b-8b37-86417c8986c3" />

Step 11: Begin Kali Linux Installation

1.The VM will now boot from the ISO. You’ll see a boot menu.  Select Graphical Install and press Enter.
<img width="1920" height="1080" alt="Screenshot 2025-08-24 174436" src="https://github.com/user-attachments/assets/88739d78-5006-4754-a97c-302fe00f7c74" />

Step 12: Select Language and Region

1.Choose your language, location, and keyboard layout.  These can be configured to your preference.

2.Click Continue after each selection.

Step 13: Configure the Network

1.You’ll be prompted to configure the network.

  Enter a hostname for your system (e.g., kali).
  
  You can leave the domain name empty if you don’t need to set up a domain.
  
Step 14: Set Up Users and Passwords

1.Create a root password for the administrator account.

  Choose a strong password and re-enter it for confirmation.
  
Step 15: Partition Disks

1.Choose Guided - use entire disk for simplicity (recommended for beginners).

2.Select the virtual disk you created earlier.

3.Choose All files in one partition.

4.Finish partitioning and confirm to write the changes to disk.

Step 16: Install the System

1.The installer will now copy files and install Kali Linux. This may take several minutes.

Step 17: Install GRUB Bootloader

1.When prompted to install the GRUB bootloader, choose Yes.

2.Select the virtual hard disk as the location to install GRUB.

Step 18: Complete Installation

1.After the installation is complete, click Continue to reboot the virtual machine.

Step 19: Login to Kali Linux

1.Once the machine reboots, you’ll be presented with a login screen.

2.Log in using the root account and the password you set earlier.
<img width="1920" height="936" alt="VirtualBox_kalilinux_24_08_2025_17_45_34" src="https://github.com/user-attachments/assets/edd107e7-3f25-41fc-9fcb-79dd7ad37c3d" />

## EXPECTED OUTPUT

<img width="955" height="925" alt="VirtualBox_kalilinux_24_08_2025_17_59_23" src="https://github.com/user-attachments/assets/adb895d6-2628-4fa2-aa55-52e15ae3784f" />

## Expected and terminal output:
<img width="1920" height="937" alt="VirtualBox_kalilinux_24_08_2025_18_14_33" src="https://github.com/user-attachments/assets/3b9390f4-05d3-462f-ac7a-a2bc94ffc587" />

<img width="1920" height="937" alt="VirtualBox_kalilinux_24_08_2025_18_03_53" src="https://github.com/user-attachments/assets/8a357197-dae0-49da-b4ed-2fdfb2ce1b31" />

## Linux Commands:
<img width="1920" height="937" alt="VirtualBox_kalilinux_24_08_2025_18_11_39" src="https://github.com/user-attachments/assets/3c0c1037-394b-4fde-8670-ab22c351ebd1" />

## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.

