
# Microsoft 365 URL List

This page is similar to the Office 365 URLs list, but includes additional details around Intune, Teams Room Premium as well as URLs for specific vendor-related Teams MTRs, Phones, and other devices.

## Microsoft Teams (& Skype for Business)
The following list contains IPs and URLs that Teams and Skype for Business use.

Note that <b> ER </b> Stands for Express Route.

Any category marked as Required must be allowed through your corporate firewall/proxy for the service to function correctly.

| ID    | Category         | ER | Addresses                                                    | Ports                       |
|:------|------------------| -- | -------------------------------------------------------------| --------------------------- |
|     11| Optimize Required| Yes| 13.107.64.0/18<br> 52.112.0.0/14<br> 52.122.0.0/15<br> 2603:1063::/38| UDP: 3478<br> 3479<br> 3480<br> 3481  |
|     12| Allow Required   | Yes| *.lync.com<br> *.teams.microsoft.com<br> teams.microsoft.com 13.107.64.0/18<br> 52.112.0.0/14<br> 52.122.0.0/15<br> 52.238.119.141/32<br> 52.244.160.207/32<br> 2603:1027::/48<br> 2603:1037::/48<br> 2603:1047::/48<br> 2603:1057::/48<br> 2603:1063::/38<br> 2620:1ec:6::/48<br> 2620:1ec:40::/42| TCP: 443, 80 |
|     13| Allow Required   | Yes| *.broadcast.skype.com<br> broadcast.skype.com 13.107.64.0/18<br> 52.112.0.0/14<br> 52.122.0.0/15<br> 52.238.119.141/32<br> 52.244.160.207/32<br> 2603:1027::/48<br> 2603:1037::/48<br> 2603:1047::/48<br> 2603:1057::/48<br> 2603:1063::/38<br> 2620:1ec:6::/48<br> 2620:1ec:40::/42| TCP: 443 |
|     15| Default Required | No | *.sfbassets.com | TCP: 443, 80 |
|     16| Default Required | No | *.keydelivery.mediaservices.windows.net<br> *.streaming.mediaservices.windows.net<br> mlccdn.blob.core.windows.net| TCP:443|
|     17| Default Required | No | aka.ms | TCP: 443 |
|     18| Default Optional. <br></br><b> Notes:</b> Federation with Skype and public IM connectivity: Contact picture retrieval | No | *.users.storage.live.com | TCP: 443 |
|     19| Default Optional. <br></br><b> Notes:</b> Applies only to those who deploy the Conference Room Systems. | No | *.adl.windows.com | TCP: 443, 80|
|     22| Allow Optional. <br></br><b> Notes:</b> Teams: Messaging interop with Skype for Business. | Yes | *.skypeforbusiness.com 13.107.64.0/18<br> 52.112.0.0/14<br> 52.122.0.0/15<br> 52.238.119.141/32<br> 52.244.160.207/32<br> 2603:1027::/48<br> 2603:1037::/48<br> 2603:1047::/48<br> 2603:1057::/48<br> 2603:1063::/38<br> 2620:1ec:6::/48<br> 2620:1ec:40::/42 | TCP: 443 |
|     26| Default Optional. <br></br><b> Notes:</b> Wildcard being moved to optional prior to being removed. | No| *.msedge.net | TCP: 443|
|     27| Default Required | No | *.mstea.ms<br> *.secure.skypeassets.com<br> mlccdnprod.azureedge.net | TCP: 443|
|    127| Default Required | No | *.skype.com | TCP: 443, 80 |
|    180| Default Requried | No | compass-ssl.microsoft.com | TCP:443|

## Microsoft 365 Common
The following list contains IPs and URLs that are common to all Office 365 services, including Teams and Skype for Business.

Note that <b> ER </b> Stands for Express Route.

Any category marked as Required must be allowed through your corporate firewall/proxy for the service to function correctly.

