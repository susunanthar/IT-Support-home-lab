**# Microsoft 365 Web Application End-User Troubleshooting**



**## Overview**



This project simulates real-world Level 1 (L1) Help support scenarios focused on Microsoft 365 web application. It demonstrates foundational troubleshooting, ticket resolution, and end-user verification workflows conducted within a browser environment on a virtual machine.



**## Objectives**



\- Diagnose and resolve common end-user issues across core M365 collaboration and productivity tools.

\- Validate web-based application access, mail flow, and cloud storage permissions.

\- Document a structured, step-by-step troubleshooting methodology suitable for an IT support portfolio.



**## Environment \& Tools**



\- Oracle VM VirtualBox

\- Windows 11 ( Virtual Machine)

\- Google Chrome / Microsoft Edge

\- Outlook Web App (OWA), Microsoft Teams Web/Desktop, Microsoft OneDrive

\- Test M365 user account for mail flow and sharing verification



**## Tasks Performed**



**### Microsoft Outlook & Mail flow ( Screenshots 01 - 05 )**



**#### 1. Verify the Outlook Web Environment**



Accessed the Outlook Web App ('outlook.live.com') to confirm account access and establish a baseline browser environment for email troubleshooting.



<img src="./Evidence/01-Outlook-Web-Environment.png" alt="outlook web environment">



**#### 2. Verify Inbound and Outbound Mail Flow**



Send and received a test email message to confirm active mail delivery and rule out service outages.



<img src="./Evidence/02-Test-Email-Verification.png" alt="test email verification">



**#### 3. Troubleshooting Missing Mail in Focused Inbox**



Checked both the 'Focused' and 'Other' inbox tabs to locate emails automatically filtered away from the user's primary view.



<img src="./Evidence/03a-Focused-Inbox-Troubleshooting.png" alt="focused inbox tab">

<img src="./Evidence/03b-Focused-Inbox-Troubleshooting.png" alt="other inbox tab">



**#### 4. Locate Misfiled Messages Using Global Search**



Used the Outlook search bar with keyword filters across all folders to find misplaced emails.



<img src="./Evidence/04-Email-Search-Troubleshooting.png" alt="email search troubleshooting">



**#### 5. Inspect Junk Email and Deleted Items**



Reviewed the 'Junk Email' and 'Deleted Items' folders to check for falsely flagged spam or accidentally deleted message.



<img src="./Evidence/05a-Checking-Junk-Email-and-Deleted-Items.png" alt="checking junk email">

<img src="./Evidence/05b-Checking-Junk-Email-and-Deleted-Items.png" alt="checking deleted items">



**### Microsoft Teams Collaboration & Audio/Video (Screenshots 06 - 10)**



**#### 6. Verify Microsoft Teams Web Chat Functionality**



Logged into the Microsoft Teams web client ('teams.live.com') and sent a test message to confirm basic messaging availability.



<img src="./Evidence/06-Teams-Web-Chat-Verification.png" alt="teams web chat verification">



**#### 7. Troubleshooting Teams Microphone Settings and OS Permissions**



Verified the active microphone device inside Teams settings and confirmed app-level microphone access in Windows Privacy \& Security settings.



<img src="./Evidence/07a-Teams-Microphone-Troubleshooting.png" alt="teams microphone setting">

<img src="./Evidence/07b-Teams-Microphone-Troubleshooting.png" alt="windows microphone permissions">



**#### 8. Troubleshooting Teams Speaker Output and System Volume**



Checked the selected playback device in Teams audio settings and verified system output levels in the Windows Sound Volume Mixer.



<img src="./Evidence/08a-Teams-Speaker-Troubleshooting.png" alt="teams speaker setting">

<img src="./Evidence/08b-Teams-Speaker-Troubleshooting.png" alt="windows volume mixer">



**#### 9. Verify Camera Permissions and Pre-Join Video Settings**



Confirmed camera access permissions for Microsoft Teams in Windows Privacy \& Security settings and checked the pre-join meeting video toggle.



<img src="./Evidence/09a-Teams-Camera-Permission-Troubleshooting.png" alt="windows camera permission">

<img src="./Evidence/09b-Teams-Camera-Permission-Troubleshooting.png" alt="teams pre-joun video settings">



**#### 10. Verify Teams Meeting Access and Controls**



Joined an active test meeting to confirm audio, participant visibility, and meeting control functionality.



<img src="./Evidence/10-Teams-Meeting-Access-Verification.png" alt="teams meeting access verification">


### Microsoft OneDrive Cloud Storage & Sharing (Screenshots 11 - 13)

#### 11. Verify the OneDrive Web Environment

Accessed the Microsoft OneDrive web portal ('onedrive.live.com') to confirm cloud storage availability in the browser.

<img src="./Evidence/11-OneDrive-Web-Environment.png" alt="onedrive web environment">

#### 12. Verify OneDrive File Upload functionality

Upload a test text file ('OneDrive_test.txt') to confirm active file synchronization and write permissions in cloud storage.

<img src="./Evidence/12-OneDrive-File-Upload-Verification.png" alt="onedrive file upload verification">


#### 13. Configure and Verify OneDrive File Sharing Permissions

Configured user access levels ('Can view' vs 'Can edit'), adjusted link sharing scopes, and verified recipient access in the 'shared with me' view.


<img src="./Evidence/13a-OneDrive-File-Share-and-Access-Verification.png" alt="onedrive share permissions">
<img src="./Evidence/13b-OneDrive-File-Share-and-Access-Verification.png" alt="onedrive link settings">
<img src="./Evidence/13c-OneDrive-File-Share-and-Access-Verification.png" alt="onedrive shared with me verification">





















































