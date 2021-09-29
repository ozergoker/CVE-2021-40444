# Microsoft MSHTML Remote Code Execution Vulnerability CVE-2021-40444
![image](https://github.com/ozergoker/CVE-2021-40444/blob/main/microsoft-office-hack.jpg)

# How to disable ActiveX controls on an individual system ?

# 1. To disable installing ActiveX controls in Internet Explorer in all zones, paste the following into a text file and save it with the .reg file extension:

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CurrentVersion\Internet Settings\Zones\0]
"1001"=dword:00000003
"1004"=dword:00000003

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CurrentVersion\Internet Settings\Zones\1]
"1001"=dword:00000003
"1004"=dword:00000003

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CurrentVersion\Internet Settings\Zones\2]
"1001"=dword:00000003
"1004"=dword:00000003

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CurrentVersion\Internet Settings\Zones\3]
"1001"=dword:00000003
"1004"=dword:00000003

# 2. Double-click the .reg file to apply it to your Policy hive.

# 3. Reboot the system to ensure the new configuration is applied.

# References

https://msrc.microsoft.com/update-guide/vulnerability/CVE-2021-40444

#CVE-2021-40444
