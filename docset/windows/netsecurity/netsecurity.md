---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: NetSecurity
Module Guid: 4B26FF51-7AEE-4731-9CF7-508B82532CBF
Download Help Link: http://go.microsoft.com/fwlink/?linkid=285764
Help Version: 4.0.3.1
Locale: en-US
title: NetSecurity
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/27/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 9E474DAE-3089-41AF-98FF-30EA9FDB0C32
---

# NetSecurity Module
## Description
This reference provides cmdlet descriptions and syntax for all Network Security cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## NetSecurity Cmdlets
### [Copy-NetFirewallRule](./copy-netfirewallrule.md)
Copies an entire firewall rule, and associated filters, to the same or to a different policy store.

### [Copy-NetIPsecMainModeCryptoSet](./copy-netipsecmainmodecryptoset.md)
Copies an entire main mode cryptographic set to the same or to a different policy store.

### [Copy-NetIPsecMainModeRule](./copy-netipsecmainmoderule.md)
Copies an entire main mode rule, and associated filters, to the same or to a different policy store.

### [Copy-NetIPsecPhase1AuthSet](./Copy-NetIPsecPhase1AuthSet.md)
Copies an entire phase 1 authentication set to the same or to a different policy store.

### [Copy-NetIPsecPhase2AuthSet](./Copy-NetIPsecPhase2AuthSet.md)
Copies an entire phase 2 authentication set to the same or to a different policy store.

### [Copy-NetIPsecQuickModeCryptoSet](./copy-netipsecquickmodecryptoset.md)
Copies an entire quick mode cryptographic set to the same or to a different policy store.

### [Copy-NetIPsecRule](./copy-netipsecrule.md)
Copies an entire IPsec rule, and the associated filters, to the same or to a different policy store.

### [Disable-NetFirewallRule](./disable-netfirewallrule.md)
Disables a firewall rule.

### [Disable-NetIPsecMainModeRule](./disable-netipsecmainmoderule.md)
Disables a main mode rule.

### [Disable-NetIPsecRule](./disable-netipsecrule.md)
Disables an IPsec rule.

### [Enable-NetFirewallRule](./enable-netfirewallrule.md)
Enables a previously disabled firewall rule.

### [Enable-NetIPsecMainModeRule](./enable-netipsecmainmoderule.md)
Enables a previously disabled main mode rule.

### [Enable-NetIPsecRule](./enable-netipsecrule.md)
Enables a previously disabled IPsec rule.

### [Find-NetIPsecRule](./find-netipsecrule.md)
Gets IPsec rules that match specified criteria.

### [Get-DAPolicyChange](./get-dapolicychange.md)
Gets a list of IP addresses that need to be added and deleted to an IPsec rule based on the differences detected between the IP addresses for the existing rule and the IP addresses derived from the input parameters, and creates a Windows PowerShell?? script (.ps1) that updates the IPsec rule in the appropriate policy stores.

### [Get-NetFirewallAddressFilter](./get-netfirewalladdressfilter.md)
Retrieves address filter objects from the target computer.

### [Get-NetFirewallApplicationFilter](./get-netfirewallapplicationfilter.md)
Retrieves application filter objects from the target computer.

### [Get-NetFirewallInterfaceFilter](./get-netfirewallinterfacefilter.md)
Retrieves interface filter objects from the target computer.

### [Get-NetFirewallInterfaceTypeFilter](./get-netfirewallinterfacetypefilter.md)
Retrieves interface type filter objects from the target computer.

### [Get-NetFirewallPortFilter](./get-netfirewallportfilter.md)
Retrieves port filter objects from the target computer.

### [Get-NetFirewallProfile](./get-netfirewallprofile.md)
Displays settings that apply to the per-profile configurations of the Windows Firewall with Advanced Security.

### [Get-NetFirewallRule](./get-netfirewallrule.md)
Retrieves firewall rules from the target computer.

### [Get-NetFirewallSecurityFilter](./get-netfirewallsecurityfilter.md)
Retrieves security filter objects from the target computer.

### [Get-NetFirewallServiceFilter](./get-netfirewallservicefilter.md)
Retrieves service filter objects from the target computer.

### [Get-NetFirewallSetting](./get-netfirewallsetting.md)
Retrieves the global firewall settings of the target computer.

### [Get-NetIPsecDospSetting](./get-netipsecdospsetting.md)
Retrieves IPsec DoS protection settings from the target computer.

### [Get-NetIPsecMainModeCryptoSet](./get-netipsecmainmodecryptoset.md)
Gets main mode cryptographic sets from the target computer.

### [Get-NetIPsecMainModeRule](./get-netipsecmainmoderule.md)
Gets the IPsec main mode rules from the target computer.

