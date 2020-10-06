# DMU Hackers VM Setup Guide

Username: **root**

Password: **dmuhackers**

Kali Linux is a Linux distribution designed for penetration testing and digital forensics, it contains over 600 tools commonly used within the security field. As a society we have created a virtual machine with our own modified Kali Linux install, containing tools that we regularly use and recommend. This should be especially useful for use with remote sessions as if everyone is working from the same VM setup, it should be easier to provide remote assistance. 

## 1 - VMware

As a DMU student you have free access to the latest version of **VMware Workstation**, a piece of software that allows us to run virtual machines. Sign in and download it at https://vmware.tech.dmu.ac.uk/.

We recommend using **VMware Workstation 16.x Pro** on Windows and Linux, or **VMware Fusion 12 Pro** on macOS.

<p align="center">
	<img src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/screenshots/vmware_versions.png?raw=true">
</p>

Be sure to hang on to the **serial number** provided when you hit 'add to cart', you'll need to enter it after installing. 

## 2 - VM Download

Download the latest version of the virtual machine from ADD LINK and extract the **.ova** file to a suitable location.

## 3 - Importing the VM

Open VMware and click '**Open a Virtual Machine**', browse to the **.ova** file you extracted earlier. 
<img src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/screenshots/before_import.png?raw=true">

Once the machine has been imported, ensure that the network adapter is set to **Bridged (Automatic)** and power on the machine.
<img src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/screenshots/after_import.png?raw=true">

You should be presented with a login screen, log in with the username **root** and the password **dmuhackers**.
<p align="center">
	<img src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/screenshots/login.png?raw=true">
</p>

Congratulations! You've just set up your own DMU Hackers Kali Linux VM, and if all went well you should be ready for future sessions.
<img src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/screenshots/desktop.png?raw=true">

## Closing notes

Keep in mind that by default **this VM will revert back to a snapshot when you power it off**, so don't store anything important on it. 

If you need extra help feel free to ask in the [Discord](https://discord.gg/Vvrk4kK).
