---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: IpamServer
Module Guid: 69775F93-9317-4234-A558-13B6655FC41B
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390777
Help Version: 5.0.2.1
Locale: en-US
title: IpamServer
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: E3FDBFD8-19FB-42FE-B426-B83DAC1CCC08
---

# IpamServer Module
## Description
This reference provides cmdlet descriptions and syntax for all IP Address Management (IPAM) Server-specific cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## IpamServer Cmdlets
### [Add-IpamAddress](./add-ipamaddress.md)
Adds an IP address to IPAM.

### [Add-IpamAddressSpace](./add-ipamaddressspace.md)
Adds an address space to IPAM.

### [Add-IpamBlock](./add-ipamblock.md)
Adds an IP address block to IPAM.

### [Add-IpamCustomField](./add-ipamcustomfield.md)
Adds a free-form or multivalued custom field to IPAM.

### [Add-IpamCustomFieldAssociation](./add-ipamcustomfieldassociation.md)
Adds an association between values for custom fields that are defined in IPAM.

### [Add-IpamCustomValue](./add-ipamcustomvalue.md)
Adds a value to a custom field in IPAM.

### [Add-IpamDiscoveryDomain](./add-ipamdiscoverydomain.md)
Adds a new Active Directory domain to the list of domains in which IPAM discovers infrastructure servers.

### [Add-IpamRange](./add-ipamrange.md)
Adds an IP address range to the configuration of an IPAM server.

### [Add-IpamServerInventory](./add-ipamserverinventory.md)
Adds an infrastructure server to an IPAM database.

### [Add-IpamSubnet](./add-ipamsubnet.md)
Adds a subnet to IPAM.

### [Disable-IpamCapability](./disable-ipamcapability.md)
Disables an optional capability in IPAM.

### [Enable-IpamCapability](./enable-ipamcapability.md)
Enables an optional capability on the IPAM server.

### [Export-IpamAddress](./export-ipamaddress.md)
Exports IP addresses from IPAM.

### [Export-IpamRange](./export-ipamrange.md)
Exports all of the IP address ranges as a file or as an array of objects or both.

### [Export-IpamSubnet](./export-ipamsubnet.md)
Exports the IP address subnets of an address family on the computer that runs IPAM.

### [Find-IpamFreeAddress](./find-ipamfreeaddress.md)
Gets one or more free IP addresses from a range of IP addresses in IPAM.

### [Find-IpamFreeRange](./find-ipamfreerange.md)
Finds one or more free IP ranges from a specified subnet.

### [Find-IpamFreeSubnet](./find-ipamfreesubnet.md)
Finds one or more free IP subnets in a specified IP block.

### [Get-IpamAddress](./get-ipamaddress.md)
Gets IP addresses from IPAM.

### [Get-IpamAddressSpace](./get-ipamaddressspace.md)
Gets address spaces in IPAM.

### [Get-IpamAddressUtilizationThreshold](./get-ipamaddressutilizationthreshold.md)
Gets the threshold configuration for address utilization alerts.

### [Get-IpamBlock](./get-ipamblock.md)
Gets a set of address blocks from IPAM.

### [Get-IpamCapability](./get-ipamcapability.md)
Gets all optional capabilities in IPAM.

### [Get-IpamConfiguration](./get-ipamconfiguration.md)
Gets the configuration for the computer that runs IPAM.

### [Get-IpamConfigurationEvent](./get-ipamconfigurationevent.md)
Gets IPAM configuration events from the IPAM database.

### [Get-IpamCustomField](./get-ipamcustomfield.md)
Gets custom fields in IPAM.

### [Get-IpamCustomFieldAssociation](./get-ipamcustomfieldassociation.md)
Gets associations between two custom fields defined in IPAM.

### [Get-IpamDatabase](./get-ipamdatabase.md)
Gets configuration settings for the IPAM database.

### [Get-IpamDhcpConfigurationEvent](./get-ipamdhcpconfigurationevent.md)
Gets configuration events for DHCP servers from the IPAM database.

### [Get-IpamDhcpScope](./get-ipamdhcpscope.md)
Gets information about DHCP scopes from IPAM database.

### [Get-IpamDhcpServer](./get-ipamdhcpserver.md)
Gets information about  DHCP servers from IPAM database.

### [Get-IpamDhcpSuperscope](./get-ipamdhcpsuperscope.md)
Gets information about DHCP superscopes from IPAM database.

### [Get-IpamDiscoveryDomain](./get-ipamdiscoverydomain.md)
Gets the list of Active Directory domains in which IPAM discovers infrastructure servers.

### [Get-IpamDnsConditionalForwarder](./get-ipamdnsconditionalforwarder.md)
Gets information about DNS conditional forwarders from IPAM database.

### [Get-IpamDnsResourceRecord](./get-ipamdnsresourcerecord.md)
Gets DNS resource records from IPAM database.

### [Get-IpamDnsServer](./get-ipamdnsserver.md)
Gets information about DNS servers from IPAM database.

