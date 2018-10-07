---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: Storage
Module Guid: 41486F7D-842F-40F1-ACE4-8405F9C2ED9B
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390832
Help Version: 5.0.0.2
Locale: en-US
title: Storage
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: DF62E18F-255B-4AD9-A6B8-05DA00853242
---

# Storage Module
## Description
This reference provides cmdlet descriptions and syntax for all Windows Storage Management-specific cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## Storage Cmdlets
### [Add-InitiatorIdToMaskingSet](./add-initiatoridtomaskingset.md)
Adds an initiator ID to an existing masking set, granting the host associated with the initiator ID access to the virtual disk and target port resources defined in the masking set.

### [Add-PartitionAccessPath](./add-partitionaccesspath.md)
Adds an access path such as a drive letter or folder to a partition.

### [Add-PhysicalDisk](./add-physicaldisk.md)
Adds a physical disk to the specified storage pool or manually assigns a physical disk to a specific virtual disk.

### [Add-TargetPortToMaskingSet](./add-targetporttomaskingset.md)
Adds one or more target ports to a specified masking set, allowing a connection between the target ports, and any virtual disks and initiator IDs that the masking set contains.

### [Add-VirtualDiskToMaskingSet](./add-virtualdisktomaskingset.md)
Adds a virtual disk to a specified masking set and grants access to the virtual disk to all initiator IDs defined in the masking set.

### [Block-FileShareAccess](./block-fileshareaccess.md)
Blocks access to a file share.

### [Clear-Disk](./clear-disk.md)
Cleans a disk by removing all partition information and un-initializing it, erasing all data on the disk.

### [Clear-FileStorageTier](./clear-filestoragetier.md)
Unpins a file from the specified storage tier.

### [Connect-VirtualDisk](./connect-virtualdisk.md)
Connects a disconnected virtual disk to the specified computer when using the Windows Storage subsystem.

### [Debug-FileShare](./debug-fileshare.md)
Finds problems with a file share and recommends solutions.

### [Debug-StorageSubSystem](./debug-storagesubsystem.md)
Finds problems with a storage subsystem and recommends solutions.

### [Debug-Volume](./debug-volume.md)
Finds problems with a volume and recommends solutions.

### [Disable-PhysicalDiskIdentification](./disable-physicaldiskidentification.md)
Turns off the identification LED on the specified physical disk.

### [Disable-StorageEnclosureIdentification](./disable-storageenclosureidentification.md)
Turns off the identification LED on a storage enclosure or the slots for individual disks.

### [Disable-StorageHighAvailability](./disable-storagehighavailability.md)
Disables a Storage resource.

### [Disable-StorageMaintenanceMode](./disable-storagemaintenancemode.md)
Disables storage maintenance mode on a fault domain.

### [Disconnect-VirtualDisk](./disconnect-virtualdisk.md)
Disconnects a virtual disk from the specified computer, revoking access to the virtual disk.

### [Dismount-DiskImage](./dismount-diskimage.md)
Dismounts a disk image (virtual hard disk or ISO) so that it can no longer be accessed as a disk.

### [Enable-PhysicalDiskIdentification](./enable-physicaldiskidentification.md)
Enables the identification LED on the specified physical disk.

### [Enable-StorageEnclosureIdentification](./enable-storageenclosureidentification.md)
Enables the identification LED on a storage enclosure or the slots for individual disks.

### [Enable-StorageHighAvailability](./enable-storagehighavailability.md)
Enables a disk to be added to the failover cluster.

### [Enable-StorageMaintenanceMode](./enable-storagemaintenancemode.md)
Enables storage maintenance mode on a device.

### [Format-Volume](./format-volume.md)
Formats one or more existing volumes or a new volume on an existing partition.

### [Get-DedupProperties](./get-dedupproperties.md)
Gets Data Deduplication information.

### [Get-Disk](./get-disk.md)
Gets one or more disks visible to the operating system.

### [Get-DiskImage](./get-diskimage.md)
Gets one or more disk image objects (virtual hard disk or ISO).

### [Get-DiskStorageNodeView](./get-diskstoragenodeview.md)
Gets the view of a disk from a storage node.

### [Get-FileIntegrity](./get-fileintegrity.md)
Gets integrity information for a file on an ReFS volume.

### [Get-FileShare](./get-fileshare.md)
Retrieves file share objects and their properties.

### [Get-FileShareAccessControlEntry](./get-fileshareaccesscontrolentry.md)
Retrieves an access control entry for the share corresponding to a single account.

