**# Active Directory User \& Account Management**



**## Overview**



This project demonstrates common Active Directory user and account management tasks performed by a junior help desk or Level 1 IT support technician.



The lab focuses on creating and managing domain user accounts, handling account lockouts, resetting passwords, managing account status, and verifying group membership.



**## Objectives**



\-Create a domain user account

\-Configure and test an account lockout policy

\-Troubleshoot a locked user account

\-Disable and re-enable a user account

\-Reset a user's password

\-Verify successful password changes

\-Verify Active Directory group membership

\-Test account behavior from the user's perspective



**## Environment**



\-Windows Server

\-Active Directory Domain Services (AD DS)

\-Active Directory Users and Computers (AD UC)

\-Windows client

\-Domain User Accounts

\-Active Directory Security Groups

\-Group Policy



**## Tasks Performed**

&#x20;

**### 1. Create a Domain User**



Created a test domain user account using Active Directory Users and Computers.



<img src="./Evidence/01-Create-Domain-User.PNG" alt="Create Domain User">



**### 2. Verify the User in Active Directory**



Verified that the new user account was successfully created in Active Directory.



<img src="./Evidence/02-Verify-User-in-ADUC.PNG" alt="Verify user account">



**### 3. Verify Domain User Login**



Tested the domain user account from the Windows client.



<img src="./Evidence/03-Verify-Domain-User-Login.png" alt="Verify domain user login">



**### 4. Configure Account Lockout Policy**



Configured an account lockout threshold to help protect domain accounts against repeated incorrect password attempts.



<img src="./Evidence/04-Configure-Account-lockout-policy.PNG" alt="Account Lockout Policy">



**### 5. Test Account Lockout**



Tested the policy by entering an incorrect password repeatedly and verifying that the account became locked.



<img src="./Evidence/05-Test-Account-Lockout.png" alt="Test Account Lockout">



**### 6. Verify Account Lockout**



Verified that the user account was locked after entering incorrect password repeatedly.



<img src="./Evidence/06-Account-Locked-After-Failed-Logins.PNG" alt="Account Locked">



**### 7. Unlock the User Account**



Unlock the user's account using Active Directory Users and Computers.



<img src="./Evidence/07-Unlock-User-Account.PNG" alt="Unlock User Account">



**### 8. Disable the User Account**



Disabled the domain user account.



<img src="./Evidence/08-Disable-User-Account.PNG" alt="Disable User Account">



**### 9. Verify the Disabled Account**



Tested the account from the user's side and verified that the disabled account could not be used normally.



<img src="./Evidence/09-Verify-Disabled-Account.png" alt="Verify Disabled Account">



**### 10. Re-enable the User Account**



Re-enabled the disabled domain user account.



<img src="./Evidence/10-Re-enable-User-Account.png" alt="Account re-enable">



**### 11. Reset the User Password**



Performed the password reset for the domain user.



<img src="./Evidence/11-Reset-User-Password.png" alt="Reset User Password">



**### 12. Test the Reset Password**



Tested the new password after performing the password reset.



<img src="./Evidence/12-Test-Reset-Password.png" alt="Test Reset Password">



**### 13. Verify the New Password**



Verified that the user could successfully authenticate using the updated password.



<img src="./Evidence/13-Verify-New-Password.png" alt="Verify New Password">



**### 14. Change the New Password After Reset**



Verified that the user successfully changed the new password.



<img src="./Evidence/14-Change-Password-After-Reset.png" alt="Change the New Password">



\### 15. Verify Group Membership



Verified that the user account belonged to the appropriate Active Directory Security Group.



<img src="./Evidence/15-Verify-Group-Membership.png" alt="Verify Group Membership">











