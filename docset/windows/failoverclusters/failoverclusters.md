---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: FailoverClusters
Module Guid: CC3E946B-9141-48C2-95D8-D9E56594416A
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390770
Help Version: 5.0.3.3
Locale: en-US
title: FailoverClusters
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 1149AB0F-CE0C-4F56-8352-15D29814411F
---

# FailoverClusters Module
## Description
This reference provides cmdlet descriptions and syntax for all failover cluster-specific cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## FailoverClusters Cmdlets
### [Add-ClusterCheckpoint](./add-clustercheckpoint.md)
Adds a cryptographic key checkpoint or registry checkpoint for a resource.

### [Add-ClusterDisk](./add-clusterdisk.md)
Makes a new disk available for use in a failover cluster.

### [Add-ClusterFileServerRole](./add-clusterfileserverrole.md)
Creates a clustered file server resource group.

### [Add-ClusterGenericApplicationRole](./add-clustergenericapplicationrole.md)
Configures high availability for an application that was not originally designed to run in a failover cluster.

### [Add-ClusterGenericScriptRole](./add-clustergenericscriptrole.md)
Configures an application controlled by a script that runs in Windows Script Host, within a failover cluster.

### [Add-ClusterGenericServiceRole](./add-clustergenericservicerole.md)
Configures high availability for a service that was not originally designed to run in a failover cluster.

### [Add-ClusterGroup](./add-clustergroup.md)
Adds an empty resource group to the failover cluster configuration, in preparation for adding clustered resources to the group.

### [Add-ClusterGroupSetDependency](./add-clustergroupsetdependency.md)
Adds a dependency to a cluster set.

### [Add-ClusterGroupToSet](./add-clustergrouptoset.md)
Adds a group to a set.

### [Add-ClusteriSCSITargetServerRole](./add-clusteriscsitargetserverrole.md)
Creates a highly available iSCSI Target server.

### [Add-ClusterNode](./add-clusternode.md)
Adds a node (server) to a failover cluster.

### [Add-ClusterResource](./add-clusterresource.md)
Adds a resource to a clustered role, or resource group, in a failover cluster.

### [Add-ClusterResourceDependency](./add-clusterresourcedependency.md)
Adds a resource to the list of resources on which a particular resource depends, using AND as the connector, within a failover cluster.

### [Add-ClusterResourceType](./add-clusterresourcetype.md)
Adds a resource type to a failover cluster, and specifies information such as the dynamic-link library (DLL) to use with that resource type.

### [Add-ClusterScaleOutFileServerRole](./add-clusterscaleoutfileserverrole.md)
Creates a clustered file server for scale-out application data.

### [Add-ClusterSharedVolume](./add-clustersharedvolume.md)
Makes a volume available in Cluster Shared Volumes in a failover cluster.

### [Add-ClusterVirtualMachineRole](./add-clustervirtualmachinerole.md)
Creates a clustered virtual machine, that is, a virtual machine that can be failed over if necessary to a different server in the failover cluster.

### [Add-ClusterVMMonitoredItem](./add-clustervmmonitoreditem.md)
Configures monitoring for a service or an Event Tracing for Windows (ETW) event so that it is monitored on a virtual machine.

### [Block-ClusterAccess](./block-clusteraccess.md)
Prevents the specified user or users from accessing a failover cluster.

### [Clear-ClusterDiskReservation](./clear-clusterdiskreservation.md)
Clears the persistent reservation on a disk in a failover cluster.

### [Clear-ClusterNode](./clear-clusternode.md)
Clears the cluster configuration from a node that was evicted from a failover cluster.

### [Disable-ClusterStorageSpacesDirect](./disable-clusterstoragespacesdirect.md)
Disables S2D.

### [Enable-ClusterStorageSpacesDirect](./enable-clusterstoragespacesdirect.md)
Enables S2D.

### [Get-Cluster](./get-cluster.md)
Gets information about one or more failover clusters in a given domain.

### [Get-ClusterAccess](./get-clusteraccess.md)
Gets information about permissions that control access to a failover cluster.

### [Get-ClusterAvailableDisk](./get-clusteravailabledisk.md)
Gets information about the disks that can support Failover Clustering and are visible to all nodes, but are not yet part of the set of clustered disks.

### [Get-ClusterCheckpoint](./get-clustercheckpoint.md)
Retrieves a cryptographic key checkpoint or registry checkpoint for a resource.

### [Get-ClusterDiagnosticInfo](./get-clusterdiagnosticinfo.md)
Gets diagnostics for a cluster a cluster that contains VMs and produces a zip file containing the data.

### [Get-ClusterFaultDomain](./get-clusterfaultdomain.md)
Gets the cluster fault domains in a cluster.

