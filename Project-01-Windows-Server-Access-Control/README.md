**# Windows Server File Share Access Control Using Active Directory Security Groups and NTFS Permissions**



**## Overview**

This project demonstrates configuring role-based access to a Windows Server shared folder using Active Directory security groups and NTFS permissions.



**## Objectives**

&#x20;    - 	Create Active Directory security groups for different access levels

&#x20;    -	Add users to the appropriate security groups

&#x20;    -	Create windows server shared folder

&#x20;    -	Apply share permission to everyone

&#x20;    -	Apply NTFS permissions based on user roles

&#x20;    -	Test access using different user accounts



**## Environments**

&#x20;    -	Windows Server

&#x20;    -	Active Directory Domain Services (AD DS)

&#x20;    -	Active Directory Users and Computers

&#x20;    -	Windows clients

&#x20;    -	NTFS permissions

&#x20;    -	Active Directory security groups



**## Evidence**



**## 1. Active Directory Security Groups**

Security groups are created in AD to manage access to shared folder based on user roles.



<img src="./Evidence/01-AD-Security-Groups.PNG" alt="AD Security Groups">



**## 2. Group Memberships**

Users were added to the appropriate security groups according to their required access level.



!\[AD Group Members for Modify Permission](Evidence/02-AD-Group-Members.PNG)

!\[AD Group Members for read Permission](Evidence/03-AD-Group-Members.PNG)



**## 3. Shared Folder Configuration**

The 'practice\_shared' folder was configured as a Windows Server shared folder.



!\[Shared Folder](Evidence/04-shared-Folder.PNG)



**## 4. Share Permissions**

Share-level permissions were configured for the shard folder.



!\[Share Permissions](Evidence/05-Share-Permissions.PNG)



**## 5. NTFS Modify Permissions**

The group was granted NTFS modify permissions on the folder.



!\[NTFS Modify Permission](Evidence/06-NTFS-Modify-Permission.PNG)



**## 6. NTFS Read Permissions**

The group was granted NTFS read permission on the folder.



!\[NTFS Read Permission](Evidence/07-NTFS-Read-Permission.PNG)



**## 7. Access Testing - Modify Permission**

A user with modify permission successfully created and deleted a file.



!\[Create File Test](Evidence/08-Create-File-Test.png)

!\[Delete File Try](Evidence/09-try-to-delete-file-test.png)

!\[Delete File Success](Evidence/10-Delete-File-Success.png)



\## 8. Access Testing - Read Permission

A user with read permission was unable to read file contents of the shared folder.



!\[Access File Denied](Evidence/11-Access-File-Denied.png)

