---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: SmbShare
Module Guid: 3AF1699D-CC54-4E54-81CF-28D2DF5CCE0A
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390827
Help Version: 5.0.1.1
Locale: en-US
title: SmbShare
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: D4DCA601-168D-4943-9778-1975F870BAA9
---

# SmbShare Module
## Description
This reference provides cmdlet descriptions and syntax for all Server Message Block (SMB) Share-specific cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## SmbShare Cmdlets
### [Block-SmbShareAccess](./block-smbshareaccess.md)
Adds a deny ACE for a trustee to the security descriptor of the SMB share.

### [Close-SmbOpenFile](./close-smbopenfile.md)
Closes a file that is open by one of the clients of the SMB server.

### [Close-SmbSession](./close-smbsession.md)
Ends forcibly the SMB session.

### [Disable-SmbDelegation](./disable-smbdelegation.md)
Disables a constrained delegation authorization for an SMB client and server.

### [Enable-SmbDelegation](./enable-smbdelegation.md)
Enables a constrained delegation authorization for an SMB client and server.

### [Get-SmbBandwidthLimit](./get-smbbandwidthlimit.md)
Gets the list of SMB bandwidth caps for each traffic category.

### [Get-SmbClientConfiguration](./get-smbclientconfiguration.md)
Retrieves the SMB client configuration.

### [Get-SmbClientNetworkInterface](./get-smbclientnetworkinterface.md)
Retrieves the network interfaces used by the SMB client.

### [Get-SmbConnection](./get-smbconnection.md)
Retrieves the connections established from the SMB client to the SMB servers.

### [Get-SmbDelegation](./get-smbdelegation.md)
Gets the constrained delegation authorizations for an SMB client.

### [Get-SmbMapping](./get-smbmapping.md)
Retrieves the SMB client directory mappings created for a server.

### [Get-SmbMultichannelConnection](./get-smbmultichannelconnection.md)
Retrieves the SMB connections made between the SMB client network interfaces and the SMB server network interfaces.

### [Get-SmbMultichannelConstraint](./get-smbmultichannelconstraint.md)
Retrieves the constraints that define how the SMB client uses network interfaces to connect to the servers.

### [Get-SmbOpenFile](./get-smbopenfile.md)
Retrieves basic information about the files that are open on behalf of the clients of the SMB server.

### [Get-SmbServerConfiguration](./get-smbserverconfiguration.md)
Retrieves the SMB server configuration.

### [Get-SmbServerNetworkInterface](./get-smbservernetworkinterface.md)
Retrieves the network interfaces used by the SMB server.

### [Get-SmbSession](./get-smbsession.md)
Retrieves information about the SMB sessions that are currently established between the SMB server and the associated clients.

### [Get-SmbShare](./get-smbshare.md)
Retrieves the SMB shares on the computer.

### [Get-SmbShareAccess](./get-smbshareaccess.md)
Retrieves the ACL of the SMB share.

### [Grant-SmbShareAccess](./grant-smbshareaccess.md)
Adds an allow ACE for a trustee to the security descriptor of the SMB share.

### [New-SmbMapping](./new-smbmapping.md)
Creates an SMB mapping.

### [New-SmbMultichannelConstraint](./new-smbmultichannelconstraint.md)
Creates an SMB multi-channel constraint for the specified server.

### [New-SmbShare](./new-smbshare.md)
Creates an SMB share.

### [Remove-SmbBandwidthLimit](./remove-smbbandwidthlimit.md)
Removes SMB bandwidth caps.

### [Remove-SmbMapping](./remove-smbmapping.md)
Removes the SMB mapping to an SMB share.

### [Remove-SmbMultichannelConstraint](./remove-smbmultichannelconstraint.md)
Removes SMB multi-channel constraints.

### [Remove-SmbShare](./remove-smbshare.md)
Deletes the specified SMB shares.

### [Revoke-SmbShareAccess](./revoke-smbshareaccess.md)
Removes all of the allow ACEs for a trustee from the security descriptor of the SMB share.

### [Set-SmbBandwidthLimit](./set-smbbandwidthlimit.md)
Adds an SMB bandwidth cap.

### [Set-SmbClientConfiguration](./set-smbclientconfiguration.md)
Sets the SMB client configuration.

### [Set-SmbPathAcl](./set-smbpathacl.md)
Sets the ACL for the file system folder to match the ACL used by an SMB share.

### [Set-SmbServerConfiguration](./set-smbserverconfiguration.md)
Sets the SMB Service configuration.

### [Set-SmbShare](./set-smbshare.md)
Modifies the properties of the SMB share.

### [Unblock-SmbShareAccess](./unblock-smbshareaccess.md)
Removes all of the deny ACEs for the trustee from the security descriptor of the SMB share.

### [Update-SmbMultichannelConnection](./update-smbmultichannelconnection.md)
Forces the SMB client to update the multi-channel-related information.



