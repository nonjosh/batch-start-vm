# Start a VMware Workstation With a Batch

edit VMware workstation installation directory and .vmx file path if needed

```sh
@echo off

PATH "C:\Program Files (x86)\VMware\VMware Player\"
START vmplayer.exe "D:\VM\2003\Windows Server 2003 Enterprise Edition.vmx"
```

Reference: https://ibrahim.fandom.com/wiki/SCRIPT:_Start_a_VMware_Workstation_With_a_Batch