### [Get-FileStorageTier](./get-filestoragetier.md)
Gets the files assigned to a Storage tier on a volume, and their status.

### [Get-InitiatorId](./get-initiatorid.md)
Gets the InitiatorID objects for the specified iSCSI initiators.

### [Get-InitiatorPort](./get-initiatorport.md)
Gets one or more host bus adapter (HBA) initiator ports.

### [Get-MaskingSet](./get-maskingset.md)
Gets masking sets.

### [Get-OffloadDataTransferSetting](./get-offloaddatatransfersetting.md)
Returns offloaded data transfer (ODX) settings for the specified subsystem.

### [Get-Partition](./get-partition.md)
Returns a list of all partition objects visible on all disks, or optionally a filtered list using specified parameters.

### [Get-PartitionSupportedSize](./get-partitionsupportedsize.md)
Returns information on supported partition sizes for the specified Disk object.

### [Get-PhysicalDisk](./get-physicaldisk.md)
Gets a list of all PhysicalDisk objects visible across any available Storage Management Providers, or optionally a filtered list.

### [Get-PhysicalDiskStorageNodeView](./get-physicaldiskstoragenodeview.md)
Gets the node view of a physical disk.

### [Get-PhysicalExtent](./get-physicalextent.md)
Gets physical allocations for a physical disk, storage tier, or virtual disk.

### [Get-PhysicalExtentAssociation](./get-physicalextentassociation.md)
Gets the physical disk, storage tier, or virtual disk that is associated with a physical extent.

### [Get-ResiliencySetting](./get-resiliencysetting.md)
Gets the resiliency settings (also known as storage layouts) available for creating virtual disks on the specified storage subsystem.

### [Get-StorageAdvancedProperty](./get-storageadvancedproperty.md)
Gets the advanced properties on a storage device.

### [Get-StorageDiagnosticInfo](./get-storagediagnosticinfo.md)
Gets Storage diagnostic information.

### [Get-StorageEnclosure](./get-storageenclosure.md)
Gets storage enclosures.

### [Get-StorageEnclosureStorageNodeView](./get-storageenclosurestoragenodeview.md)
Gets the node view of a Storage enclosure.

### [Get-StorageEnclosureVendorData](./get-storageenclosurevendordata.md)
Gets vendor-specific data for an enclosure.

### [Get-StorageFaultDomain](./get-storagefaultdomain.md)
Gets a Storage fault domain object.

### [Get-StorageFileServer](./get-storagefileserver.md)
Gets a storage file server.

### [Get-StorageFirmwareInformation](./get-storagefirmwareinformation.md)
Gets information about firmware on a storage object.

### [Get-StorageHealthAction](./get-storagehealthaction.md)
Gets health-related system activities.

### [Get-StorageHealthReport](./get-storagehealthreport.md)
Gets a storage health report.

### [Get-StorageHealthSetting](./get-storagehealthsetting.md)
Gets storage health service settings.

### [Get-StorageJob](./get-storagejob.md)
Returns information about long-running Storage module jobs, such as a repair task.

### [Get-StorageNode](./get-storagenode.md)
Gets storage nodes.

### [Get-StoragePool](./get-storagepool.md)
Gets a specific storage pool, or a set of StoragePool objects either from all storage subsystems across all storage providers, or optionally a filtered subset based on specific parameters.

### [Get-StorageProvider](./get-storageprovider.md)
Returns a list of the storage providers available on the local computer.

### [Get-StorageReliabilityCounter](./get-storagereliabilitycounter.md)
Gets storage reliability counters.

### [Get-StorageSetting](./get-storagesetting.md)
Gets a StorageSettings object.

### [Get-StorageSubsystem](./get-storagesubsystem.md)
Gets one or more StorageSubsystem objects.

### [Get-StorageTier](./get-storagetier.md)
Gets storage tiers on Windows Storage subsystems.

### [Get-StorageTierSupportedSize](./get-storagetiersupportedsize.md)
Gets the minimum and maximum possible sizes of a storage tier.

### [Get-SupportedClusterSizes](./get-supportedclustersizes.md)
Gets the supported cluster sizes.

### [Get-SupportedFileSystems](./get-supportedfilesystems.md)
Gets the file system choices for a specified volume.

### [Get-TargetPort](./get-targetport.md)
Returns a TargetPort object associated with a specific port address and connection type.