### [Get-ClusterFaultDomainXML](./get-clusterfaultdomainxml.md)
Gets the fault domain as an XML string.

### [Get-ClusterGroup](./get-clustergroup.md)
Gets information about one or more clustered roles (resource groups) in a failover cluster.

### [Get-ClusterGroupSet](./get-clustergroupset.md)
Gets the group sets in the cluster.

### [Get-ClusterGroupSetDependency](./get-clustergroupsetdependency.md)
Gets the cluster group sets based on dependency relationships.

### [Get-ClusterLog](./get-clusterlog.md)
Creates a log file for all nodes, or a specific a node, in a failover cluster.

### [Get-ClusterNetwork](./get-clusternetwork.md)
Gets information about one or more networks in a failover cluster.

### [Get-ClusterNetworkInterface](./get-clusternetworkinterface.md)
Gets information about one or more network adapters in a failover cluster.

### [Get-ClusterNode](./get-clusternode.md)
Gets information about one or more nodes, or servers, in a failover cluster.

### [Get-ClusterOwnerNode](./get-clusterownernode.md)
Gets information about which nodes can own a resource in a failover cluster or information about the order of preference among owner nodes for a clustered role.

### [Get-ClusterParameter](./get-clusterparameter.md)
Gets detailed information about an object in a failover cluster, such as a cluster resource.

### [Get-ClusterQuorum](./get-clusterquorum.md)
Gets information about the quorum configuration of a failover cluster.

### [Get-ClusterResource](./get-clusterresource.md)
Gets information about one or more resources in a failover cluster.

### [Get-ClusterResourceDependency](./get-clusterresourcedependency.md)
Gets information about the dependencies that have been configured between clustered resources in a failover cluster.

### [Get-ClusterResourceDependencyReport](./get-clusterresourcedependencyreport.md)
Generates a report that lists the dependencies between resources in a failover cluster.

### [Get-ClusterResourceType](./get-clusterresourcetype.md)
Gets information about one or more resource types in a failover cluster.

### [Get-ClusterSharedVolume](./get-clustersharedvolume.md)
Gets information about Cluster Shared Volumes in a failover cluster.

### [Get-ClusterSharedVolumeState](./get-clustersharedvolumestate.md)
Gets the state of Cluster Shared Volumes in a cluster.

### [Get-ClusterStorageSpacesDirect](./get-clusterstoragespacesdirect.md)
Gets the S2D settings from a cluster.

### [Get-ClusterVMMonitoredItem](./get-clustervmmonitoreditem.md)
Gets the list of services and events currently being monitored in the virtual machine.

### [Grant-ClusterAccess](./grant-clusteraccess.md)
Grants access to a failover cluster, either full access or read-only access.

### [Move-ClusterGroup](./move-clustergroup.md)
Moves a clustered role (a resource group) from one node to another in a failover cluster.

### [Move-ClusterResource](./move-clusterresource.md)
Moves a clustered resource from one clustered role to another within a failover cluster.

### [Move-ClusterSharedVolume](./move-clustersharedvolume.md)
Moves a Cluster Shared Volume (CSV) to ownership by a different node in a failover cluster.

### [Move-ClusterVirtualMachineRole](./move-clustervirtualmachinerole.md)
Moves the ownership of a clustered virtual machine to a different node.

### [New-Cluster](./new-cluster.md)
Creates a new failover cluster.

### [New-ClusterFaultDomain](./new-clusterfaultdomain.md)
Creates a fault domain in the cluster.

### [New-ClusterGroupSet](./new-clustergroupset.md)
Create a names set of groups in the cluster.

### [New-ClusterNameAccount](./new-clusternameaccount.md)
Creates a cluster name account in Active Directory Domain Services.

### [Remove-Cluster](./remove-cluster.md)
Destroys an existing failover cluster.

### [Remove-ClusterAccess](./remove-clusteraccess.md)
Removes a user from the access list on the cluster.

### [Remove-ClusterCheckpoint](./remove-clustercheckpoint.md)
Removes a cryptographic key checkpoint or registry checkpoint for a resource.

### [Remove-ClusterFaultDomain](./remove-clusterfaultdomain.md)
Removes a fault domain.

### [Remove-ClusterGroup](./remove-clustergroup.md)
Removes a clustered role, also called a resource group, from a failover cluster.

### [Remove-ClusterGroupFromSet](./remove-clustergroupfromset.md)
Removes a group from a set.

### [Remove-ClusterGroupSet](./remove-clustergroupset.md)
Removes a group set from the cluster.

### [Remove-ClusterGroupSetDependency](./remove-clustergroupsetdependency.md)
Removes a dependency from a group set.

### [Remove-ClusterNode](./remove-clusternode.md)
Removes a node from a failover cluster.

### [Remove-ClusterResource](./remove-clusterresource.md)
Removes a clustered resource from the failover cluster.

