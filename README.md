# psWinupdate
Basic application created in Powershell with a frontend UI to simplify things. 
Please be sure to run the application as administrator before applying/removing any changes on the workstation with this tool.

![Version 1.0.13.0](https://aselectfew.com/img/psWinBlock.png)

---
### How does it work?
Depending on if you are applying or removing the configuration, the application writes to the following registry keys:

    HKLM:\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\TargetReleaseVersion
    HKLM:\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\TargetReleaseVersionInfo
---
### Usage
In the textbox, set the maximum build number to be updated on the machine. Choose **Configure** & **Reboot**.
To remove any previously set configuration; Choose **Remove Config** & **Reboot**.
