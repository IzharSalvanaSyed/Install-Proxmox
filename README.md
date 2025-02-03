# Install-Proxmox

### Table of contents

1. [Introduction](#introduction)
2. [Installing Proxmox](#proxmox)

## Introduction <a name="introduction">
------  
## Installing Proxmox <a name="proxmox">

### Creating an installation USB for Proxmox  
1. Download Proxmox ISO from the [proxmox website](https://www.proxmox.com/en/downloads/proxmox-virtual-environment/iso)
2. Create a bootable Proxmox Installation USB
   - There are many ways to create a bootable USB Stick, but I used Balena Etcher.
     1. Download [BalenaEtcher](https://etcher.balena.io/)
     2. Install BalenaEtcher
     3. Plug in a USB Stick
     4. Open BalenaEtcher
     5. Select Proxmox ISO image
     6. Select the USB stick to Flash Proxmox ISO
     7. Wait a while for it to flash
     8. FINISH
    
### Instal Proxmox  
1. Plug the USB to an available USB port on your Computer
2. Press Delete, F2, or whatever key you need to press to get into the Bios
3. Change the boot order to start up with the Flashed USB

### Installation Process
- you can use this guide to [install Proxmox](https://pve.proxmox.com/wiki/Installation)
- Followed this [video](https://youtu.be/gTCZ-g-cbbE?t=138) at [9:39](https://youtu.be/gTCZ-g-cbbE?t=138) to install Proxmox
