# Windows RDP Support Lab

## Objective 
In this lab, I built a simulated IT help desk environment using VirtualBox with three virtual machines: an Active Directory Domain Controller, a HelpDesk workstation, and a User workstation. I organized accounts by placing my HelpDesk account in an IT organizational unit and my User account in a Sales OU to reflect a real enterprise setup. Through this environment, I was able to practice key help desk tasks such as resetting and unlocking user passwords, managing group memberships, applying group policies, and providing remote support using RDP. 

This lab gave me hands-on experience with Active Directory and Windows administration, helping me strengthen the skills needed for common IT support scenarios.

### Skills Learned

- Active Directory domain setup and user account management

- Password resets, account unlocks, and group membership administration

- Group Policy creation and deployment

-  Remote Desktop support and troubleshooting

- Windows Server and Windows 10 domain configuration

### Tools Used

- VirtualBox

- Windows Server 2022 (Active Directory Domain Services)

- Active Directory Users and Computers (ADUC)

- Remote Desktop Protocol (RDP)

- PowerShell (basic administration and troubleshooting)

## Steps

<img width="509" height="178" alt="image" src="https://github.com/user-attachments/assets/8d7e8c16-2efc-48c1-8051-ca4e29e0d3f7" />
<img width="490" height="153" alt="image" src="https://github.com/user-attachments/assets/8b2baa6a-eed0-4539-938c-1be2c725a993" />


_**Ref 1:** Began installation and configuration of all necessary VM's_

-----

<img width="634" height="358" alt="image" src="https://github.com/user-attachments/assets/b39b9dda-55d8-458c-9493-fcb57031db3b" />

_**Ref 2:** Install Windows Server, AD DS, and create users (See AD LAB for more Active Directory setup images)_

-----
<img width="603" height="319" alt="image" src="https://github.com/user-attachments/assets/b13b2bdc-7f54-48d7-8653-b7ba87672b71" />
<img width="278" height="56" alt="image" src="https://github.com/user-attachments/assets/c71d7b8a-d864-4f12-8947-7635cea26e1b" />

_**Ref 3:** Manually reset sales employee's password through ADUC &/or force password change for security policies and more_

-----
<img width="787" height="542" alt="image" src="https://github.com/user-attachments/assets/f53fc613-74ee-44d2-a25b-f8d2e0314f40" />
<img width="887" height="241" alt="image" src="https://github.com/user-attachments/assets/478f4b5f-058c-4a3b-b35a-b1fa50d4fb46" />
<img width="436" height="147" alt="image" src="https://github.com/user-attachments/assets/29922a3b-40c8-4746-ad92-ac3fb0c4991f" />

_**Ref 4:** Add RDP policy and force update on target machine_

-----

<img width="687" height="252" alt="image" src="https://github.com/user-attachments/assets/04839605-59eb-4839-867a-cc7dd0b99c80" />


_**Ref 5:** Initiate RDP on Admin (IT) account and continue with any relevant support tasks_