### [Get-TargetPortal](./get-targetportal.md)
Returns a TargetPortal object.

### [Get-VirtualDisk](./get-virtualdisk.md)
Returns a list of VirtualDisk objects, across all storage pools, across all providers, or optionally a filtered subset based on provided criteria.

### [Get-VirtualDiskSupportedSize](./get-virtualdisksupportedsize.md)
Returns all sizes supported by a storage pool for virtual disk creation based on the specified resiliency setting name.

### [Get-Volume](./get-volume.md)
Gets the specified Volume object, or all Volume objects if no filter is provided.

### [Get-VolumeCorruptionCount](./get-volumecorruptioncount.md)
Gets a count of the file system errors on the NTFS volume.

### [Get-VolumeScrubPolicy](./get-volumescrubpolicy.md)
Gets the status of the volume scrub policy.

### [Grant-FileShareAccess](./grant-fileshareaccess.md)
Grants access to a file share.

### [Hide-VirtualDisk](./hide-virtualdisk.md)
Hides the virtual disk from the host when the Storage Management Provider in use does not support masking sets.

### [Initialize-Disk](./initialize-disk.md)
Initializes a RAW disk for first time use, enabling the disk to be formatted and used to store data.

### [Mount-DiskImage](./mount-diskimage.md)
Mounts a previously created disk image (virtual hard disk or ISO), making it appear as a normal disk.

### [New-FileShare](./new-fileshare.md)
Creates an access point for a remote file share.

### [New-MaskingSet](./new-maskingset.md)
Creates a new masking set.

### [New-Partition](./new-partition.md)
Creates a new partition on an existing Disk object.

### [New-StorageFileServer](./new-storagefileserver.md)
Creates a storage file server.

### [New-StoragePool](./new-storagepool.md)
Creates a new storage pool using a group of physical disks.

### [New-StorageSubsystemVirtualDisk](./new-storagesubsystemvirtualdisk.md)
Allows the creation of a VirtualDisk object on a storage subsystem that does not support creation of storage pools.

### [New-StorageTier](./new-storagetier.md)
Creates a storage tier.

### [New-VirtualDisk](./new-virtualdisk.md)
Creates a new virtual disk in the specified storage pool.

### [New-VirtualDiskClone](./new-virtualdiskclone.md)
Creates a new clone of a specified virtual disk.

### [New-VirtualDiskSnapshot](./new-virtualdisksnapshot.md)
Creates a new snapshot of the specified virtual disk.

### [New-Volume](./new-volume.md)
Creates a volume with the specified file system.

### [Optimize-StoragePool](./optimize-storagepool.md)
Optimizes a Storage pool.

### [Optimize-Volume](./optimize-volume.md)
Optimizes a volume.

### [Register-StorageSubsystem](./register-storagesubsystem.md)
Connects to storage subsystems on a remote computer.

### [Remove-FileShare](./remove-fileshare.md)
Removes a file share.

### [Remove-InitiatorId](./remove-initiatorid.md)
Removes an initiator identifier (ID).

### [Remove-InitiatorIdFromMaskingSet](./remove-initiatoridfrommaskingset.md)
Removes an initiator identifier (ID) from a masking set.

### [Remove-MaskingSet](./remove-maskingset.md)
Removes a masking set.

### [Remove-Partition](./remove-partition.md)
Deletes the specified Partition object on an existing disk and any underlying Volume objects.

### [Remove-PartitionAccessPath](./remove-partitionaccesspath.md)
Removes an access path such as a drive letter or folder from a partition.

### [Remove-PhysicalDisk](./remove-physicaldisk.md)
Removes a physical disk from a specified storage pool.

### [Remove-StorageFileServer](./remove-storagefileserver.md)
Removes a file server.

### [Remove-StorageHealthSetting](./remove-storagehealthsetting.md)
Removes a storage health service setting.

### [Remove-StoragePool](./remove-storagepool.md)
Deletes a storage pool and associated VirtualDisk objects.

### [Remove-StorageTier](./remove-storagetier.md)
Removes storage tiers from a storage pool.

### [Remove-TargetPortFromMaskingSet](./remove-targetportfrommaskingset.md)
Removes a specified target port from a masking set.

### [Remove-VirtualDisk](./remove-virtualdisk.md)
Deletes an existing virtual disk and reclaims the used space for use by other virtual disks in the same storage pool.

### [Remove-VirtualDiskFromMaskingSet](./remove-virtualdiskfrommaskingset.md)
Removes a virtual disk from a specified masking set to block access to the virtual disk by an InitiatorIds object defined in the masking set.

