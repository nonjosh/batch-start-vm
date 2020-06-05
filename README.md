# CMD to Open VM

## Start a VMware Workstation

Change VMware workstation installation directory and `.vmx` file path if needed

```sh
PATH "C:\Program Files (x86)\VMware\VMware Player\"
START vmplayer.exe "D:\VM\2003\Windows Server 2003 Enterprise Edition.vmx"
```

## Start a Virtualbox

Change VM name and start type (`--type gui|sdl|headless|separate]`) if needed

```sh
"C:\Program Files\Oracle\VirtualBox\VBoxManage.exe" startvm "Ubuntu Server" --type separate
```

## Reference:
- https://ibrahim.fandom.com/wiki/SCRIPT:_Start_a_VMware_Workstation_With_a_Batch
