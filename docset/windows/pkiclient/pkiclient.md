---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: PKIClient
Module Guid: CMDLETS
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390811
Help Version: 5.0.0.1
Locale: en-US
title: PKIClient
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 8008D3A6-4E97-4977-92F7-795EF45B4A27
---

# PKIClient Module
## Description
This reference provides cmdlet descriptions and syntax for all public key infrastructure (PKI) client-specific cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## PKIClient Cmdlets
### [Add-CertificateEnrollmentPolicyServer](./add-certificateenrollmentpolicyserver.md)
Adds an enrollment policy server to the current user or local system configuration.

### [Export-Certificate](./export-certificate.md)
Exports a certificate from a certificate store into a file.

### [Export-PfxCertificate](./export-pfxcertificate.md)
Exports a certificate or a PFXData object to a Personal Information Exchange (PFX) file.

### [Get-Certificate](./get-certificate.md)
Submits a certificate request to an enrollment server and installs the response or retrieves a certificate for a previously submitted request.

### [Get-CertificateAutoEnrollmentPolicy](./get-certificateautoenrollmentpolicy.md)
Retrieves certificate auto-enrollment policy settings.

### [Get-CertificateEnrollmentPolicyServer](./get-certificateenrollmentpolicyserver.md)
Returns all of the certificate enrollment policy server URL configurations.

### [Get-CertificateNotificationTask](./get-certificatenotificationtask.md)
Returns all registered certificate notification tasks.

### [Get-PfxData](./get-pfxdata.md)
Extracts the content of a Personal Information Exchange (PFX) file into a structure without importing it to certificate store.

### [Import-Certificate](./import-certificate.md)
Imports one or more certificates into a certificate store.

### [Import-PfxCertificate](./import-pfxcertificate.md)
Imports certificates and private keys from a Personal Information Exchange (PFX) file to the destination store.

### [New-CertificateNotificationTask](./new-certificatenotificationtask.md)
Creates a new task in the Task Scheduler that will be triggered when a certificate is replaced, expired, or about to expired.

### [New-SelfSignedCertificate](./new-selfsignedcertificate.md)
Creates a new self-signed certificate for testing purposes.

### [Remove-CertificateEnrollmentPolicyServer](./remove-certificateenrollmentpolicyserver.md)
Removes an enrollment policy server and the URL of the enrollment policy server from the current user or local computer configuration.

### [Remove-CertificateNotificationTask](./remove-certificatenotificationtask.md)
Removes a certificate notification task from Task Scheduler.

### [Set-CertificateAutoEnrollmentPolicy](./set-certificateautoenrollmentpolicy.md)
Sets local certificate auto-enrollment policy.

### [Switch-Certificate](./switch-certificate.md)
Marks one certificate as having been replaced by another certificate.

### [Test-Certificate](./test-certificate.md)
Verifies a certificate according to the input parameters.



