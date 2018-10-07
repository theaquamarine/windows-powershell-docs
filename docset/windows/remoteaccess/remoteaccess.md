---
ms.mktglfcycl: manage
ms.sitesec: library
ms.author: coreyp
Module Name: RemoteAccess
Module Guid: D9D222A9-756C-41F8-B23A-2A596093216B
Download Help Link: http://go.microsoft.com/fwlink/?linkid=390819
Help Version: 5.0.1.1
Locale: en-US
title: RemoteAccess
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
keywords: powershell, cmdlet
author: coreyp-at-msft
manager: jasgro
ms.date: 12/20/2016
ms.topic: reference
ms.prod: w10
ms.technology: powershell-windows
ms.assetid: 6A012DA3-8BD5-4EC5-8CF6-75A3F1C00430
---

# RemoteAccess Module
## Description
This reference provides cmdlet descriptions and syntax for all Remote Access-specific cmdlets. It lists the cmdlets in alphabetical order based on the verb at the beginning of the cmdlet.

## RemoteAccess Cmdlets
### [Add-BgpCustomRoute](./add-bgpcustomroute.md)
Adds custom routes to the BGP routing table.

### [Add-BgpPeer](./add-bgppeer.md)
Adds a new BGP peer.

### [Add-BgpRouteAggregate](./add-bgprouteaggregate.md)
Adds a new aggregate route for specific BGP routes.

### [Add-BgpRouter](./add-bgprouter.md)
Adds a BGP router for the specified Tenant ID.

### [Add-BgpRoutingPolicy](./add-bgproutingpolicy.md)
Adds a BGP routing policy to the policy store.

### [Add-BgpRoutingPolicyForPeer](./add-bgproutingpolicyforpeer.md)
Adds BGP routing policies to BGP peers.

### [Add-DAAppServer](./add-daappserver.md)
Adds a new application server security group to the DirectAccess (DA) deployment, adds an application servers to an application server security group that is already part of the DirectAccess deployment, and adds or updates application server Group Policy Object (GPO) in a domain.

### [Add-DAClient](./add-daclient.md)
Adds one or more client computer security groups (SGs) to the DirectAccess (DA) deployment, adds one or more DA client Group Policy Objects (GPOs) in one or more domains, adds one or more SGs of down-level clients to the DA deployment in a multi-site deployment, or adds one or more down-level DA client GPOs in one or more domains in a multi-site deployment.

### [Add-DAClientDnsConfiguration](./add-daclientdnsconfiguration.md)
Adds the specified DNS suffix, DNS server addresses, or proxy server set to the Name Resolution Policy Table (NRPT).

### [Add-DAEntryPoint](./add-daentrypoint.md)
Adds an entry point to a multi-site deployment.

### [Add-DAMgmtServer](./add-damgmtserver.md)
Adds the specified Management servers to the DirectAccess (DA) deployment.

### [Add-RemoteAccessIpFilter](./add-remoteaccessipfilter.md)
Adds filters for traffic that passes through an interface.

### [Add-RemoteAccessLoadBalancerNode](./add-remoteaccessloadbalancernode.md)
Adds a server to the load balancing cluster.

### [Add-RemoteAccessRadius](./add-remoteaccessradius.md)
Adds a new external RADIUS server for VPN authentication, accounting for DirectAccess (DA) and VPN, or one-time password (OTP) authentication for DA.

### [Add-VpnIPAddressRange](./add-vpnipaddressrange.md)
Adds a new IPv4 address range from which IPv4 addresses can be assigned to VPN clients.

### [Add-VpnS2SInterface](./Add-VpnS2SInterface.md)
Create a S2S interface with the specified parameters.

### [Add-VpnSstpProxyRule](./add-vpnsstpproxyrule.md)
Adds a tenant ID to gateway mapping.

### [Clear-BgpRouteFlapDampening](./clear-bgprouteflapdampening.md)
Clears the route flap dampening information for the specified set of BGP routes.

