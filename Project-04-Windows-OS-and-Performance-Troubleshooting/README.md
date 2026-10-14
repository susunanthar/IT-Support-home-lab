**# Windows OS and Performance Troubleshooting**



**## Overview**



This project demonstrates hands-on Windows troubleshooting skills using built-in Windows tools in a virtual lab environment.



**## Objectives**



&#x20; - Practice investigating system performance

&#x20; - Check Windows health

&#x20; - Review startup application

&#x20; - Use diagnostic tools to identify and resolve common Windows issues



**## Environment**



&#x20; - Oracle VirtualBox

&#x20; - Windows client VM

&#x20; - Task manager, Resource monitor, Windows settings, Reliability Monitor, Command Prompt, System File Checker (sfc /scannow)



**## Task Performed**



**### 1. System information**



Reviewed Windows system information, including the operating system and hardware details.



<img src="./Evidence/01-System-Information.png" alt="system information">



**### 2. Task Manager**



Reviewed running processes and their resource usage to understand how applications use system resources.



<img src="./Evidence/02-Task-Manager-Processes.png" alt="Task Manager Processes">



**### 3A. Task Manager - CPU Performance**



Monitored CPU utilization and reviewed the performance graph to understand processor usage.



<img src="./Evidence/03a-Task-Manager-CPU-Performance.png" alt="CPU Performance">



**### 3B. Task Manager - Memory Performance**



Reviewed memory utilization to understand how much RAM was in use and how Windows reports memory performance.



<img src="./Evidence/03b-Task-Manager-Memory-Performance.png" alt="Memory Performance">



**### 4. Resource Monitor - Resource Usage**



Used Resource Monitor to examine system resource activity in more detail.



<img src="./Evidence/04-Resource-Monitor-Resource-Usage.png" alt="Resource Monitor">



**### 5. Available Disk Space**



Checked available disk space to identify whether insufficient storage could contribute to Windows performance problems.



<img src="./Evidence/05-Available-Disk-Space.png" alt="Available disk space">



**### 6. High Resource Usage Investigation**



Investigated running processes and reviewed CPU and memory usage to practice identifying applications that may contribute to slow performance.



<img src="./Evidence/06-High-Resource-Usage-Investigation.png" alt="high resource usage investigation">



**### 7. Startup Application**



Reviewed applications configured to launch automatically when windows start.



<img src="./Evidence/07-Startup-Applications.png" alt="startup app">



**### 8. Disable a Nonessential Startup Application**



Disabled a selected nonessential startup application to practice managing applications that launch automatically.



<img src="./Evidence/08a-Disable-Nonessential-Startup-App.png" alt="disable a selected startup app">





<img src="./Evidence/08b-Disable-Nonessential-Startup-App.png" alt="disable a selected startup app">



**### 9. Windows Update Status**



Checked the Windows update page to review the system's update status.



<img src="./Evidence/09-Windows-Update-Status.png" alt="windows update status">



**### 10. Reliability Monitor**



Reviewed Windows reliability history to check for recorded application failures and system issues.



<img src="./Evidence/10-Reliability-Monitor.png" alt="reliability monitor">



**### 11. System File Checker (SFC)**



Ran 'sfc /scannow' in an elevated Command Prompt to scan Windows system files for corruption. Windows reported that it found corrupt files and successfully repaired them.



<img src="./Evidence/11-System-File-Checker-Result.png" alt="SFC result">





















