### [Remove-ClusterResourceDependency](./remove-clusterresourcedependency.md)
Removes a dependency between two resources in a clustered role within a failover cluster.

### [Remove-ClusterResourceType](./remove-clusterresourcetype.md)
Removes a resource type from a failover cluster.

### [Remove-ClusterSharedVolume](./remove-clustersharedvolume.md)
Removes a volume from the Cluster Shared Volumes in a failover cluster, and places it in Available Storage in the cluster.

### [Remove-ClusterVMMonitoredItem](./remove-clustervmmonitoreditem.md)
Removes monitoring of a service or event that is currently being monitored on a virtual machine.

### [Repair-ClusterStorageSpacesDirect](./repair-clusterstoragespacesdirect.md)
Repairs S2D disks.

### [Reset-ClusterVMMonitoredState](./reset-clustervmmonitoredstate.md)
Resets the Application Critical state of a virtual machine, so that the virtual machine is no longer marked as being in a critical state in the cluster.

### [Resume-ClusterNode](./resume-clusternode.md)
Resumes a node from the paused state or brings back drained workloads to the node or both.

### [Resume-ClusterResource](./resume-clusterresource.md)
Turns off maintenance for a disk resource or Cluster Shared Volume within a failover cluster.

### [Set-ClusterFaultDomain](./set-clusterfaultdomain.md)
Update an existing cluster fault domain.

### [Set-ClusterFaultDomainXML](./set-clusterfaultdomainxml.md)
Sets the cluster fault domain using XML.

### [Set-ClusterGroupSet](./set-clustergroupset.md)
Updates a cluster group set.

### [Set-ClusterLog](./set-clusterlog.md)
Sets the size and level of detail for the cluster log.

### [Set-ClusterOwnerNode](./set-clusterownernode.md)
Specifies which nodes can own a resource in a failover cluster or specifies the order of preference among owner nodes for a clustered role, or resource group.

### [Set-ClusterParameter](./set-clusterparameter.md)
Controls specific properties of an object in a failover cluster, such as a resource, a group, or a network.

### [Set-ClusterQuorum](./set-clusterquorum.md)
Configures quorum options for a failover cluster.

### [Set-ClusterResourceDependency](./set-clusterresourcedependency.md)
Specifies the resources that a particular resource depends on within a failover cluster.

### [Set-ClusterStorageSpacesDirect](./set-clusterstoragespacesdirect.md)
Sets S2D cache parameters.

### [Set-ClusterStorageSpacesDirectDisk](./set-clusterstoragespacesdirectdisk.md)
Configures the system to enable S2D to claim or not claim specific physical disks.

### [Start-Cluster](./start-cluster.md)
Starts the Cluster service on all nodes of the cluster on which it is not yet started.

### [Start-ClusterGroup](./start-clustergroup.md)
Starts one or more clustered roles, also known as resource groups, on a failover cluster.

### [Start-ClusterNode](./start-clusternode.md)
Starts the Cluster service on a node in a failover cluster.

### [Start-ClusterResource](./start-clusterresource.md)
Brings a resource online in a failover cluster.

### [Stop-Cluster](./stop-cluster.md)
Stops the Cluster service on all nodes in a failover cluster, which will stop all services and applications configured in the cluster.

### [Stop-ClusterGroup](./stop-clustergroup.md)
Stops one or more clustered roles on a failover cluster.

### [Stop-ClusterNode](./stop-clusternode.md)
Stops the Cluster service on a node in a failover cluster.

### [Stop-ClusterResource](./stop-clusterresource.md)
Takes a resource offline in a failover cluster.

### [Suspend-ClusterNode](./suspend-clusternode.md)
Suspends activity on a failover cluster node, that is, pauses the node.

### [Suspend-ClusterResource](./suspend-clusterresource.md)
Turns on maintenance for a disk resource or CSV so that you can run a disk maintenance tool without triggering failover.

### [Test-Cluster](./test-cluster.md)
Runs validation tests for failover cluster hardware and settings.

### [Test-ClusterResourceFailure](./test-clusterresourcefailure.md)
Simulates a failure of a cluster resource.

### [Update-ClusterFunctionalLevel](./update-clusterfunctionallevel.md)
Updates the functional level of a mixed-version cluster.

### [Update-ClusterIPResource](./update-clusteripresource.md)
Renews or releases the DHCP lease for an IP address resource in a failover cluster.

### [Update-ClusterNetworkNameResource](./update-clusternetworknameresource.md)
Registers existing Network Name resources with a DNS server in a way that does not interrupt cluster availability.

### [Update-ClusterVirtualMachineConfiguration](./update-clustervirtualmachineconfiguration.md)
Refreshes the configuration of a clustered virtual machine within a failover cluster.





