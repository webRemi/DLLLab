# DLLLab
Some random DLLs reside there. Be careful with the one you deploy.

## Description
Use a tool from the FUSE family to deploy the DLLs (DFuse, NFuse, SFuse)

## Table
| ID | Name | Description | Status | System harm |
| --- | --- | --- | --- | --- |
| 0 | dllwin.dll | The DLL ransomware! Deploy a **ransomware** and encrypt **every** files in the directory | OK | Be cautious |
| 1 | dllwin1.dll | Deploy a **keylogger** and stores the log file in **C:\Users\\%username%\AppData\Thumbs.db** | OK | x |
| 2 | dllwin2.dll | Deploy a **clipboardlogger** and stores the log file in **C:\Users\\%username%\AppData\Thumbs.db** | OK | x |
| 3 | dllwin3.dll | Spawn a reverse shell | In progress | x | 
| 4 | dllwin4.dll | Dump registry hives: **SAM** **SYSTEM** **SECURITY** as **config.ini** **data.db** **export.cfg** and store them in **C:\Users\\%username%\AppData\Roaming** | OK | Clean directory after usage |
| 5 | dllwin5.dll | Spawn a **calc.exe** process for malware dev testing | OK | x |
| 6 | dllwin6.dll | Require **Administrative** privileges! Spawn a **NT AUTHORITY\SYSTEM** shell and enable **all** existing privileges | OK | x |
