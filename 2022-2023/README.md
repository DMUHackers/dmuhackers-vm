# DMU Hackers VM Setup Guide

[Direct Download](https://drive.google.com/file/d/1o-y_EzPeYCUBMiLdau8EvwJYzC9xrXHl/view) (Limited)

[Torrent Download](https://github.com/DMUHackers/dmuhackers-vm/2022-2023/raw/master/DMU-Hackers-x86-x64.ova.torrent)

[UTM Download](https://github.com/DMUHackers/dmuhackers-vm/2022-2023/raw/master/DMU-Hackers.utm.7z.torrent) (Torrent Only)

Username: **kali**<br>
Password: **kali**<br>

Kali Linux is a Linux distribution designed for penetration testing and digital forensics, it contains over 600 tools commonly used within the security field. As a society we have created a virtual machine with our own modified Kali Linux install, containing tools that we regularly use and recommend.

## 1 - Virtual Box

[Virtual Box](https://www.virtualbox.org/) is a free piece of software that allows us to run virtual machines on a variety of x86/amd64 based systems.

## 2 - VM Download

[Download](https://drive.google.com/file/d/1o-y_EzPeYCUBMiLdau8EvwJYzC9xrXHl/view) the latest version of the virtual machine and extract the **.ova** file to a suitable location.

## 3 - Importing the VM

Open the **.ova** file with virtual box manager and click import
<img style="max-width:80%;" src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/2022-2023/screenshots/import_to_virtualbox.png?raw=true">

Once the machine has been imported go to file > prefernces > network and create a new nat network and rename it to DMU Hackers
<img style="max-width:80%;" src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/2022-2023/screenshots/natnetwork.png?raw=true">

Start the VM. You should be presented with a login screen, log in with the username **kali** and the password **kali**.
<p align="center">
	<img style="max-width:80%;" src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/2022-2023/screenshots/login.png?raw=true">
</p>

Congratulations! You've just set up your own DMU Hackers Kali Linux VM, and if all went well you should be ready for future sessions.
<img style="max-width:80%;" src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/2022-2023/screenshots/desktop.png?raw=true">

# Setting up on arm64 Macs (m1, m2)
 
## 1 - UTM
[UTM](https://mac.getutm.app/) is a free and open-source piece of software that allows for the running of arm64 and emulation of x86/amd64 based virtual machines

## 2 - VM Download

To run the VM natively on arm64 instructions you will need the [UTM Native Version](https://github.com/DMUHackers/dmuhackers-vm/2022-2023/raw/master/DMU-Hackers.utm.7z.torrent).

## 3 - Using the VM
Start the VM. You should be presented with a login screen, log in with the username **kali** and the password **kali**.
<p align="center">
	<img style="max-width:80%;" src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/2022-2023/screenshots/login.png?raw=true">
</p>

Congratulations! You've just set up your own DMU Hackers Kali Linux VM, and if all went well you should be ready for future sessions.
<img style="max-width:80%;" src="https://github.com/DMUHackers/dmuhackers-vm/blob/master/2022-2023/screenshots/desktop.png?raw=true">


## Closing notes

If you need extra help feel free to ask in the [Discord](https://discord.gg/Vvrk4kK).
