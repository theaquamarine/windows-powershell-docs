---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: RemoteDesktop
Module Guid: CMDLETS
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390820
Help Version: 5.0.2.0
Locale: en-US
title: RemoteDesktop
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 2DCC3D8E-4155-44FC-AF0E-DC6608D33D8D
---

# RemoteDesktop Module
## Description
This reference provides cmdlet descriptions and syntax for all Remote Desktop Service-specific cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## RemoteDesktop Cmdlets
### [Add-RDServer](./add-rdserver.md)
Adds an RDS server to a Remote Desktop deployment.

### [Add-RDSessionHost](./add-rdsessionhost.md)
Adds one or more RD Session Host servers to a session collection.

### [Add-RDVirtualDesktopToCollection](./add-rdvirtualdesktoptocollection.md)
Adds virtual desktops to a virtual desktop collection.

### [Disable-RDVirtualDesktopADMachineAccountReuse](./disable-rdvirtualdesktopadmachineaccountreuse.md)
Prevents the RD Connection Broker server from reusing existing Active Directory (AD) computer accounts.

### [Disconnect-RDUser](./disconnect-rduser.md)
Disconnects a user from a session that runs on a remote server.

### [Enable-RDVirtualDesktopADMachineAccountReuse](./enable-rdvirtualdesktopadmachineaccountreuse.md)
Configures the RD Connection Broker server to reuse existing AD DS computer accounts.

### [Export-RDPersonalSessionDesktopAssignment](./export-rdpersonalsessiondesktopassignment.md)
Exports the current map of personal session desktops to users.

### [Export-RDPersonalVirtualDesktopAssignment](./export-rdpersonalvirtualdesktopassignment.md)
Exports the current associations between users and personal virtual desktops to a file.

### [Get-RDAvailableApp](./get-rdavailableapp.md)
Gets a list of publishable applications from a collection.

### [Get-RDCertificate](./get-rdcertificate.md)
Gets certificates associated with RDS roles.

### [Get-RDConnectionBrokerHighAvailability](./get-rdconnectionbrokerhighavailability.md)
Gets high availability settings for the RD Connection Broker server in a Remote Desktop deployment.

### [Get-RDDeploymentGatewayConfiguration](./get-rddeploymentgatewayconfiguration.md)
Gets configuration settings for the RD Gateway for a Remote Desktop deployment.

### [Get-RDFileTypeAssociation](./get-rdfiletypeassociation.md)
Displays the file extensions associated with a RemoteApp program.

### [Get-RDLicenseConfiguration](./get-rdlicenseconfiguration.md)
Retrieves the current settings for the RD Licensing server and the licensing mode of the Remote Desktop deployment.

### [Get-RDPersonalSessionDesktopAssignment](./get-rdpersonalsessiondesktopassignment.md)
Gets personal session desktop assignments.

### [Get-RDPersonalVirtualDesktopAssignment](./get-rdpersonalvirtualdesktopassignment.md)
Retrieves a list of personal virtual desktops and associated user accounts.

### [Get-RDPersonalVirtualDesktopPatchSchedule](./get-rdpersonalvirtualdesktoppatchschedule.md)
Gets a patch schedule for a virtual desktop.

### [Get-RDRemoteApp](./get-rdremoteapp.md)
Gets RemoteApp programs in a Remote Desktop deployment.

### [Get-RDRemoteDesktop](./get-rdremotedesktop.md)
Gets published Remote Desktop connections.

### [Get-RDServer](./get-rdserver.md)
Gets RDS servers in a Remote Desktop deployment.

### [Get-RDSessionCollection](./get-rdsessioncollection.md)
Gets session collections in a Remote Desktop deployment.

### [Get-RDSessionCollectionConfiguration](./get-rdsessioncollectionconfiguration.md)
Gets configuration information for a session collection.

### [Get-RDSessionHost](./get-rdsessionhost.md)
Gets a list of RD Session Host servers in a session collection.

### [Get-RDUserSession](./get-rdusersession.md)
Gets a list of all user sessions in a collection or in a Remote Desktop deployment.

### [Get-RDVirtualDesktop](./get-rdvirtualdesktop.md)
Gets a list of virtual desktops in the remote desktop deployment.