| ID    | Category         | ER | Addresses                                                    | Ports                       |
|:------|------------------| -- | -------------------------------------------------------------| --------------------------- |
| 41 | Default Optional. <br></br><b> Notes:</b> Microsoft Stream | No | *.microsoftstream.com | TCP: 443|
| 43 | Default Optional. <br></br><b> Notes:</b> Microsoft Stream 3rd party integration (including CDNs) | No | nps.onyx.azure.net | TCP: 443 |
| 44 | Default Optional. <br></br><b> Notes:</b> Microsoft Stream - unauthenticated | No | *.azureedge.net<br> *.media.azure.net<br> *.streaming.mediaservices.windows.net | TCP: 443|
| 45 | Default Optional. <br></br><b> Notes:</b> Microsoft Stream | No | *.keydelivery.mediaservices.windows.net | TCP: 443 |
| 46 | Allow Required | Yes | *.officeapps.live.com<br> *.online.office.com<br> office.live.com<br> 13.107.6.171/32<br> 13.107.18.15/32<br> 13.107.140.6/32<br> 52.108.0.0/14<br> 52.238.106.116/32<br> 52.244.37.168/32<br> 52.244.203.72/32<br> 52.244.207.172/32<br> 52.244.223.198/32<br> 52.247.150.191/32<br> 2603:1010:2::cb/128<br> 2603:1010:200::c7/128<br> 2603:1020:200::682f:a0fd/128<br> 2603:1020:201:9::c6/128<br> 2603:1020:600::a1/128<br> 2603:1020:700::a2/128<br> 2603:1020:800:2::6/128<br> 2603:1020:900::8/128<br> 2603:1030:7::749/128<br> 2603:1030:800:5::bfee:ad3c/128<br> 2603:1030:f00::17/128<br> 2603:1030:1000::21a/128<br> 2603:1040:200::4f3/128<br> 2603:1040:401::762/128<br> 2603:1040:601::60f/128<br> 2603:1040:a01::1e/128<br> 2603:1040:c01::28/128<br> 2603:1040:e00:1::2f/128<br> 2603:1040:f00::1f/128<br> 2603:1050:1::cd/128<br> 2620:1ec:c::15/128<br> 2620:1ec:8fc::6/128<br> 2620:1ec:a92::171/128<br> 2a01:111:f100:2000::a83e:3019/128<br> 2a01:111:f100:2002::8975:2d79/128<br> 2a01:111:f100:2002::8975:2da8/128<br> 2a01:111:f100:7000::6fdd:6cd5/128<br> 2a01:111:f100:a004::bfeb:88cf/128 | TCP: 443, 80|
| 47 | Default Required | No | *.office.net | TCP:443<br> 80 |
| 49 | Default Required | No | *.onenote.com | TCP: 443 |
| 50 | Default Optional. <br></br><b> Notes:</b> OneNote notebooks (wildcards) | No | *.microsoft.com | TCP: 443 | 
| 51 | Default Required | No | *cdn.onenote.net | TCP: 443 |
| 53 | Default Required | No | ajax.aspnetcdn.com<br> apis.live.net<br> officeapps.live.com<br> ww<span></span><span></span>w.onedrive.com | TCP: 443 |
| 56 | Allow Required | Yes | *.auth.microsoft.com<br> *.msftidentity.com<br> *.msidentity.com<br> account.activedirectory.windowsazure.com<br> accounts.accesscontrol.windows.net<br> adminwebservice.microsoftonline.com<br> api.passwordreset.microsoftonline.com<br> autologon.microsoftazuread-sso.com<br> becws.microsoftonline.com<br> ccs.login.microsoftonline.com<br> clientconfig.microsoftonline-p.net<br> companymanager.microsoftonline.com<br> device.login.microsoftonline.com<br> graph.microsoft.com<br> graph.windows.net<br> login.microsoft.com<br> login.microsoftonline.com<br> login.microsoftonline-p.com<br> login.windows.net<br> logincert.microsoftonline.com<br> loginex.microsoftonline.com<br> login-us.microsoftonline.com<br> nexus.microsoftonline-p.com<br> passwordreset.microsoftonline.com<br> provisioningapi.microsoftonline.com<br> 20.190.128.0/18<br> 40.126.0.0/18<br> 2603:1006:2000::/48<br> 2603:1007:200::/48<br> 2603:1016:1400::/48<br> 2603:1017::/48<br> 2603:1026:3000::/48<br> 2603:1027:1::/48<br> 2603:1036:3000::/48<br> 2603:1037:1::/48<br> 2603:1046:2000::/48<br> 2603:1047:1::/48<br> 2603:1056:2000::/48<br> 2603:1057:2::/48 | TCP: 443, 80 |
| 59 | Default Required | No | *.hip.live.com<br> *.microsoftonline.com<br> *.microsoftonline-p.com<br> *.msauth.net<br> *.msauthimages.net<br> *.msecnd.net<br> *.msftauth.net<br> *.msftauthimages.net<br> *.phonefactor.net<br> enterpriseregistration.windows.net<br> management.azure.com<br> policykeyservice.dc.ad.msft.net | TCP: 443, 80 |
| 64 | Allow Required | Yes | *.compliance.microsoft.com<br> *.protection.office.com<br> *.security.microsoft.com<br> compliance.microsoft.com<br> defender.microsoft.com<br> protection.office.com<br> security.microsoft.com<br> 52.108.0.0/14<br> 2603:1006:1400::/40<br> 2603:1016:2400::/40<br> 2603:1026:2400::/40<br> 2603:1036:2400::/40<br> 2603:1046:1400::/40<br> 2603:1056:1400::/40<br> 2a01:111:200a:<zero-width space>a::/64<br> 2a01:111:2035:8::/64<br> 2a01:111:f406:1::/64<br> 2a01:111:f406:c00::/64<br> 2a01:111:f406:1004::/64<br> 2a01:111:f406:1805::/64<br> 2a01:111:f406:3404::/64<br> 2a01:111:f406:8000::/64<br> 2a01:111:f406:8801::/64<br> 2a01:111:f406:a003::/64 | TCP: 443 |
| 65 | Allow Required | Yes | account.office.net<br> 52.108.0.0/14<br> 2603:1006:1400::/40<br> 2603:1016:2400::/40<br> 2603:1026:2400::/40<br> 2603:1036:2400::/40<br> 2603:1046:1400::/40<br> 2603:1056:1400::/40<br> '2a01:111:200a:<zero-width space>a::/64'<br> 2a01:111:2035:8::/64<br> 2a01:111:f406:1::/64<br> 2a01:111:f406:c00::/64<br> 2a01:111:f406:1004::/64<br> 2a01:111:f406:1805::/64<br> 2a01:111:f406:3404::/64<br> 2a01:111:f406:8000::/64<br> 2a01:111:f406:8801::/64<br> 2a01:111:f406:a003::/64 | TCP: 443, 80 |
| 66 | Default Required | No | *.portal.cloudappsecurity.com | TCP: 443 |
| 67 | Default Optional. <br></br><b> Notes:</b> Security and Compliance Center eDiscovery export | No | *.blob.core.windows.net | TCP: 443 |
| 68 | Default Optional. <br></br><b> Notes:</b> Portal and shared: 3rd party office integration. (including CDNs) | No | firstpartyapps.oaspapps.com<br> prod.firstpartyapps.oaspapps.com.akadns.net<br> telemetryservice.firstpartyapps.oaspapps.com<br> wus-firstpartyapps.oaspapps.com | TCP: 443 |
| 69 | Default Required | No | *.aria.microsoft.com<br> *.events.data.microsoft.com | TCP: 443 |
| 70 | Default Required | No | *.o365weve.com<br> amp.azure.net<br> appsforoffice.microsoft.com<br> assets.onestore.ms<br> auth.gfx.ms<br> c1.microsoft.com<br> dgps.support.microsoft.com<br> docs.microsoft.com<br> msdn.microsoft.com<br> platform.linkedin.com<br> prod.msocdn.com<br> shellprod.msocdn.com<br> support.microsoft.com<br> technet.microsoft.com | TCP: 443 |
| 71 | Default Required | No | *.office365.com | TCP: 443, 80 |
| 72 | Default Optional. <br></br><b> Notes:</b> Azure Rights Management (RMS) with Office 2010 clients | No | *.cloudapp.net | TCP: 443 |
| 73 | Default Required | No | *.aadrm.com<br> *.azurerms.com<br> *.informationprotection.azure.com<br> ecn.dev.virtualearth.net<br> informationprotection.hosting.portal.azure.net | TCP: 443 |
| 75 | Default Optional. <br></br><b> Notes:</b> Graph.windows.net<br> Office 365 Management Pack for Operations Manager<br> SecureScore<br> Azure AD Device Registration<br> Forms<br> StaffHub<br> Application Insights<br> captcha services | No | *.sharepointonline.com<br> dc.services.visualstudio.com<br> mem.gfx.ms<br> staffhub.ms | TCP: 443 |
| 78 | Default Optional. <br></br><b> Notes:</b> Some Office 365 features require endpoints within these domains (including CDNs). Many specific FQDNs within these wildcards have been published recently as we work to either remove or better explain our guidance relating to these wildcards. | No | *.microsoft.com<br> *.msocdn.com<br> *.onmicrosoft.com | TCP: 443, 80 |
| 79 | Default Required | No | o15.officeredir.microsoft.com<br> officepreviewredir.microsoft.com<br> officeredir.microsoft.com<br> r.office.microsoft.com | TCP: 443, 80 |
| 83 | Default Required | No | activation.sls.microsoft.com | TCP: 443 |
| 84 | Default Required | No | crl.microsoft.com | TCP: 443, 80 |
| 86 | Default Required | No | office15client.microsoft.com<br> officeclient.microsoft.com | TCP: 443 |
| 89 | Default Required | No | go.microsoft.com | TCP: 443, 80
| 91 | Default Required | No | ajax.aspnetcdn.com<br> cdn.odc.officeapps.live.com | TCP: 443: 80 |
| 92 | Default Required | No | officecdn.microsoft.com<br> officecdn.microsoft.com.edgesuite.net | TCP: 443, 80 |
| 93 | Default Optional. <br></br><b> Notes:</b> ProPlus: auxiliary URLs | No | *.virtualearth.net<br> c.bing.net<br> excelbingmap.firstpartyapps.oaspapps.com<br> ocos-office365-s2s.msedge.net<br> peoplegraph.firstpartyapps.oaspapps.com<br> tse1.mm.bing.net<br> wikipedia.firstpartyapps.oaspapps.com<br> ww<span></span><span></span>w.bing.com | TCP: 443, 80 |
| 95 | Default Optional. <br></br><b> Notes:</b> Outlook for Android and iOS | No | *.acompli.net<br> *.outlookmobile.com | TCP: 443 |
| 96 | Default Optional. <br></br><b> Notes:</b> Outlook for Android and iOS: Authentication | No | login.windows-ppe.net | TCP: 443 |
| 97 | Default Optional. <br></br><b> Notes:</b> Outlook for Android and iOS: Consumer Outlook.com and OneDrive integration | No | account.live.com<br> login.live.com | TCP: 443 |
| 105 | Default Optional. <br></br><b> Notes:</b> Outlook for Android and iOS: Outlook Privacy | No | ww<span></span><span></span>w.acompli.com | TCP: 443 |
| 114 | Default Optional. <br></br><b> Notes:</b> Office Mobile URLs | No | *.appex.bing.com<br> *.appex-rf.msn.com<br> c.bing.com<br> c.live.com<br> d.docs.live.net<br> directory.services.live.com<br> docs.live.net<br> partnerservices.getmicrosoftkey.com<br> signup.live.com | TCP: 443, 80 |
| 116 | Default Optional. <br></br><b> Notes:</b> Office for iPad URLs | No | account.live.com<br> auth.gfx.ms<br> login.live.com | TCP: 443. 80 |
| 117 | Default Optional. <br></br><b> Notes:</b> Yammer | No | *.yammer.com<br> *.yammerusercontent.com | TCP: 443 |
| 118 | Default Optional. <br></br><b> Notes:</b> Yammer CDN | No | *.assets-yammer.com | TCP: 443 |
| 121 | Default Optional. <br></br><b> Notes:</b> Planner: auxiliary URLs | No | ww<span></span><span></span>w.outlook.com | TCP: 443, 80 |
| 122 | Default Optional. <br></br><b> Notes:</b> Sway CDNs | No | eus-ww<span></span><span></span>w.sway-cdn.com<br> eus-ww<span></span><span></span>w.sway-extensions.com<br> wus-ww<span></span><span></span>w.sway-cdn.com<br> wus-ww<span></span><span></span>w.sway-extensions.com | TCP: 443 |
| 124 | Default Optional. <br></br><b> Notes:</b> Sway | No | sway.com<br> ww<span></span><span></span>w.sway.com | TCP: 443 | 
| 125 | Default Required | No | *.entrust.net<br> *.geotrust.com<br> *.omniroot.com<br> *.public-trust.com<br> *.symcb.com<br> *.symcd.com<br> *.verisign.com<br> *.verisign.net<br> apps.identrust.com<br> cacerts.digicert.com<br> cert.int-x3.letsencrypt.org<br> crl.globalsign.com<br> crl.globalsign.net<br> crl.identrust.com<br> crl3.digicert.com<br> crl4.digicert.com<br> isrg.trustid.ocsp.identrust.com<br> mscrl.microsoft.com<br> ocsp.digicert.com<br> ocsp.globalsign.com<br> ocsp.msocsp.com<br> ocsp2.globalsign.com<br> ocspx.digicert.com<br> secure.globalsign.com<br> ww<span></span><span></span>w.digicert.com<br> ww<span></span><span></span>w.microsoft.com | TCP: 443, 80 |
| 126 | Default Optional. <br></br><b> Notes:</b> <br></br><b> Notes:</b> Connection to the speech service is required for Office Dictation features. If connectivity is not allowed<br> Dictation will be disabled. | No | officespeech.platform.bing.com | TCP: 443 |
| 128 | Default Required | No | *.manage.microsoft.com | TCP: 443 |
| 147 | Default Requried | No | *.office.com | TCP: 443, 80 |
| 148 | Default Required | No | cdnprod.myanalytics.microsoft.com<br> myanalytics.microsoft.com<br> myanalytics-gcc.microsoft.com | TCP: 443, 80 |
| 152 | Default Optional. <br></br><b> Notes:</b> These endpoints enables the Office Scripts functionality in Office clients available through the Automate tab.  This feature can also be disabled through the Office 365 Admin portal. | No | *.microsoftusercontent.com | TCP: 443 |
| 153 | Default Required | No | *.azure-apim.net<br> *.flow.microsoft.com<br> *.powerapps.com | TCP: 443 |
| 156 | Default Required | No | *.activity.windows.com<br> activity.windows.com | TCP: 80 |
| 157 | Default Required | No | ocsp.int-x3.letsencrypt.org | TCP: 80 |
| 158 | Default Required | No | *.cortana.ai | TCP: 443 |
| 159 | Default Required | No | admin.microsoft.com | TCP: 443, 80 |
| 160 | Default Required | No | cdn.odc.officeapps.live.com<br> cdn.uci.officeapps.live.com | TCP: 443, 80 |