### [Clear-RemoteAccessInboxAccountingStore](./clear-remoteaccessinboxaccountingstore.md)
Clears the inbox accounting store for the specified time period.

### [Clear-VpnS2SInterfaceStatistics](./Clear-VpnS2SInterfaceStatistics.md)
Clears statistics for a site-to-site (S2S) interface.

### [Connect-VpnS2SInterface](./Connect-VpnS2SInterface.md)
Connects a site-to-site (S2S) interface that is currently not connected.

### [Disable-BgpRouteFlapDampening](./disable-bgprouteflapdampening.md)
Disables route dampening for the flapping BGP routes.

### [Disable-DAMultiSite](./disable-damultisite.md)
Disables a multi-site deployment that contains a single entry point.

### [Disable-DAOtpAuthentication](./disable-daotpauthentication.md)
Disables one-time password (OTP) authentication for DirectAccess (DA) users.

### [Disable-RemoteAccessRoutingDomain](./disable-remoteaccessroutingdomain.md)
Disables remote access functions for a routing domain.

### [Disconnect-VpnS2SInterface](./Disconnect-VpnS2SInterface.md)
Disconnect a site-to-site (S2S) interface that is currently connected.

### [Disconnect-VpnUser](./disconnect-vpnuser.md)
Disconnects a VPN connection originated by a specific user or originating from a specific client computer.

### [Enable-BgpRouteFlapDampening](./enable-bgprouteflapdampening.md)
Enables route dampening for the flapping BGP routes.

### [Enable-DAMultiSite](./enable-damultisite.md)
Enables and configures a multi-site deployment, and adds the first entry point.

### [Enable-DAOtpAuthentication](./enable-daotpauthentication.md)
Enables and configures one-time password (OTP) authentication for DirectAccess (DA) users.

### [Enable-RemoteAccessRoutingDomain](./enable-remoteaccessroutingdomain.md)
Enables VPN or S2S functions for a specified routing domain.

### [Get-BgpCustomRoute](./get-bgpcustomroute.md)
Gets custom route information from the BGP router.

### [Get-BgpPeer](./get-bgppeer.md)
Gets configuration information for BGP peers.

### [Get-BgpRouteAggregate](./get-bgprouteaggregate.md)
Gets all the aggregate BGP routes configured by the administrator.

### [Get-BgpRouteFlapDampening](./get-bgprouteflapdampening.md)
Retrieves the configuration of a BGP route dampening engine.

### [Get-BgpRouteInformation](./get-bgprouteinformation.md)
Retrieves BGP route information for one or more network prefixes from the BGP routing table.

### [Get-BgpRouter](./get-bgprouter.md)
Gets configuration information for BGP routers.

### [Get-BgpRoutingPolicy](./get-bgproutingpolicy.md)
Gets configuration information of BGP routing policies.

### [Get-BgpStatistics](./get-bgpstatistics.md)
Retrieves BGP peering-related message and route advertisement statistics.

### [Get-DAAppServer](./get-daappserver.md)
Displays the list of application server security groups that are part of the DirectAccess (DA) deployment and the properties of the connections made to the application servers in the groups.

### [Get-DAClient](./get-daclient.md)
Displays the list of client security groups that are part of the DirectAccess (DA) deployment and the client properties.

### [Get-DAClientDnsConfiguration](./get-daclientdnsconfiguration.md)
Displays all the Name Resolution Policy Table (NRPT) entries and the local name resolution property.

### [Get-DAEntryPoint](./get-daentrypoint.md)
Displays the settings for an entry point.

### [Get-DAEntryPointDC](./get-daentrypointdc.md)
Retrieves a list of entry points and the associated domain controllers (DCs).

### [Get-DAMgmtServer](./get-damgmtserver.md)
Displays the configured management servers.