### [Get-RDVirtualDesktopCollection](./get-rdvirtualdesktopcollection.md)
Gets a list of virtual desktop collections in a remote desktop deployment.

### [Get-RDVirtualDesktopCollectionConfiguration](./get-rdvirtualdesktopcollectionconfiguration.md)
Gets configuration details of a virtual desktop collection.

### [Get-RDVirtualDesktopCollectionJobStatus](./get-rdvirtualdesktopcollectionjobstatus.md)
Gets the status of a job on a virtual desktop collection.

### [Get-RDVirtualDesktopConcurrency](./get-rdvirtualdesktopconcurrency.md)
Gets the number of virtual desktops that RDS can create in parallel.

### [Get-RDVirtualDesktopIdleCount](./get-rdvirtualdesktopidlecount.md)
Gets the number of idle virtual desktops on hosts.

### [Get-RDVirtualDesktopTemplateExportPath](./get-rdvirtualdesktoptemplateexportpath.md)
Gets the export path setting of the virtual desktop template.

### [Get-RDWorkspace](./get-rdworkspace.md)
Gets the workspace name for a Remote Desktop deployment.

### [Grant-RDOUAccess](./grant-rdouaccess.md)
Grants the Remote Desktop Connection Broker server access to one or more organizational units in a given domain of Active Directory Domain Services.

### [Import-RDPersonalSessionDesktopAssignment](./import-rdpersonalsessiondesktopassignment.md)
Imports a map of personal session desktops to users.

### [Import-RDPersonalVirtualDesktopAssignment](./import-rdpersonalvirtualdesktopassignment.md)
Imports associations between user accounts and personal virtual desktops from a text file.

### [Invoke-RDUserLogoff](./invoke-rduserlogoff.md)
Ends a user session and closes all running applications.

### [Move-RDVirtualDesktop](./move-rdvirtualdesktop.md)
Moves a virtual desktop to a new Remote Desktop Virtualization Host (RD Virtualization Host) server.

### [New-RDCertificate](./new-rdcertificate.md)
Creates a certificate for an RDS role.

### [New-RDPersonalVirtualDesktopPatchSchedule](./new-rdpersonalvirtualdesktoppatchschedule.md)
Creates a patch schedule for a personal virtual desktop.

### [New-RDRemoteApp](./new-rdremoteapp.md)
Publishes a RemoteApp program to a Remote Desktop deployment.

### [New-RDSessionCollection](./new-rdsessioncollection.md)
Creates a session collection of RD Session Host servers.

### [New-RDSessionDeployment](./new-rdsessiondeployment.md)
Installs the required role services for session-based desktop deployment.

### [New-RDVirtualDesktopCollection](./new-rdvirtualdesktopcollection.md)
Creates a virtual desktop collection.

### [New-RDVirtualDesktopDeployment](./new-rdvirtualdesktopdeployment.md)
Installs role services for Virtual Desktop Infrastructure.

### [Remove-RDDatabaseConnectionString](./remove-rddatabaseconnectionstring.md)
Removes the secondary database connection string for the shared database server in a high availability environment configuration.

### [Remove-RDPersonalSessionDesktopAssignment](./remove-rdpersonalsessiondesktopassignment.md)
Removes the association between a personal session desktop assignment and a user.

### [Remove-RDPersonalVirtualDesktopAssignment](./remove-rdpersonalvirtualdesktopassignment.md)
Removes the association between a personal virtual desktop and a user.

### [Remove-RDPersonalVirtualDesktopPatchSchedule](./remove-rdpersonalvirtualdesktoppatchschedule.md)
Removes a patch schedule from a personal virtual desktop.

### [Remove-RDRemoteApp](./remove-rdremoteapp.md)
Removes a RemoteApp program.

### [Remove-RDServer](./remove-rdserver.md)
Removes a server from a Remote Desktop deployment.

### [Remove-RDSessionCollection](./remove-rdsessioncollection.md)
Removes a session collection from a Remote Desktop deployment.

### [Remove-RDSessionHost](./remove-rdsessionhost.md)
Removes one or more RD Session Host servers from a session collection.

### [Remove-RDVirtualDesktopCollection](./remove-rdvirtualdesktopcollection.md)
Removes a virtual desktop collection.