## Microsoft Intune
The following list contains IPs and URLs that allow Teams devices to communicate with the Intune service.

Note that <b> ER </b> Stands for Express Route.

Any category marked as Required must be allowed through your corporate firewall/proxy for the service to function correctly.

| Domain(s)    | IP Address(es)  |
|:------|------------------|
| login.microsoftonline.com<br> *.officeconfig.msocdn.com<br> config.office.com<br> graph.windows.net<br> enterpriseregistration.windows.net<br> | |
| *.manage.microsoft.com<br>  manage.microsoft.com<br> | 20.43.129.0/24<br> 20.44.19.224/27<br> 20.49.93.160/27<br> 40.119.8.128/25<br> 40.67.121.224/27<br> 40.70.151.32/28<br> 40.71.14.96/28<br> 40.74.25.0/24<br> 40.78.245.240/28<br> 40.78.247.128/27<br> 40.79.197.64/27<br> 40.79.197.96/28<br> 40.80.180.208/28<br> 40.80.180.224/27<br> 40.80.184.128/25<br> 40.82.248.224/28<br> 40.82.249.128/25<br> 52.150.137.0/25<br> 52.162.111.96/28<br> 52.168.116.128/27<br> 52.182.141.192/27<br> 52.236.189.96/27<br> 52.240.244.160/27<br> 104.214.164.192/27<br> 104.46.162.96/27<br> 13.67.13.176/28<br> 13.67.15.128/27<br> 13.69.231.128/28<br> 13.69.67.224/28<br> 13.70.78.128/28<br> 13.70.79.128/27<br> 13.71.199.64/28<br> 13.73.244.48/28<br> 13.74.111.192/27<br> 13.75.39.208/28<br> 13.77.53.176/28<br> 13.86.221.176/28<br> 13.89.174.240/28<br> 13.89.175.192/28<br> 20.189.105.0/24<br> 20.189.172.160/27<br> 20.189.229.0/25<br> 20.191.167.0/25<br> 20.37.153.0/24<br> 20.37.192.128/25<br> 20.38.81.0/24<br> 20.41.1.0/24<br> 20.42.1.0/24<br> 20.42.130.0/24<br> 20.42.224.128/25|

