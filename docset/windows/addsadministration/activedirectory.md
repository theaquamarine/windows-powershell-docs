---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: ActiveDirectory
Module Guid: 43C15630-959C-49E4-A977-758C5CC93408
Download Help Link: http://go.microsoft.com/fwlink/?LinkId=301394
Help Version: 4.0.6.1
Locale: en-US
title: ActiveDirectory
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/27/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 8AD46969-D3B0-4DE9-81D3-D485B99CB93F
---

# ActiveDirectory Module
## Description
The Active Directory module for Windows PowerShell is a PowerShell module that consolidates a group of cmdlets. You can use these cmdlets to manage your Active Directory domains, Active Directory Lightweight Directory Services (AD LDS) configuration sets, and Active Directory Database Mounting Tool instances in a single, self-contained package.

If you don't have the Active Directory module installed on your machine, you need to download the correct Remote Server Administration Tools (RSAT) package for your OS.  If you're running windows 7, you will also need to run the `import-module ActiveDirectory` command from an elevated PowerShell prompt.

## ActiveDirectory Cmdlets
### [Add-ADCentralAccessPolicyMember](./add-adcentralaccesspolicymember.md)
Adds central access rules to a central access policy in Active Directory.

### [Add-ADComputerServiceAccount](./add-adcomputerserviceaccount.md)
Adds one or more service accounts to an Active Directory computer.

### [Add-ADDomainControllerPasswordReplicationPolicy](./add-addomaincontrollerpasswordreplicationpolicy.md)
Adds users, computers, and groups to the allowed or denied list of a read-only domain controller password replication policy.

### [Add-ADFineGrainedPasswordPolicySubject](./add-adfinegrainedpasswordpolicysubject.md)
Applies a fine-grained password policy to one or more users and groups.

### [Add-ADGroupMember](./add-adgroupmember.md)
Adds one or more members to an Active Directory group.

### [Add-ADPrincipalGroupMembership](./add-adprincipalgroupmembership.md)
Adds a member to one or more Active Directory groups.

### [Add-ADResourcePropertyListMember](./add-adresourcepropertylistmember.md)
Adds one or more resource properties to a resource property list in Active Directory.

### [Clear-ADAccountExpiration](./clear-adaccountexpiration.md)
Clears the expiration date for an Active Directory account.

### [Clear-ADClaimTransformLink](./clear-adclaimtransformlink.md)
Removes a claims transformation from being applied to one or more cross-forest trust relationships in Active Directory.

### [Disable-ADAccount](./disable-adaccount.md)
Disables an Active Directory account.

### [Disable-ADOptionalFeature](./disable-adoptionalfeature.md)
Disables an Active Directory optional feature.

### [Enable-ADAccount](./enable-adaccount.md)
Enables an Active Directory account.

### [Enable-ADOptionalFeature](./enable-adoptionalfeature.md)
Enables an Active Directory optional feature.

### [Get-ADAccountAuthorizationGroup](./get-adaccountauthorizationgroup.md)
Gets the accounts token group information.

### [Get-ADAccountResultantPasswordReplicationPolicy](./get-adaccountresultantpasswordreplicationpolicy.md)
Gets the resultant password replication policy for an Active Directory account.

### [Get-ADAuthenticationPolicy](./get-adauthenticationpolicy.md)
Gets one or more Active Directory Domain Services authentication policies.

### [Get-ADAuthenticationPolicySilo](./get-adauthenticationpolicysilo.md)
Gets one or more Active Directory Domain Services authentication policy silos.

### [Get-ADCentralAccessPolicy](./get-adcentralaccesspolicy.md)
Retrieves central access policies from Active Directory.

### [Get-ADCentralAccessRule](./get-adcentralaccessrule.md)
Retrieves central access rules from Active Directory.

### [Get-ADClaimTransformPolicy](./get-adclaimtransformpolicy.md)
Returns one or more Active Directory claim transform objects based on a specified filter.

### [Get-ADClaimType](./get-adclaimtype.md)
Returns a claim type from Active Directory.

### [Get-ADComputer](./get-adcomputer.md)
Gets one or more Active Directory computers.