### [Get-DAMultiSite](./get-damultisite.md)
Retrieves global settings applied to all entry points in a multi-site deployment.

### [Get-DANetworkLocationServer](./get-danetworklocationserver.md)
Displays the detailed Network Location Server (NLS) configuration.

### [Get-DAOtpAuthentication](./get-daotpauthentication.md)
Displays one-time password (OTP) authentication settings for DirectAccess (DA).

### [Get-DAServer](./get-daserver.md)
Displays the properties of the DirectAccess (DA) server.

### [Get-RemoteAccess](./get-remoteaccess.md)
Displays the configuration of DirectAccess (DA) and VPN (both Remote Access VPN and site-to-site VPN).

### [Get-RemoteAccessAccounting](./get-remoteaccessaccounting.md)
Displays the accounting configuration for Remote Access, such as the different types of accounting that are enabled and the respective configuration.

### [Get-RemoteAccessConfiguration](./get-remoteaccessconfiguration.md)
Retrieves the remote access configuration.

### [Get-RemoteAccessConnectionStatistics](./get-remoteaccessconnectionstatistics.md)
Displays the statistics of real-time, currently active DirectAccess (DA) and VPN connections and the statistics of DA and VPN historical connections for a specified time duration.

### [Get-RemoteAccessConnectionStatisticsSummary](./get-remoteaccessconnectionstatisticssummary.md)
Displays the summary statistics of real-time, currently active DirectAccess (DA) and VPN connections and the summary statistics of DA and VPN historical connections for a specified time duration.

### [Get-RemoteAccessHealth](./get-remoteaccesshealth.md)
Obtains the current health of a RemoteAccess (RA) deployment.

### [Get-RemoteAccessIpFilter](./get-remoteaccessipfilter.md)
Retrieves IP filters on an interface.

### [Get-RemoteAccessLoadBalancer](./get-remoteaccessloadbalancer.md)
Displays load balanced cluster settings.

### [Get-RemoteAccessRadius](./get-remoteaccessradius.md)
Displays the list of RADIUS servers including RADIUS for VPN authentication, RADIUS for DirectAccess (DA) and VPN Accounting, and RADIUS for one-time password (OTP) authentication for DA.

### [Get-RemoteAccessRoutingDomain](./get-remoteaccessroutingdomain.md)
Retrieves configuration information for a routing domain.

### [Get-RemoteAccessUserActivity](./get-remoteaccessuseractivity.md)
Displays the resources accessed over the active DirectAccess (DA) and VPN connections and the resources accessed over historical DA and VPN connections.

### [Get-RoutingProtocolPreference](./get-routingprotocolpreference.md)
Displays preferences for routing protocols.

### [Get-VpnAuthProtocol](./get-vpnauthprotocol.md)
Retrieves authentication parameters configured on a VPN server.

### [Get-VpnS2SInterface](./Get-VpnS2SInterface.md)
Retrieves configuration details for a site-to-site (S2S) interface.

### [Get-VpnS2SInterfaceStatistics](./Get-VpnS2SInterfaceStatistics.md)
Retrieves statistics of a site-to-site (S2S) interface.

### [Get-VpnServerConfiguration](./get-vpnserverconfiguration.md)
Gets VPN server properties.

### [Get-VpnSstpProxyRule](./get-vpnsstpproxyrule.md)
Retrieves the Tenant ID to gateway mapping.

### [Install-RemoteAccess](./install-remoteaccess.md)
Performs prerequisite checks for DirectAccess (DA) to ensure that it can be installed, installs DA for remote access (RA) (includes management of remote clients) or for management of remote clients only, installs VPN (both Remote Access VPN and site-to-site VPN), and installs Border Gateway Protocol Routing..

### [New-VpnSstpProxyRule](./new-vpnsstpproxyrule.md)
Creates a tenant ID to gateway mapping object.

### [New-VpnTrafficSelector](./new-vpntrafficselector.md)
Creates a VPN Traffic selector object that configures the IKE traffic selector.

