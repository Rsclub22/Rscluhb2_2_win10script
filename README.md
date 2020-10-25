# win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.

##Install

# One Comand Install(make sure tu run wwith admin & powershell):

powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/Rsclub22/win10script/master/win10debloat.ps1')"

#Manual Install(make sure tu run wwith admin & powershell):

- Download Powershell script  (Win10debloat.ps1)
- cd with a powershell into the Download Directory
- type .\win10debloat.ps1


## My Additions

- Enable Cortana back
- Disable Fastboot
- Dark Mode
- Feature Updates get availible
- One Command to launch and run
- Chocolatey Install
- O&O Shutup10 CFG and Run
- Added Install Programs
- Added Debloat Microsoft Store Apps
- some other stuff ...

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip

Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