### [Rename-MaskingSet](./rename-maskingset.md)
Renames an existing masking set.

### [Repair-FileIntegrity](./repair-fileintegrity.md)
Repairs a corrupted file on an NTFS or ReFS volume.

### [Repair-VirtualDisk](./repair-virtualdisk.md)
Performs repairs on a virtual disk that is unhealthy.

### [Repair-Volume](./repair-volume.md)
Performs repairs on a volume.

### [Reset-PhysicalDisk](./reset-physicaldisk.md)
Resets the status of a physical disk.

### [Reset-StorageReliabilityCounter](./reset-storagereliabilitycounter.md)
Resets storage reliability counters for a disk.

### [Resize-Partition](./resize-partition.md)
Resizes a partition and the underlying file system.

### [Resize-StorageTier](./resize-storagetier.md)
Increases the size of storage tiers.

### [Resize-VirtualDisk](./resize-virtualdisk.md)
Resizes an existing virtual disk to be larger or smaller.

### [Revoke-FileShareAccess](./revoke-fileshareaccess.md)
Revokes access to a file share.

### [Set-Disk](./set-disk.md)
Takes a Disk object or unique disk identifiers and a set of attributes, and updates the physical disk on the system.

### [Set-FileIntegrity](./set-fileintegrity.md)
Sets integrity for a file on an ReFS volume.

### [Set-FileShare](./set-fileshare.md)
Modifies a file share.

### [Set-FileStorageTier](./set-filestoragetier.md)
Assigns a file to a storage tier.

### [Set-InitiatorPort](./set-initiatorport.md)
Sets properties on the InitiatorPort object.

### [Set-Partition](./set-partition.md)
Sets attributes of a partition, such as active, read-only, and offline states.

### [Set-PhysicalDisk](./set-physicaldisk.md)
Sets attributes on a specific physical disk.

### [Set-ResiliencySetting](./set-resiliencysetting.md)
Modifies the properties of the specified resiliency setting name.

### [Set-StorageFileServer](./set-storagefileserver.md)
Modifies a storage file server.

### [Set-StorageHealthSetting](./set-storagehealthsetting.md)
Modifies a storage health service setting.

### [Set-StoragePool](./set-storagepool.md)
Modifies the properties of the specified storage pool.

### [Set-StorageProvider](./set-storageprovider.md)
Modifies whether to enable the SMP provider cache.

### [Set-StorageSetting](./set-storagesetting.md)
Adjusts or configures current storage settings of the StorageSetting object.

### [Set-StorageSubsystem](./set-storagesubsystem.md)
Modifies the properties of a StorageSubsystem object.

### [Set-StorageTier](./set-storagetier.md)
Modifies a storage tier.

### [Set-VirtualDisk](./set-virtualdisk.md)
Modifies the attributes of an existing virtual disk.

### [Set-Volume](./set-volume.md)
Sets or changes the file system label of an existing volume.

### [Set-VolumeScrubPolicy](./set-volumescrubpolicy.md)
Sets the status of the volume scrub policy.

### [Show-VirtualDisk](./show-virtualdisk.md)
Makes a virtual disk available to a host.

### [Start-StorageDiagnosticLog](./start-storagediagnosticlog.md)
Starts Storage diagnostic logging.

### [Stop-StorageDiagnosticLog](./stop-storagediagnosticlog.md)
Stops a Storage diagnostic log.

### [Stop-StorageJob](./stop-storagejob.md)
Stops storage job.

### [Unblock-FileShareAccess](./unblock-fileshareaccess.md)
Unblocks access to a file share.

### [Unregister-StorageSubsystem](./unregister-storagesubsystem.md)
Disconnects from storage subsystems on a remote computer.

### [Update-Disk](./update-disk.md)
Updates cached information about the specified Disk object only

### [Update-HostStorageCache](./update-hoststoragecache.md)
Initiates an update on the host storage cache to reflect the current status of storage.

### [Update-StorageFirmware](./update-storagefirmware.md)
Updates the firmware on a storage device.

### [Update-StoragePool](./update-storagepool.md)
Updates the metadata of a Windows Server 2012 R2 storage pool.

### [Update-StorageProviderCache](./update-storageprovidercache.md)
Updates the cache of the service for a particular provider and associated child objects.

### [Write-VolumeCache](./write-volumecache.md)
Writes the file system cache to disk.