### [Remove-BgpCustomRoute](./remove-bgpcustomroute.md)
Removes custom routes from the BGP router.

### [Remove-BgpPeer](./remove-bgppeer.md)
Removes BGP peers from a router.

### [Remove-BgpRouteAggregate](./remove-bgprouteaggregate.md)
Removes the set of specified aggregate BGP routes.

### [Remove-BgpRouter](./remove-bgprouter.md)
Removes a BGP router.

### [Remove-BgpRoutingPolicy](./remove-bgproutingpolicy.md)
Removes routing policies from the policy store.

### [Remove-BgpRoutingPolicyForPeer](./remove-bgproutingpolicyforpeer.md)
Removes routing policies from BGP peers.

### [Remove-DAAppServer](./remove-daappserver.md)
Removes the specified list of application server security groups (SGs) from the DirectAccess (DA) deployment, removes the specified application servers from the specified DA application server SG,and removes the application server Group Policy Objects (GPOs) in the specified domains.

### [Remove-DAClient](./remove-daclient.md)
Removes one or more client computer security groups (SGs) from the DirectAccess (DA) deployment, removes one or more DA client Group Policy Objects (GPOs) from domains, removes one or more SGs of down-level clients (down-level clients can connect only to the specified site) from the DA deployment in a multi-site deployment, and removes one or more down-level DA client GPOs from domains in a multi-site deployment.

### [Remove-DAClientDnsConfiguration](./remove-daclientdnsconfiguration.md)
Removes the Name Resolution Policy Table (NRPT) entry corresponding to the specified DNS suffix from the NRPT.

### [Remove-DAEntryPoint](./remove-daentrypoint.md)
Removes an entry point from a multi-site deployment.

### [Remove-DAMgmtServer](./remove-damgmtserver.md)
Removes the specified management servers from the DirectAccess (DA) deployment.

### [Remove-RemoteAccessIpFilter](./remove-remoteaccessipfilter.md)
Removes an IP filter for an interface.

### [Remove-RemoteAccessLoadBalancerNode](./remove-remoteaccessloadbalancernode.md)
Removes a server from the network load balancing (NLB) cluster.

### [Remove-RemoteAccessRadius](./remove-remoteaccessradius.md)
Removes an external RADIUS server from being used for VPN authentication, accounting for both DirectAccess (DA) and VPN, or one-time password (OTP) authentication for DA.

### [Remove-VpnIPAddressRange](./remove-vpnipaddressrange.md)
Removes an existing IPv4 address range from the pool for IP address assignment.

### [Remove-VpnS2SInterface](./Remove-VpnS2SInterface.md)
Removes a specified site-to-site (S2S) interface.

### [Remove-VpnSstpProxyRule](./remove-vpnsstpproxyrule.md)
Removes one or more tenant IDs to gateway mappings for SSTP proxy.

### [Set-BgpPeer](./set-bgppeer.md)
Updates the configuration of the specified BGP peer.

### [Set-BgpRouteAggregate](./set-bgprouteaggregate.md)
Updates the properties of specified aggregate BGP route.

### [Set-BgpRouteFlapDampening](./set-bgprouteflapdampening.md)
Configures the BGP route dampening engine.

### [Set-BgpRouter](./set-bgprouter.md)
Updates the configuration of the local BGP router for the specified tenant ID.

### [Set-BgpRoutingPolicy](./set-bgproutingpolicy.md)
Modifies a routing policy configuration.

### [Set-BgpRoutingPolicyForPeer](./set-bgproutingpolicyforpeer.md)
Modifies BGP routing policies for BGP peers.

### [Set-DAAppServerConnection](./set-daappserverconnection.md)
Configures the properties of the connection to application servers and the IPsec security traffic protection policies for the connection.

### [Set-DAClient](./set-daclient.md)
Configures the properties related to a DirectAccess (DA) client.