## Teams Room Premium
The following list contains IPs and URLs that the Teams Room Premium service uses to communicate with your Teams room devices.

Note that <b> ER </b> Stands for Express Route.

Any category marked as Required must be allowed through your corporate firewall/proxy for the service to function correctly.

| URL    |
|:------|
| agent.rooms.microsoft.com<br> global.azure-devices-provisioning.net<br> gj3ftstorage.blob.core.windows.net<br> mmrstgnoamiot.azure-devices.net<br> mmrstgnoamstor.blob.core.windows.net<br> mmrprodapaciot.azure-devices.net<br> mmrprodapacstor.blob.core.windows.net<br> mmrprodemeaiot.azure-devices.net<br> mmrprodemeastor.blob.core.windows.net<br> mmrprodnoamiot.azure-devices.net<br> mmrprodnoamstor.blob.core.windows.net |

# Vendor Specific URLs

Vendor specific URLs are additional to the above, and are required to support that vendors specific hardware (Teams Handsets and MTRs).

It is recommended that you open these URLs up on your firewall/proxy.

Note: Teams Phones and android-based room systems do not support proxy servers. The advice is to configure these devices on a separate VLAN that can access the required URLs without passing through a proxy.

## Poly
These URLs are for Poly devices (MTRs and desk phones).

| URL    |
|:------|
| ntp.polycom.com<br> api.silica-prod01.io.lens.poly.com<br> zto.poly.com<br> firebaseremoteconfig.googleapis.com<br> connectivitycheck.android.com<br> firebaseinstallations.googleapis.com<br> 0.pool.ntp.org<br> in.appcenter.ms|


## Logitech
These URLs are for Logitech devices.

| URL    |
| :------|
| sync.logitech.com<br> updates.vc.logitech.com<br> raiden.vc.logitech.com<br> svcs.vc.logitech.com|