### [Get-ADComputerServiceAccount](./get-adcomputerserviceaccount.md)
Gets the service accounts hosted by a computer.

### [Get-ADDCCloningExcludedApplicationList](./get-addccloningexcludedapplicationlist.md)
Gets a list of installed programs and services present on this domain controller that are not in the default or user defined inclusion list.

### [Get-ADDefaultDomainPasswordPolicy](./get-addefaultdomainpasswordpolicy.md)
Gets the default password policy for an Active Directory domain.

### [Get-ADDomain](./get-addomain.md)
Gets an Active Directory domain.

### [Get-ADDomainController](./get-addomaincontroller.md)
Gets one or more Active Directory domain controllers based on discoverable services criteria, search parameters or by providing a domain controller identifier, such as the NetBIOS name.

### [Get-ADDomainControllerPasswordReplicationPolicy](./get-addomaincontrollerpasswordreplicationpolicy.md)
Gets the members of the allowed list or denied list of a read-only domain controller's password replication policy.

### [Get-ADDomainControllerPasswordReplicationPolicyUsage](./get-addomaincontrollerpasswordreplicationpolicyusage.md)
Gets the Active Directory accounts that are authenticated by a read-only domain controller or that are in the revealed list of the domain controller.

### [Get-ADFineGrainedPasswordPolicy](./get-adfinegrainedpasswordpolicy.md)
Gets one or more Active Directory fine-grained password policies.

### [Get-ADFineGrainedPasswordPolicySubject](./get-adfinegrainedpasswordpolicysubject.md)
Gets the users and groups to which a fine-grained password policy is applied.

### [Get-ADForest](./get-adforest.md)
Gets an Active Directory forest.

### [Get-ADGroup](./get-adgroup.md)
Gets one or more Active Directory groups.

### [Get-ADGroupMember](./get-adgroupmember.md)
Gets the members of an Active Directory group.

### [Get-ADObject](./get-adobject.md)
Gets one or more Active Directory objects.

### [Get-ADOptionalFeature](./get-adoptionalfeature.md)
Gets one or more Active Directory optional features.

### [Get-ADOrganizationalUnit](./get-adorganizationalunit.md)
Gets one or more Active Directory organizational units.

### [Get-ADPrincipalGroupMembership](./get-adprincipalgroupmembership.md)
Gets the Active Directory groups that have a specified user, computer, group, or service account.

### [Get-ADReplicationAttributeMetadata](./get-adreplicationattributemetadata.md)
Gets the replication metadata for one or more Active Directory replication partners.

### [Get-ADReplicationConnection](./get-adreplicationconnection.md)
Returns a specific Active Directory replication connection or a set of AD replication connection objects based on a specified filter.

### [Get-ADReplicationFailure](./get-adreplicationfailure.md)
Returns a collection of data describing an Active Directory replication failure.

### [Get-ADReplicationPartnerMetadata](./get-adreplicationpartnermetadata.md)
Returns the replication metadata for a set of one or more replication partners.

### [Get-ADReplicationQueueOperation](./get-adreplicationqueueoperation.md)
Returns the contents of the replication queue for a specified server.

### [Get-ADReplicationSite](./get-adreplicationsite.md)
Returns a specific Active Directory replication site or a set of replication site objects based on a specified filter.

### [Get-ADReplicationSiteLink](./get-adreplicationsitelink.md)
Returns a specific Active Directory site link or a set of site links based on a specified filter.

### [Get-ADReplicationSiteLinkBridge](./get-adreplicationsitelinkbridge.md)
Gets a specific Active Directory site link bridge or a set of site link bridge objects based on a specified filter.

### [Get-ADReplicationSubnet](./get-adreplicationsubnet.md)
Gets one or more Active Directory subnets.

### [Get-ADReplicationUpToDatenessVectorTable](./get-adreplicationuptodatenessvectortable.md)
Displays the highest Update Sequence Number (USN) for the specified domain controller.

### [Get-ADResourceProperty](./get-adresourceproperty.md)
Gets one or more resource properties.

### [Get-ADResourcePropertyList](./get-adresourcepropertylist.md)
Gets resource property lists from Active Directory.