### [Set-DAClientDnsConfiguration](./set-daclientdnsconfiguration.md)
Configures the DNS server and proxy server addresses of a Name Resolution Policy Table (NRPT) entry and configures the local name resolution property.

### [Set-DAEntryPoint](./set-daentrypoint.md)
Configures settings for the entry point.

### [Set-DAEntryPointDC](./set-daentrypointdc.md)
Modifies domain controller (DC) settings for the entry point.

### [Set-DAMultiSite](./set-damultisite.md)
Configures global settings for all entry points in a multi-site deployment.

### [Set-DANetworkLocationServer](./set-danetworklocationserver.md)
Configures the Network Location Server (NLS).

### [Set-DAOtpAuthentication](./set-daotpauthentication.md)
Configures one-time password (OTP) authentication settings for DirectAccess (DA).

### [Set-DAServer](./set-daserver.md)
Sets the properties specific to the DirectAccess (DA) server.

### [Set-RemoteAccess](./set-remoteaccess.md)
Modifies the configuration that is common to both DirectAccess (DA) and VPN such SSL certificate, Internal interface, and Internet interface.

### [Set-RemoteAccessAccounting](./set-remoteaccessaccounting.md)
Sets the enabled state for inbox and RADIUS accounting for both external RADIUS and Windows accounting and configures the settings when enabled.

### [Set-RemoteAccessConfiguration](./set-remoteaccessconfiguration.md)
Modifies the configuration of a remote access role.

### [Set-RemoteAccessInboxAccountingStore](./set-remoteaccessinboxaccountingstore.md)
Modifies the size of the inbox accounting store.

### [Set-RemoteAccessIpFilter](./set-remoteaccessipfilter.md)
Modifies IP filter action.

### [Set-RemoteAccessLoadBalancer](./set-remoteaccessloadbalancer.md)
Configures load balancing on the Remote Access (RA) server or the cluster server.

### [Set-RemoteAccessRadius](./set-remoteaccessradius.md)
Edits the properties associated with an external RADIUS server being used for VPN authentication, accounting for DirectAccess (DA) and VPN, and one-time password (OTP) authentication for DA.

### [Set-RemoteAccessRoutingDomain](./set-remoteaccessroutingdomain.md)
Configures S2S VPN settings for a routing domain configuration.

### [Set-RoutingProtocolPreference](./set-routingprotocolpreference.md)
Configures preferences for routing protocols.

### [Set-VpnAuthProtocol](./set-vpnauthprotocol.md)
Configures the authentication method for incoming site-to-site (S2S) VPN interfaces on a Routing and Remote Access (RRAS) server.

### [Set-VpnAuthType](./set-vpnauthtype.md)
Sets the authentication type to be used for connecting to a VPN.

### [Set-VpnIPAddressAssignment](./set-vpnipaddressassignment.md)
Configures the IPv4 address assignment method or the IPv6 prefix for IPv6 address assignment.

### [Set-VpnS2SInterface](./Set-VpnS2SInterface.md)
Updates parameters for an S2S Interface.

### [Set-VpnServerConfiguration](./set-vpnserverconfiguration.md)
Updates S2S server parameters.

### [Set-VpnSstpProxyRule](./set-vpnsstpproxyrule.md)
This cmdlet updates the tenant ID to gateway mapping for SSTP Proxy.

### [Start-BgpPeer](./start-bgppeer.md)
Starts routing sessions for BGP peers.

### [Stop-BgpPeer](./stop-bgppeer.md)
Stops routing sessions for BGP peers.

### [Uninstall-RemoteAccess](./uninstall-remoteaccess.md)
Uninstalls DirectAccess (DA) and VPN, both Remote Access (RA) VPN and site-to-site VPN.

### [Update-DAMgmtServer](./update-damgmtserver.md)
Updates the list of Management servers of the DirectAccess (DA) deployment.