### [Get-NetIPsecMainModeSA](./get-netipsecmainmodesa.md)
Returns active main mode security associations (SA) from the target computer.

### [Get-NetIPsecPhase1AuthSet](./Get-NetIPsecPhase1AuthSet.md)
Gets a phase 1 authentication set from the target computer.

### [Get-NetIPsecPhase2AuthSet](./Get-NetIPsecPhase2AuthSet.md)
Gets a phase 2 authorization set from the target computer.

### [Get-NetIPsecQuickModeCryptoSet](./get-netipsecquickmodecryptoset.md)
Gets a quick mode cryptographic set from the target computer.

### [Get-NetIPsecQuickModeSA](./get-netipsecquickmodesa.md)
Returns active quick mode security associations (SAs) from the target computer.

### [Get-NetIPsecRule](./get-netipsecrule.md)
Gets an IPsec rule from the target computer.

### [New-NetFirewallRule](./new-netfirewallrule.md)
Creates a new inbound or outbound firewall rule and adds the rule to the target computer.

### [New-NetIPsecAuthProposal](./new-netipsecauthproposal.md)
Creates a main mode authentication proposal that specifies a suite of authentication protocols to offer in IPsec main mode negotiations with other computers.

### [New-NetIPsecDospSetting](./new-netipsecdospsetting.md)
Creates an IPsec DoS protection setting and adds the setting to the target computer.

### [New-NetIPsecMainModeCryptoProposal](./new-netipsecmainmodecryptoproposal.md)
Creates a main mode cryptographic proposal that specifies a suite of cryptographic protocols to offer in IPsec main mode negotiations with other computers.

### [New-NetIPsecMainModeCryptoSet](./new-netipsecmainmodecryptoset.md)
Creates a main mode cryptographic set that contains suites of cryptographic protocols to offer in IPsec main mode negotiations with other computers.

### [New-NetIPsecMainModeRule](./new-netipsecmainmoderule.md)
Creates an IPsec main mode rule that tells the computer which peers require IPsec security associations (SAs) for securing network traffic, and how to negotiate those SAs.

### [New-NetIPsecPhase1AuthSet](./New-NetIPsecPhase1AuthSet.md)
Creates a phase 1 authentication set that specifies the methods offered for main mode first authentication during IPsec negotiations.

### [New-NetIPsecPhase2AuthSet](./New-NetIPsecPhase2AuthSet.md)
Creates a phase 2 authentication set that specifies the methods offered for second user authentication during IPsec negotiations.

### [New-NetIPsecQuickModeCryptoProposal](./new-netipsecquickmodecryptoproposal.md)
Creates a quick mode cryptographic proposal that specifies a suite of cryptographic protocols to offer in IPsec quick mode negotiations with other computers.

### [New-NetIPsecQuickModeCryptoSet](./new-netipsecquickmodecryptoset.md)
Creates a quick mode cryptographic set that contains suites of cryptographic protocols to offer in IPsec quick mode negotiations with other computers.

### [New-NetIPsecRule](./new-netipsecrule.md)
Creates an IPsec rule that defines security requirements for network connections that match the specified criteria.

### [Open-NetGPO](./open-netgpo.md)
Creates a cached copy of the Group Policy Object (GPO) to modify locally.

### [Remove-NetFirewallRule](./remove-netfirewallrule.md)
Deletes one or more firewall rules that match the specified criteria.

### [Remove-NetIPsecDospSetting](./remove-netipsecdospsetting.md)
Deletes existing IPsec Dosp configurations.

### [Remove-NetIPsecMainModeCryptoSet](./remove-netipsecmainmodecryptoset.md)
Deletes any main mode cryptographic sets that match the specified criteria.

### [Remove-NetIPsecMainModeRule](./remove-netipsecmainmoderule.md)
Deletes any main mode rules that match the specified criteria.

### [Remove-NetIPsecMainModeSA](./remove-netipsecmainmodesa.md)
Removes an active main mode security association (SA).

### [Remove-NetIPsecPhase1AuthSet](./Remove-NetIPsecPhase1AuthSet.md)
Deletes all of the phase 1 authentication sets that match the specified criteria.

### [Remove-NetIPsecPhase2AuthSet](./Remove-NetIPsecPhase2AuthSet.md)
Deletes all of the phase 2 authentication sets that match the specified criteria.

### [Remove-NetIPsecQuickModeCryptoSet](./remove-netipsecquickmodecryptoset.md)
Deletes all of the quick mode cryptographic sets that match the specified criteria.

### [Remove-NetIPsecQuickModeSA](./remove-netipsecquickmodesa.md)
Deletes an established quick mode security association (SA).