### [Get-ADResourcePropertyValueType](./get-adresourcepropertyvaluetype.md)
Gets a resource property value type from Active Directory.

### [Get-ADRootDSE](./get-adrootdse.md)
Gets the root of a directory server information tree.

### [Get-ADServiceAccount](./get-adserviceaccount.md)
Gets one or more Active Directory managed service accounts or group managed service accounts.

### [Get-ADTrust](./get-adtrust.md)
Gets all trusted domain objects in the directory.

### [Get-ADUser](./get-aduser.md)
Gets one or more Active Directory users.

### [Get-ADUserResultantPasswordPolicy](./get-aduserresultantpasswordpolicy.md)
Gets the resultant password policy for a user.

### [Grant-ADAuthenticationPolicySiloAccess](./grant-adauthenticationpolicysiloaccess.md)
Grants permission to join an authentication policy silo.

### [Install-ADServiceAccount](./install-adserviceaccount.md)
Installs an Active Directory managed service account on a computer or caches a group managed service account on a computer.

### [Move-ADDirectoryServer](./move-addirectoryserver.md)
Moves a directory server in Active Directory to a new site.

### [Move-ADDirectoryServerOperationMasterRole](./move-addirectoryserveroperationmasterrole.md)
Moves operation master roles to an Active Directory directory server.

### [Move-ADObject](./move-adobject.md)
Moves an Active Directory object or a container of objects to a different container or domain.

### [New-ADAuthenticationPolicy](./new-adauthenticationpolicy.md)
Creates an Active Directory Domain Services authentication policy object.

### [New-ADAuthenticationPolicySilo](./new-adauthenticationpolicysilo.md)
Creates an Active Directory Domain Services authentication policy silo object.

### [New-ADCentralAccessPolicy](./new-adcentralaccesspolicy.md)
Creates a new central access policy in Active Directory containing a set of central access rules.

### [New-ADCentralAccessRule](./new-adcentralaccessrule.md)
Creates a central access rule in Active Directory.

### [New-ADClaimTransformPolicy](./new-adclaimtransformpolicy.md)
Creates a new claim transformation policy object in Active Directory.

### [New-ADClaimType](./new-adclaimtype.md)
Creates a new claim type in Active Directory.

### [New-ADComputer](./new-adcomputer.md)
Creates a new Active Directory computer object.

### [New-ADDCCloneConfigFile](./new-addccloneconfigfile.md)
Performs prerequisite checks for cloning a domain controller and generates a clone configuration file if all checks succeed.

### [New-ADFineGrainedPasswordPolicy](./new-adfinegrainedpasswordpolicy.md)
Creates a new Active Directory fine-grained password policy.

### [New-ADGroup](./new-adgroup.md)
Creates an Active Directory group.

### [New-ADObject](./new-adobject.md)
Creates an Active Directory object.

### [New-ADOrganizationalUnit](./new-adorganizationalunit.md)
Creates an Active Directory organizational unit.

### [New-ADReplicationSite](./new-adreplicationsite.md)
Creates an Active Directory replication site in the directory.

### [New-ADReplicationSiteLink](./new-adreplicationsitelink.md)
Creates a new Active Directory site link for in managing replication.

### [New-ADReplicationSiteLinkBridge](./new-adreplicationsitelinkbridge.md)
Creates a site link bridge in Active Directory for replication.

### [New-ADReplicationSubnet](./new-adreplicationsubnet.md)
Creates an Active Directory replication subnet object.

### [New-ADResourceProperty](./new-adresourceproperty.md)
Creates a resource property in Active Directory.

### [New-ADResourcePropertyList](./new-adresourcepropertylist.md)
Creates a resource property list in Active Directory.

### [New-ADServiceAccount](./new-adserviceaccount.md)
Creates a new Active Directory managed service account or group managed service account object.

### [New-ADUser](./new-aduser.md)
Creates an Active Directory user.

### [Remove-ADAuthenticationPolicy](./remove-adauthenticationpolicy.md)
Removes an Active Directory Domain Services authentication policy object.

### [Remove-ADAuthenticationPolicySilo](./remove-adauthenticationpolicysilo.md)
Removes an Active Directory Domain Services authentication policy silo object.

