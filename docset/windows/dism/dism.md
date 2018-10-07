---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: DISM
Module Guid: 389c464d-8b8d-48e9-aafe-6d8a590d6798
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390767
Help Version: 5.0.1.1
Locale: en-US
title: DISM
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/21/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 3DD32417-9E7D-41FE-BB76-8F24D96B835A
---

# DISM Module
## Description
The Deployment Image Servicing and Management (DISM) platform is used to mount and service Windows images before deployment. A subset of DISM commands can be used on online Windows images. You can use DISM tools to mount, and get information about, Windows image (.wim) files or virtual hard disks (.vhd or .vhdx). You can also use it to install, uninstall, configure, and update Windows features, packages, and drivers in a Windows image or to change the edition of a Windows image.

This topic introduces the DISM cmdlets available in the DISM PowerShell module. This module is available in Windows 8.1 and Windows Server 2012 R2. On other supported operating systems, you can install the DISM module from the [Windows Assessment and Deployment Kit (Windows ADK)](http://go.microsoft.com/fwlink/?LinkId=206587). For more information about how to use the DISM PowerShell module installed with the ADK, see [How to Use DISM in Windows PowerShell](http://go.microsoft.com/fwlink/?LinkId=239927).

For Windows 8.1 and Windows Server 2012 R2, Windows PowerShell 4.0 is included in the installation. For other supported versions of Windows and Windows Server, (including Windows 8, Windows 7 SP1, Windows Server 2012, and Windows Server 2008 R2 SP1), you must install Windows Management Framework 4.0. You can download and install [Windows Management Framework 4.0](http://go.microsoft.com/fwlink/?LinkId=293881) from the Microsoft Download Center.

The DISM platform also includes a command-line tool, DISM.exe, and the [DISM API](http://go.microsoft.com/fwlink/?LinkID=237611). The command-line tool is available in the [Windows Assessment and Deployment Kit (Windows ADK)](http://go.microsoft.com/fwlink/?LinkId=206587) and includes additional functionality that supports servicing commands for international settings.

You can check for errors when running DISM cmdlets by checking if the $?. If set to True the last operation succeeded. If False the last operation failed. The $LASTEXITCODE contains the exit code of the last Win32 executable run. For example, to check that the **Get-WindowsImage** cmdlet fails to get information about the Windows image contained in the file, E:\images\c.wim, type the following: 

```
try
{
       
    Get-WindowsImage -ImagePath E:\images\c.wim
}
catch
{
    $message = "TRAPPED: {0}: '{1}'" -f ($_.Exception.GetType().FullName), ($_.Exception.Message)
    Write-host $message
}

```

For more information about error handling, see the [about_Try_Catch_Finally](http://go.microsoft.com/fwlink/p/?LinkID=317390).

## DISM Cmdlets
### [Add-AppxProvisionedPackage](./add-appxprovisionedpackage.md)
Adds an app package (.appx) that will install for each new user to a Windows image.

### [Add-WindowsCapability](./add-windowscapability.md)
Installs a Windows capability package on the specified operating system image.

### [Add-WindowsDriver](./add-windowsdriver.md)
Adds a driver to an offline Windows image.

### [Add-WindowsImage](./add-windowsimage.md)
Adds an additional image to an existing image (.wim) file.

### [Add-WindowsPackage](./add-windowspackage.md)
Adds a single .cab or .msu file to a Windows image.

### [Clear-WindowsCorruptMountPoint](./clear-windowscorruptmountpoint.md)
Deletes all of the resources associated with a mounted image that has been corrupted.

### [Disable-WindowsOptionalFeature](./disable-windowsoptionalfeature.md)
Disables a feature in a Windows image.

### [Dismount-WindowsImage](./dismount-windowsimage.md)
Dismounts a Windows image from the directory it is mapped to.

### [Enable-WindowsOptionalFeature](./enable-windowsoptionalfeature.md)
Enables a feature in a Windows image.

### [Expand-WindowsCustomDataImage](./expand-windowscustomdataimage.md)
Expands a custom data image.

### [Expand-WindowsImage](./expand-windowsimage.md)
Applies an image to a specified location.

### [Export-WindowsDriver](./export-windowsdriver.md)
Exports all third-party drivers from a Windows image to a destination folder.

### [Export-WindowsImage](./export-windowsimage.md)
Exports a copy of the specified image to another image file.

### [Get-AppxProvisionedPackage](./get-appxprovisionedpackage.md)
Gets information about app packages (.appx) in an image that will be installed for each new user.

### [Get-WIMBootEntry](./get-wimbootentry.md)
Displays the Windows image file boot (WIMBoot) configuration entries for a specified disk volume.

### [Get-WindowsCapability](./get-windowscapability.md)
Gets Windows capabilities for an image or a running operating system.

### [Get-WindowsDriver](./get-windowsdriver.md)
Displays information about drivers in a Windows image.

### [Get-WindowsEdition](./get-windowsedition.md)
Gets edition information about a Windows image.

### [Get-WindowsImage](./get-windowsimage.md)
Gets information about a Windows image in a WIM or VHD file.

### [Get-WindowsImageContent](./get-windowsimagecontent.md)
Displays a list of the files and folders in a specified image.

### [Get-WindowsOptionalFeature](./get-windowsoptionalfeature.md)
Gets information about optional features in a Windows image.

### [Get-WindowsPackage](./get-windowspackage.md)
Gets information about packages in a Windows image.

### [Mount-WindowsImage](./mount-windowsimage.md)
Mounts a Windows image in a WIM or VHD file to a directory on the local computer.

### [New-WindowsCustomImage](./new-windowscustomimage.md)
Captures an image of customized or serviced Windows components on a Windows Image File Boot (WIMBoot) configured device.

### [New-WindowsImage](./new-windowsimage.md)
Captures an image of a drive to a new WIM file.

### [Optimize-WindowsImage](./optimize-windowsimage.md)
Configures a Windows image with specified optimizations.

### [Remove-AppxProvisionedPackage](./remove-appxprovisionedpackage.md)
Removes an app package (.appx) from a Windows image.

### [Remove-WindowsCapability](./remove-windowscapability.md)
Uninstalls a Windows capability package from an image.

### [Remove-WindowsDriver](./remove-windowsdriver.md)
Removes a driver from an offline Windows image.

### [Remove-WindowsImage](./remove-windowsimage.md)
Deletes the specified volume image from a WIM file that has multiple volume images.

### [Remove-WindowsPackage](./remove-windowspackage.md)
Removes a package from a Windows image.

### [Repair-WindowsImage](./repair-windowsimage.md)
Repairs a Windows image in a WIM or VHD file.

### [Save-WindowsImage](./save-windowsimage.md)
Applies changes made to a mounted image to its WIM or VHD file.

### [Set-AppXProvisionedDataFile](./set-appxprovisioneddatafile.md)
Adds custom data into the specified app (.appx) package that has been provisioned in a Windows image.

### [Set-WindowsEdition](./set-windowsedition.md)
Changes a Windows image to a higher edition.

### [Set-WindowsProductKey](./set-windowsproductkey.md)
Sets the product key for the Windows image.

### [Split-WindowsImage](./split-windowsimage.md)
Splits an existing .wim file into multiple read-only split .wim files.

### [Update-WIMBootEntry](./update-wimbootentry.md)
Updates the Windows image file boot (WIMBoot) configuration entry, associated with either the specified data source ID, the renamed image file path or the moved image file path.

### [Use-WindowsUnattend](./use-windowsunattend.md)
Applies an unattended answer file to a Windows image.




