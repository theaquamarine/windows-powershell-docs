---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: BootEventCollector
Module Guid: 7E4C6113-1789-4C2D-ABAA-BEA1EF5C62E8
Download Help Link: http://go.microsoft.com/fwlink/?LinkId=518772
Help Version: 5.0.0.2
Locale: en-US
title: BootEventCollector
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 394B60AC-9516-494B-86D7-50F767321820
---

# BootEventCollector Module
## Description
The Boot Event Collector module contains cmdlets to help you administer Boot Event Collector tasks in Windows Server 2016 Technical Preview.

## BootEventCollector Cmdlets
### [Checkpoint-SbecActiveConfig](./checkpoint-sbecactiveconfig.md)
Creates a configuration checkpoint.

### [Clear-SbecProviderCache](./clear-sbecprovidercache.md)
Clears the provider cache.

### [Disable-SbecAutologger](./disable-sbecautologger.md)
Disables the forwarding of events to the Setup and Boot Event Collector in the AutoLogger settings.

### [Disable-SbecBcd](./disable-sbecbcd.md)
Disables the event forwarding mode in BCD settings.

### [Enable-SbecAutologger](./enable-sbecautologger.md)
Enables the forwarding of the events to the Setup and Boot Event Collector in the AutoLogger settings.

### [Enable-SbecBcd](./enable-sbecbcd.md)
Enables and configures the event forwarding mode in the BCD settings.

### [Enable-SbecBootImage](./enable-sbecbootimage.md)
Enables AutoLogger settings in offline WinPE Setup images.

### [Enable-SbecWdsBcd](./enable-sbecwdsbcd.md)
Enables the BCD settings in the offline boot images imported into the WDS server.

### [Get-SbecActiveConfig](./get-sbecactiveconfig.md)
Gets the current active configuration from the running Setup and Boot Event Collector.

### [Get-SbecBackupConfig](./get-sbecbackupconfig.md)
Get the backup configuration files that are available to restore.

### [Get-SbecDestination](./get-sbecdestination.md)
Get destination data files.

### [Get-SbecForwarding](./get-sbecforwarding.md)
Gets the current connections and how data is forwarded.

### [Get-SbecHistory](./get-sbechistory.md)
Gets the recent history of changes in connection status.

### [Get-SbecLocalizedMessage](./get-sbeclocalizedmessage.md)
Gets a localized message string.

### [Get-SbecLogSession](./get-sbeclogsession.md)
Gets the running log sessions.

### [Get-SbecTraceProviders](./get-sbectraceproviders.md)
Gets the ETW trace providers.

### [New-SbecUnattendFragment](./new-sbecunattendfragment.md)
Creates a fragment for Unattend.xml with post-install commands.

### [Redo-SbecActiveConfig](./redo-sbecactiveconfig.md)
Redoes a change to the current active configuration.

### [Restore-SbecBackupConfig](./restore-sbecbackupconfig.md)
Restores a configuration from a backup file.

### [Save-SbecInstance](./save-sbecinstance.md)
Writes in-memory buffers to disk.

### [Save-SbecLogSession](./save-sbeclogsession.md)
Flushes the buffers in a log session to disk.

### [Set-SbecActiveConfig](./set-sbecactiveconfig.md)
Sets the new active configuration for the running Setup and Boot Event Collector.

### [Set-SbecLogSession](./set-sbeclogsession.md)
Updates the settings for a log session.

### [Start-SbecInstance](./start-sbecinstance.md)
Starts the Setup and Boot Event Collector service.

### [Start-SbecLogSession](./start-sbeclogsession.md)
Starts an ETW log session.

### [Start-SbecNtKernelLogSession](./start-sbecntkernellogsession.md)
Starts an NT Kernel Logger log session with forwarding of events to the Collector.

### [Start-SbecSimpleLogSession](./start-sbecsimplelogsession.md)
Starts a log session with the forwarding of events to the Collector.

### [Stop-SbecInstance](./stop-sbecinstance.md)
Stops the Setup and Boot Event Collector.

### [Stop-SbecLogSession](./stop-sbeclogsession.md)
Stops a log session.

### [Test-SbecActiveConfig](./test-sbecactiveconfig.md)
Tests the active Boot Event Collector configuration.

### [Test-SbecConfig](./test-sbecconfig.md)
Validates a configuration.

### [Undo-SbecActiveConfig](./undo-sbecactiveconfig.md)
Reverts a change to the active configuration.