### [Remove-ADCentralAccessPolicy](./remove-adcentralaccesspolicy.md)
Removes a central access policy from Active Directory.

### [Remove-ADCentralAccessPolicyMember](./remove-adcentralaccesspolicymember.md)
Removes central access rules from a central access policy in Active Directory.

### [Remove-ADCentralAccessRule](./remove-adcentralaccessrule.md)
Removes a central access rule from Active Directory.

### [Remove-ADClaimTransformPolicy](./remove-adclaimtransformpolicy.md)
Removes a claim transformation policy object from Active Directory.

### [Remove-ADClaimType](./remove-adclaimtype.md)
Removes a claim type from Active Directory.

### [Remove-ADComputer](./remove-adcomputer.md)
Removes an Active Directory computer.

### [Remove-ADComputerServiceAccount](./remove-adcomputerserviceaccount.md)
Removes one or more service accounts from a computer.

### [Remove-ADDomainControllerPasswordReplicationPolicy](./remove-addomaincontrollerpasswordreplicationpolicy.md)
Removes users, computers, and groups from the allowed or denied list of a read-only domain controller password replication policy.

### [Remove-ADFineGrainedPasswordPolicy](./remove-adfinegrainedpasswordpolicy.md)
Removes an Active Directory fine-grained password policy.

### [Remove-ADFineGrainedPasswordPolicySubject](./remove-adfinegrainedpasswordpolicysubject.md)
Removes one or more users from a fine-grained password policy.

### [Remove-ADGroup](./remove-adgroup.md)
Removes an Active Directory group.

### [Remove-ADGroupMember](./remove-adgroupmember.md)
Removes one or more members from an Active Directory group.

### [Remove-ADObject](./remove-adobject.md)
Removes an Active Directory object.

### [Remove-ADOrganizationalUnit](./remove-adorganizationalunit.md)
Removes an Active Directory organizational unit.

### [Remove-ADPrincipalGroupMembership](./remove-adprincipalgroupmembership.md)
Removes a member from one or more Active Directory groups.

### [Remove-ADReplicationSite](./remove-adreplicationsite.md)
Deletes the specified replication site object from Active Directory.

### [Remove-ADReplicationSiteLink](./remove-adreplicationsitelink.md)
Deletes an Active Directory site link used to manage replication.

### [Remove-ADReplicationSiteLinkBridge](./remove-adreplicationsitelinkbridge.md)
Deletes a replication site link bridge from Active Directory.

### [Remove-ADReplicationSubnet](./remove-adreplicationsubnet.md)
Deletes the specified Active Directory replication subnet object from the directory.

### [Remove-ADResourceProperty](./remove-adresourceproperty.md)
Removes a resource property from Active Directory.

### [Remove-ADResourcePropertyList](./remove-adresourcepropertylist.md)
Removes one or more resource property lists from Active Directory.

### [Remove-ADResourcePropertyListMember](./remove-adresourcepropertylistmember.md)
Removes one or more resource properties from a resource property list in Active Directory.

### [Remove-ADServiceAccount](./remove-adserviceaccount.md)
Removes an Active Directory managed service account or group managed service account object.

### [Remove-ADUser](./remove-aduser.md)
Removes an Active Directory user.

### [Rename-ADObject](./rename-adobject.md)
Changes the name of an Active Directory object.

### [Reset-ADServiceAccountPassword](./reset-adserviceaccountpassword.md)
Resets the password for a standalone managed service account.

### [Restore-ADObject](./restore-adobject.md)
Restores an Active Directory object.

### [Revoke-ADAuthenticationPolicySiloAccess](./revoke-adauthenticationpolicysiloaccess.md)
Revokes membership in an authentication policy silo for the specified account.

### [Search-ADAccount](./search-adaccount.md)
Gets Active Directory user, computer, or service accounts.

### [Set-ADAccountAuthenticationPolicySilo](./set-adaccountauthenticationpolicysilo.md)
Modifies the authentication policy or authentication policy silo of an account.

### [Set-ADAccountControl](./set-adaccountcontrol.md)
Modifies user account control (UAC) values for an Active Directory account.