### [Remove-RDVirtualDesktopFromCollection](./remove-rdvirtualdesktopfromcollection.md)
Removes virtual desktops from a virtual desktop collection.

### [Send-RDUserMessage](./send-rdusermessage.md)
Sends a system message to a specified user session.

### [Set-RDActiveManagementServer](./set-rdactivemanagementserver.md)
Sets the active Remote Desktop Connection Broker  server, or management server, in a remote desktop deployment.

### [Set-RDCertificate](./set-rdcertificate.md)
Imports and secures a certificate to use with an RDS role.

### [Set-RDClientAccessName](./set-rdclientaccessname.md)
Sets a DNS name that clients use to connect to a Remote Desktop deployment.

### [Set-RDConnectionBrokerHighAvailability](./set-rdconnectionbrokerhighavailability.md)
Sets high availability settings for RD Connection Broker servers for a Remote Desktop deployment.

### [Set-RDDatabaseConnectionString](./set-rddatabaseconnectionstring.md)
Configures the database connection string for the database server used in a high availability environment.

### [Set-RDDeploymentGatewayConfiguration](./set-rddeploymentgatewayconfiguration.md)
Specifies settings for the RD Gateway server for a Remote Desktop deployment.

### [Set-RDFileTypeAssociation](./set-rdfiletypeassociation.md)
Changes the file type association of a RemoteApp program in a Remote Desktop deployment.

### [Set-RDLicenseConfiguration](./set-rdlicenseconfiguration.md)
Defines settings for the RD Licensing server and the licensing mode of the Remote Desktop deployment.

### [Set-RDPersonalSessionDesktopAssignment](./set-rdpersonalsessiondesktopassignment.md)
Associates a personal session desktop assignment with a user.

### [Set-RDPersonalVirtualDesktopAssignment](./set-rdpersonalvirtualdesktopassignment.md)
Creates an association between a personal virtual desktop and a user account.

### [Set-RDPersonalVirtualDesktopPatchSchedule](./set-rdpersonalvirtualdesktoppatchschedule.md)
Changes patch schedule settings for a personal virtual desktop.

### [Set-RDRemoteApp](./set-rdremoteapp.md)
Modifies configuration settings for a RemoteApp program.

### [Set-RDRemoteDesktop](./set-rdremotedesktop.md)
Changes whether to publish a Remote Desktop to a collection.

### [Set-RDSessionCollectionConfiguration](./set-rdsessioncollectionconfiguration.md)
Modifies configuration options for an existing session collection.

### [Set-RDSessionHost](./set-rdsessionhost.md)
Configures one or more RD Session Host servers in a session collection.

### [Set-RDVirtualDesktopCollectionConfiguration](./set-rdvirtualdesktopcollectionconfiguration.md)
Changes configuration settings for a virtual desktop collection.

### [Set-RDVirtualDesktopConcurrency](./set-rdvirtualdesktopconcurrency.md)
Sets the number of virtual desktops that RDS can create in parallel.

### [Set-RDVirtualDesktopIdleCount](./set-rdvirtualdesktopidlecount.md)
Sets the maximum number of idle virtual desktops on host servers.

### [Set-RDVirtualDesktopTemplateExportPath](./set-rdvirtualdesktoptemplateexportpath.md)
Sets the export path for virtual desktop templates.

### [Set-RDWorkspace](./set-rdworkspace.md)
Assigns a workspace name for a Remote Desktop deployment.

### [Stop-RDVirtualDesktopCollectionJob](./stop-rdvirtualdesktopcollectionjob.md)
Stops a job on a virtual desktop collection.

### [Test-RDOUAccess](./test-rdouaccess.md)
Verifies that the Remote Desktop Connection Broker  server can access an Active Directory Domain Services  organizational unit.

### [Test-RDVirtualDesktopADMachineAccountReuse](./test-rdvirtualdesktopadmachineaccountreuse.md)
Detects whether the RD Connection Broker server is configured to reuse existing AD DS computer accounts.

### [Update-RDVirtualDesktopCollection](./update-rdvirtualdesktopcollection.md)
Associates a virtual desktop collection with a new virtual desktop template.


