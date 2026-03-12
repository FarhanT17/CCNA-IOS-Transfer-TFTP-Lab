# Cisco IOS Transfer Using TFTP (Packet Tracer Lab)

## Overview

This lab demonstrates how to transfer a Cisco IOS image from a TFTP server to a router flash memory using Cisco Packet Tracer.

The lab focuses on IOS management, flash storage verification, and understanding the router boot process.

## Lab Topology

Router connected to a TFTP Server

Router IP: 10.1.1.1  
TFTP Server IP: 10.1.1.2

## Commands Used

enable

configure terminal

interface fastethernet0/0  
ip address 10.1.1.1 255.255.255.0  
no shutdown

ping 10.1.1.2

show flash

copy tftp flash

show version

reload

## Steps Performed

1. Configured IP connectivity between router and TFTP server
2. Verified connectivity using ping
3. Checked router flash memory
4. Copied IOS image from TFTP server to router flash
5. Verified the IOS file stored in flash
6. Reloaded the router and verified the operating system

## Key Learning

Routers can detect incompatible IOS images.  
In this lab the router attempted to load an IOS image designed for a different platform and automatically booted the correct IOS stored in flash.

## Skills Practiced

• IOS management  
• Flash memory operations  
• TFTP file transfer  
• Router boot process  
• Basic troubleshooting

## Tools Used

Cisco Packet Tracer

## Screenshots
<img width="1222" height="719" alt="Screenshot 2026-03-12 at 1 49 52 pm" src="https://github.com/user-attachments/assets/3a93a454-fa64-48b7-965a-ccb9050a83c5" />
<img width="692" height="660" alt="Screenshot 2026-03-12 at 1 50 45 pm" src="https://github.com/user-attachments/assets/f5452ebe-3739-4cdb-bc82-e2fac4323ce1" />
<img width="679" height="597" alt="Screenshot 2026-03-12 at 1 51 11 pm" src="https://github.com/user-attachments/assets/2ed3289c-9232-4187-ab16-94cac33ce64b" />
<img width="688" height="602" alt="Screenshot 2026-03-12 at 1 52 09 pm" src="https://github.com/user-attachments/assets/b0bbea78-6eeb-4153-8435-65b7c651906e" />