### [Get-IpamDnsZone](./get-ipamdnszone.md)
Gets information about DNS zones from IPAM database.

### [Get-IpamIpAddressAuditEvent](./get-ipamipaddressauditevent.md)
Gets all IP address audit events in IPAM.

### [Get-IpamRange](./get-ipamrange.md)
Gets a set of IP address ranges from an IPAM server.

### [Get-IpamServerInventory](./get-ipamserverinventory.md)
Gets the properties of managed servers in the IPAM server inventory.

### [Get-IpamSubnet](./get-ipamsubnet.md)
Gets a set of subnets from IPAM.

### [Import-IpamAddress](./import-ipamaddress.md)
Imports IP address into the IPAM server.

### [Import-IpamRange](./import-ipamrange.md)
Imports one or more IP address range objects from the specified file into the IPAM server.

### [Import-IpamSubnet](./import-ipamsubnet.md)
Imports IP address subnet objects from the specified file into IPAM.

### [Invoke-IpamGpoProvisioning](./invoke-ipamgpoprovisioning.md)
Creates and links group policies in the specified domain for provisioning required access settings on the servers managed by the computer running the IPAM server.

### [Invoke-IpamServerProvisioning](./invoke-ipamserverprovisioning.md)
Automates the provisioning of IPAM server.

### [Move-IpamDatabase](./move-ipamdatabase.md)
Migrates the IPAM database to a SQL Server database.

### [Remove-IpamAddress](./remove-ipamaddress.md)
Removes a set of addresses from IPAM.

### [Remove-IpamAddressSpace](./remove-ipamaddressspace.md)
Removes address spaces from IPAM.

### [Remove-IpamBlock](./remove-ipamblock.md)
Removes an address block from IPAM.

### [Remove-IpamConfigurationEvent](./remove-ipamconfigurationevent.md)
Removes IPAM server configuration events.

### [Remove-IpamCustomField](./remove-ipamcustomfield.md)
Removes a custom field from IPAM.

### [Remove-IpamCustomFieldAssociation](./remove-ipamcustomfieldassociation.md)
Removes an association between two custom fields that are defined in IPAM.

### [Remove-IpamCustomValue](./remove-ipamcustomvalue.md)
Removes a custom value from IPAM.

### [Remove-IpamDhcpConfigurationEvent](./remove-ipamdhcpconfigurationevent.md)
Removes configuration events for DHCP servers from the IPAM database.

### [Remove-IpamDiscoveryDomain](./remove-ipamdiscoverydomain.md)
Removes a domain from IPAM.

### [Remove-IpamIpAddressAuditEvent](./remove-ipamipaddressauditevent.md)
Removes IP address audit events from the IPAM database.

### [Remove-IpamRange](./remove-ipamrange.md)
Removes a range of IP addresses from an IPAM server configuration.

### [Remove-IpamServerInventory](./remove-ipamserverinventory.md)
Removes a server from an IPAM server inventory.

### [Remove-IpamSubnet](./remove-ipamsubnet.md)
Removes a subnet from IPAM.

### [Remove-IpamUtilizationData](./remove-ipamutilizationdata.md)


### [Rename-IpamCustomField](./rename-ipamcustomfield.md)
Renames a custom field in IPAM.

### [Rename-IpamCustomValue](./rename-ipamcustomvalue.md)
Changes a value for a custom field.

### [Set-IpamAccessScope](./set-ipamaccessscope.md)
Configures an IPAM access scope.

### [Set-IpamAddress](./set-ipamaddress.md)
Modifies an IP address in IPAM.

### [Set-IpamAddressSpace](./set-ipamaddressspace.md)
Modifies address spaces in IPAM.

### [Set-IpamAddressUtilizationThreshold](./set-ipamaddressutilizationthreshold.md)
Modifies the address utilization thresholds in IPAM.

### [Set-IpamBlock](./set-ipamblock.md)
Modifies an IP address block in IPAM.

### [Set-IpamConfiguration](./set-ipamconfiguration.md)
Modifies the configuration for the computer that runs the IPAM server.

### [Set-IpamCustomFieldAssociation](./set-ipamcustomfieldassociation.md)
Modifies associations of values for custom fields defined in IPAM.

### [Set-IpamDatabase](./set-ipamdatabase.md)
Modifies settings that IPAM uses to connect to the IPAM database.

### [Set-IpamDiscoveryDomain](./set-ipamdiscoverydomain.md)
Modifies the IPAM discovery configuration.

### [Set-IpamRange](./set-ipamrange.md)
Modifies an existing IP address range.

### [Set-IpamServerInventory](./set-ipamserverinventory.md)
Modifies the properties of an infrastructure server in the IPAM server inventory.

### [Set-IpamSubnet](./set-ipamsubnet.md)
Modifies an existing IP subnet in IPAM.

### [Update-IpamServer](./update-ipamserver.md)
Updates an IPAM server following an operating system upgrade.



