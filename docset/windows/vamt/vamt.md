---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: VAMT
Module Guid: C04E5406-950F-4CB4-9C5D-3E8C952214E6
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390841
Help Version: 5.0.0.1
Locale: en-US
title: VAMT
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 38E37D22-F0CF-4EBC-8E1D-8F75A0376C6A
---

# VAMT Module
## Description
Enables network administrators and other IT professionals to automate and centrally manage the volume and retail-activation process for Windows, Microsoft Office, and select other Microsoft products. It can manage volume activation using Multiple Activation Keys (MAKs) or the Windows Key Management Service (KMS). For more information about VAMT, see the [Volume Activation Management Tool Technical Reference](http://go.microsoft.com/fwlink/?LinkId=214550).

## VAMT Cmdlets
### [Add-VamtProductKey](./add-vamtproductkey.md)
Adds the user-specified product key to a VAMT database.

### [Export-VamtData](./export-vamtdata.md)
Exports product data and product-key data from a VAMT database to a portable .cilx file.

### [Find-VamtManagedMachine](./find-vamtmanagedmachine.md)
Performs VAMT discovery operations.

### [Get-VamtConfirmationId](./get-vamtconfirmationid.md)
Acquires confirmation IDs (CIDs) from the Microsoft licensing servers during proxy activation.

### [Get-VamtProduct](./get-vamtproduct.md)
Retrieves the record of a product or list of products from a VAMT database.

### [Get-VamtProductKey](./get-vamtproductkey.md)
Retrieves product-key records from a VAMT database.

### [Import-VamtData](./import-vamtdata.md)
Imports the data from a specified .cilx or .cil file into a VAMT database.

### [Initialize-VamtData](./initialize-vamtdata.md)
Initializes the VAMT database and removes all the data.

### [Install-VamtConfirmationId](./install-vamtconfirmationid.md)
Installs Confirmation IDs (CID) acquired from Microsoft to the respective computers to complete proxy activation.

### [Install-VamtProductActivation](./install-vamtproductactivation.md)
Activates products online, using the local computer's Internet connection.

### [Install-VamtProductKey](./install-vamtproductkey.md)
Installs the specified product key on a product or a group of products.

### [Update-VamtProduct](./update-vamtproduct.md)
Updates the VAMT database by querying the computers for their current status.