### [Remove-NetIPsecRule](./remove-netipsecrule.md)
Defines security requirements for network connections that match the specified criteria.

### [Rename-NetFirewallRule](./rename-netfirewallrule.md)
Renames a single IPsec rule.

### [Rename-NetIPsecMainModeCryptoSet](./rename-netipsecmainmodecryptoset.md)
Renames a single main mode cryptographic set.

### [Rename-NetIPsecMainModeRule](./rename-netipsecmainmoderule.md)
Renames a single main mode rule.

### [Rename-NetIPsecPhase1AuthSet](./Rename-NetIPsecPhase1AuthSet.md)
Renames a single phase 1 authentication set.

### [Rename-NetIPsecPhase2AuthSet](./Rename-NetIPsecPhase2AuthSet.md)
Renames a single phase 2 authentication set.

### [Rename-NetIPsecQuickModeCryptoSet](./rename-netipsecquickmodecryptoset.md)
Renames a single quick mode cryptographic set.

### [Rename-NetIPsecRule](./rename-netipsecrule.md)
Renames a single IPsec rule.

### [Save-NetGPO](./save-netgpo.md)
Applies the modified cached local Group Policy Object (GPO) to the actual GPO.

### [Set-NetFirewallAddressFilter](./set-netfirewalladdressfilter.md)
Modifies address filter objects, thereby modifying the local and remote address conditions of the firewall, IPsec, and main mode rules.

### [Set-NetFirewallApplicationFilter](./set-netfirewallapplicationfilter.md)
Modifies application filter objects, thereby modifying the program and package conditions of the firewall rules.

### [Set-NetFirewallInterfaceFilter](./set-netfirewallinterfacefilter.md)
Modifies interface filter objects, thereby modifying the InterfaceAlias parameter values of the firewall or IPsec rules.

### [Set-NetFirewallInterfaceTypeFilter](./set-netfirewallinterfacetypefilter.md)
Modifies interface type filter objects, thereby modifying the interface type conditions of the firewall or IPsec rules.

### [Set-NetFirewallPortFilter](./set-netfirewallportfilter.md)
Modifies port filter objects, thereby modifying the protocol and port conditions using the Protocol, LocalPort, RemotePort, IcmpType, and DynamicTransport parameters of the firewall or IPsec rules.

### [Set-NetFirewallProfile](./set-netfirewallprofile.md)
Configures settings that apply to the per-profile configurations of the Windows Firewall with Advanced Security.

### [Set-NetFirewallRule](./set-netfirewallrule.md)
Modifies existing firewall rules.

### [Set-NetFirewallSecurityFilter](./set-netfirewallsecurityfilter.md)
Modifies security filter objects, thereby modifying the Authentication, Encryption, OverrideBlockRules, LocalUser, RemoteUser, and RemoteMachine conditions of the firewall rules.

### [Set-NetFirewallServiceFilter](./set-netfirewallservicefilter.md)
Modifies service filter objects, thereby modifying the service conditions of the firewall rules.

### [Set-NetFirewallSetting](./set-netfirewallsetting.md)
Modifies the global firewall settings of the target computer.

### [Set-NetIPsecDospSetting](./set-netipsecdospsetting.md)
Modifies existing IPsec Dos protection settings.

### [Set-NetIPsecMainModeCryptoSet](./set-netipsecmainmodecryptoset.md)
Modifies existing main mode cryptographic sets.

### [Set-NetIPsecMainModeRule](./set-netipsecmainmoderule.md)
Modifies existing main mode rules.

### [Set-NetIPsecPhase1AuthSet](./Set-NetIPsecPhase1AuthSet.md)
Modifies existing phase 1 authentication sets.

### [Set-NetIPsecPhase2AuthSet](./Set-NetIPsecPhase2AuthSet.md)
Modifies existing phase 2 authentication sets.

### [Set-NetIPsecQuickModeCryptoSet](./set-netipsecquickmodecryptoset.md)
Modifies existing quick mode cryptographic sets.

### [Set-NetIPsecRule](./set-netipsecrule.md)
Modifies existing IPsec rules.

### [Show-NetFirewallRule](./show-netfirewallrule.md)
Displays all of the existing IPsec rules and associated objects in a fully expanded view.

### [Show-NetIPsecRule](./show-netipsecrule.md)
Displays all of the existing IPsec rules and associated objects in a fully expanded view.

### [Sync-NetIPsecRule](./sync-netipsecrule.md)
Gets the list of IP addresses to be added and deleted to an IPsec rule based on the differences detected between the existing rule IP addresses and the specified IP addresses.

### [Update-NetIPsecRule](./update-netipsecrule.md)
Updates an IPsec rule by adding or removing a set of IP addresses.



