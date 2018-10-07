---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: WindowsServerBackup
Module Guid: D27A5D7A-8B1D-4B0A-809D-65EF33EE2F2D
Download Help Link: http://go.microsoft.com/fwlink/?LinkId=285580
Help Version: 4.0.4.1
Locale: en-US
title: WindowsServerBackup
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/27/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 0F8EB40C-4481-4DA7-9D60-62847E2BD367
---

# WindowsServerBackup Module
## Description
This reference provides cmdlet descriptions and syntax for all Windows Server Backup cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## WindowsServerBackup Cmdlets
### [Add-WBBackupTarget](./add-wbbackuptarget.md)
Adds a backup target to a backup policy.

### [Add-WBBareMetalRecovery](./add-wbbaremetalrecovery.md)
Adds items to a backup policy so that backups that use the policy can perform bare metal recoveries.

### [Add-WBFileSpec](./add-wbfilespec.md)
Adds a backup file specification to a backup policy.

### [Add-WBSystemState](./add-wbsystemstate.md)
Adds the system state components to the backup policy.

### [Add-WBVirtualMachine](./add-wbvirtualmachine.md)
Adds a list of virtual machines to the backup policy.

### [Add-WBVolume](./add-wbvolume.md)
Adds the list of source volumes to the backup policy.

### [Get-WBBackupSet](./get-wbbackupset.md)
Gets backups for a server from a location that you specify.

### [Get-WBBackupTarget](./get-wbbackuptarget.md)
Gets backup storage locations that you specified as part of a backup policy.

### [Get-WBBackupVolumeBrowsePath](./get-wbbackupvolumebrowsepath.md)
Mounts a volume inside a backup so that you can browse the files on the volume.

### [Get-WBBareMetalRecovery](./get-wbbaremetalrecovery.md)
Gets a Boolean value that indicates whether or not a backup policy can perform bare metal recoveries from backups.

### [Get-WBDisk](./get-wbdisk.md)
Gets a list of internal and external disks that are online for the local computer.

### [Get-WBFileSpec](./get-wbfilespec.md)
Gets the list of backup file specifications associated with a backup policy.

### [Get-WBJob](./get-wbjob.md)
Gets the current backup operation.

### [Get-WBPerformanceConfiguration](./get-wbperformanceconfiguration.md)
Gets the current volume backup performance settings.

### [Get-WBPolicy](./get-wbpolicy.md)
Gets the current backup policy for the computer.

### [Get-WBSchedule](./get-wbschedule.md)
Gets the current schedule for backups.

### [Get-WBSummary](./get-wbsummary.md)
Gets the history of backup operations on the computer.

### [Get-WBSystemState](./get-wbsystemstate.md)
Gets a Boolean value that indicates whether system state recovery was added to the backup policy.

### [Get-WBVirtualMachine](./get-wbvirtualmachine.md)
Gets all virtual machines and components from the backup policy.

### [Get-WBVolume](./get-wbvolume.md)
Gets a list of volumes.

### [Get-WBVssBackupOption](./get-wbvssbackupoption.md)
Gets a VSS setting from the backup policy.

### [New-WBBackupTarget](./new-wbbackuptarget.md)
Creates a backup target object.

### [New-WBFileSpec](./new-wbfilespec.md)
Creates a backup file specification.

### [New-WBPolicy](./new-wbpolicy.md)
Creates a backup policy object.

### [Remove-WBBackupSet](./remove-wbbackupset.md)
Removes backups from a target catalog, a system catalog, or both.

### [Remove-WBBackupTarget](./remove-wbbackuptarget.md)
Removes backup storage locations from a backup policy.

### [Remove-WBBareMetalRecovery](./remove-wbbaremetalrecovery.md)
Removes a request to include items that implement bare metal recovery from the current backup policy.

### [Remove-WBCatalog](./remove-wbcatalog.md)
Removes the backup catalog from the local computer.

### [Remove-WBFileSpec](./remove-wbfilespec.md)
Removes a backup file specification from a backup policy.

### [Remove-WBPolicy](./remove-wbpolicy.md)
Removes the backup policy.

### [Remove-WBSystemState](./remove-wbsystemstate.md)
Removes the system state components from the backup policy.

### [Remove-WBVirtualMachine](./remove-wbvirtualmachine.md)
Removes the list of virtual machines from the backup policy.

### [Remove-WBVolume](./remove-wbvolume.md)
Removes the volume from the backup policy.

### [Restore-WBCatalog](./restore-wbcatalog.md)
Restores a backup catalog for the local computer from a storage location.

### [Resume-WBBackup](./resume-wbbackup.md)
Resumes a backup operation to a removable device after you add media to the device.

### [Resume-WBVolumeRecovery](./resume-wbvolumerecovery.md)
Resumes a volume recovery operation from a removable device and specific media.

### [Set-WBPerformanceConfiguration](./set-wbperformanceconfiguration.md)
Sets the current volume backup performance settings.

### [Set-WBPolicy](./set-wbpolicy.md)
Sets the backup policy for scheduled backups.

### [Set-WBSchedule](./set-wbschedule.md)
Sets the current schedule for backups.

### [Set-WBVssBackupOption](./set-wbvssbackupoption.md)
Sets a value that determines the VSS setting in the backup policy.

### [Start-WBApplicationRecovery](./start-wbapplicationrecovery.md)
Starts an application recovery operation.

### [Start-WBBackup](./start-wbbackup.md)
Starts a one-time backup operation.

### [Start-WBFileRecovery](./start-wbfilerecovery.md)
Starts a file recovery operation.

### [Start-WBHyperVRecovery](./start-wbhypervrecovery.md)
Starts recovery of a Hyper-V Server 2016 virtual machine.

### [Start-WBSystemStateRecovery](./start-wbsystemstaterecovery.md)
Starts a system state recovery operation.

### [Start-WBVolumeRecovery](./start-wbvolumerecovery.md)
Starts a volume recovery operation.

### [Stop-WBJob](./stop-wbjob.md)
Stops the current backup or recovery job.