### [Set-ADAccountExpiration](./set-adaccountexpiration.md)
Sets the expiration date for an Active Directory account.

### [Set-ADAccountPassword](./set-adaccountpassword.md)
Modifies the password of an Active Directory account.

### [Set-ADAuthenticationPolicy](./set-adauthenticationpolicy.md)
Modifies an Active Directory Domain Services authentication policy object.

### [Set-ADAuthenticationPolicySilo](./set-adauthenticationpolicysilo.md)
Modifies an Active Directory Domain Services authentication policy silo object.

### [Set-ADCentralAccessPolicy](./set-adcentralaccesspolicy.md)
Modifies a central access policy in Active Directory.

### [Set-ADCentralAccessRule](./set-adcentralaccessrule.md)
Modifies a central access rule in Active Directory.

### [Set-ADClaimTransformLink](./set-adclaimtransformlink.md)
Applies a claims transformation to one or more cross-forest trust relationships in Active Directory.

### [Set-ADClaimTransformPolicy](./set-adclaimtransformpolicy.md)
Sets the properties of a claims transformation policy in Active Directory.

### [Set-ADClaimType](./set-adclaimtype.md)
Modify a claim type in Active Directory.

### [Set-ADComputer](./set-adcomputer.md)
Modifies an Active Directory computer object.

### [Set-ADDefaultDomainPasswordPolicy](./set-addefaultdomainpasswordpolicy.md)
Modifies the default password policy for an Active Directory domain.

### [Set-ADDomain](./set-addomain.md)
Modifies an Active Directory domain.

### [Set-ADDomainMode](./set-addomainmode.md)
Sets the domain mode for an Active Directory domain.

### [Set-ADFineGrainedPasswordPolicy](./set-adfinegrainedpasswordpolicy.md)
Modifies an Active Directory fine-grained password policy.

### [Set-ADForest](./set-adforest.md)
Modifies an Active Directory forest.

### [Set-ADForestMode](./set-adforestmode.md)
Sets the forest mode for an Active Directory forest.

### [Set-ADGroup](./set-adgroup.md)
Modifies an Active Directory group.

### [Set-ADObject](./set-adobject.md)
Modifies an Active Directory object.

### [Set-ADOrganizationalUnit](./set-adorganizationalunit.md)
Modifies an Active Directory organizational unit.

### [Set-ADReplicationConnection](./set-adreplicationconnection.md)
Sets properties on Active Directory replication connections.

### [Set-ADReplicationSite](./set-adreplicationsite.md)
Sets the replication properties for an Active Directory site.

### [Set-ADReplicationSiteLink](./set-adreplicationsitelink.md)
Sets the properties for an Active Directory site link.

### [Set-ADReplicationSiteLinkBridge](./set-adreplicationsitelinkbridge.md)
Sets the properties of a replication site link bridge in Active Directory.

### [Set-ADReplicationSubnet](./set-adreplicationsubnet.md)
Sets the properties of an Active Directory replication subnet object.

### [Set-ADResourceProperty](./set-adresourceproperty.md)
Modifies a resource property in Active Directory.

### [Set-ADResourcePropertyList](./set-adresourcepropertylist.md)
Modifies a resource property list in Active Directory.

### [Set-ADServiceAccount](./set-adserviceaccount.md)
Modifies an Active Directory managed service account or group managed service account object.

### [Set-ADUser](./set-aduser.md)
Modifies an Active Directory user.

### [Show-ADAuthenticationPolicyExpression](./show-adauthenticationpolicyexpression.md)
Displays the Edit Access Control Conditions window update or create security descriptor definition language (SDDL) security descriptors.

### [Sync-ADObject](./sync-adobject.md)
Replicates a single object between any two domain controllers that have partitions in common.

### [Test-ADServiceAccount](./test-adserviceaccount.md)
Tests a managed service account from a computer.

### [Uninstall-ADServiceAccount](./uninstall-adserviceaccount.md)
Uninstalls an Active Directory managed service account from a computer or removes a cached group managed service account from a computer.

### [Unlock-ADAccount](./unlock-adaccount.md)
Unlocks an Active Directory account.



