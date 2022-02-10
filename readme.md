# NSCC Student EndPoint Manager Hybrid Lab

## On Prem Setup
This lab requires a local HyperV server with:
 - 32Gb Ram
 - 300Gb Storage
 - one 172 connected nic
 - two private nics
Currently provisioned as a nested host on ESXi (172.16.144.100).
 - Bonus: Shared Drive (connected to each Lab VM) for easy access to downloads 

## See template - WinServ2019-HyperV
The following configurations have already been completed:
- initial install Windows Server 2019 Datacenter (Desktop Experience)
- KMS Licence Key CB7KF-BWN84-R7R2Y-793K2-8XDDG
- local account u:Administrator p:P@ssw0rd
- VMware Tools
- Windows updates (Feb 2022)
- HyperV Role
- Remote Desktop
- Azure PS Modules
- WinRM Enabled
- Defender FW Disabled

Source: https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/manage/hybrid/server/best-practices/vmware-windows-template

## Install the Lab
1. Extract the current version of the lab (found on shared drive) to C:\LabVMs
2. Run Setup.exe
3. Wait...
4. Launch HyperV Manager and confirm VM creation.
5. Connect to HYD-CM1 to confirm access. 