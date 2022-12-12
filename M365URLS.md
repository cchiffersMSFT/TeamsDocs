
# Microsoft 365 URL List

## Microsoft Teams (& Skype for Business)

| ID    | Category         | ER | Addresses                                                    | Ports                       |
|:------|------------------| -- | -------------------------------------------------------------| --------------------------- |
|     11| Optimize Required| Yes| 13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 2603:1063::/38| UDP: 3478, 3479, 3480, 3481  |
|     12| Allow Required   | Yes| *.lync.com, *.teams.microsoft.com, teams.microsoft.com 13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 52.238.119.141/32, 52.244.160.207/32, 2603:1027::/48, 2603:1037::/48, 2603:1047::/48, 2603:1057::/48, 2603:1063::/38, 2620:1ec:6::/48, 2620:1ec:40::/42| TCP: 443, 80 |
|     13| Allow Required   | Yes| *.broadcast.skype.com, broadcast.skype.com 13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 52.238.119.141/32, 52.244.160.207/32, 2603:1027::/48, 2603:1037::/48, 2603:1047::/48, 2603:1057::/48, 2603:1063::/38, 2620:1ec:6::/48, 2620:1ec:40::/42| TCP: 443 |
|     15| Default Required | No | *.sfbassets.com | TCP: 443, 80 |
|     16| Default Required | No | *.keydelivery.mediaservices.windows.net, *.streaming.mediaservices.windows.net, mlccdn.blob.core.windows.net| TCP:443|
|     17| Default Required | No | aka.ms | TCP: 443 |
|     18| Default Optional. Notes: Federation with Skype and public IM connectivity: Contact picture retrieval | No | *.users.storage.live.com | TCP: 443 |
|     19| Default Optional. Notes: Applies only to those who deploy the Conference Room Systems. | No | *.adl.windows.com | TCP: 443, 80|
|     22| Allow Optional. Notes: Teams: Messaging interop with Skype for Business. | Yes | *.skypeforbusiness.com 13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 52.238.119.141/32, 52.244.160.207/32, 2603:1027::/48, 2603:1037::/48, 2603:1047::/48, 2603:1057::/48, 2603:1063::/38, 2620:1ec:6::/48, 2620:1ec:40::/42 | TCP: 443 |
|     26| Default Optional. Notes: Wildcard being moved to optional prior to being removed. | No| *.msedge.net | TCP: 443|
|     27| Default Required | No | *.mstea.ms, *.secure.skypeassets.com, mlccdnprod.azureedge.net | TCP: 443|
|    127| Default Required | No | *.skype.com | TCP: 443, 80 |
|    180| Default Requried | No | compass-ssl.microsoft.com | TCP:443|

## Microsoft 365 Common

| ID    | Category         | ER | Addresses                                                    | Ports                       |
|:------|------------------| -- | -------------------------------------------------------------| --------------------------- |
| 41 | Default Optional. Notes: Microsoft Stream | No | *.microsoftstream.com | TCP: 443|
| 43 | Default Optional. Notes: Microsoft Stream 3rd party integration (including CDNs) | No | nps.onyx.azure.net | TCP: 443 |
| 44 | Default Optional. Notes: Microsoft Stream - unauthenticated | No | *.azureedge.net, *.media.azure.net, *.streaming.mediaservices.windows.net | TCP: 443|
| 45 | Default Optional. Notes: Microsoft Stream | No | *.keydelivery.mediaservices.windows.net | TCP: 443 |
| 46 | Allow Required | Yes | *.officeapps.live.com, *.online.office.com, office.live.com, 13.107.6.171/32, 13.107.18.15/32, 13.107.140.6/32, 52.108.0.0/14, 52.238.106.116/32, 52.244.37.168/32, 52.244.203.72/32, 52.244.207.172/32, 52.244.223.198/32, 52.247.150.191/32, 2603:1010:2::cb/128, 2603:1010:200::c7/128, 2603:1020:200::682f:a0fd/128, 2603:1020:201:9::c6/128, 2603:1020:600::a1/128, 2603:1020:700::a2/128, 2603:1020:800:2::6/128, 2603:1020:900::8/128, 2603:1030:7::749/128, 2603:1030:800:5::bfee:ad3c/128, 2603:1030:f00::17/128, 2603:1030:1000::21a/128, 2603:1040:200::4f3/128, 2603:1040:401::762/128, 2603:1040:601::60f/128, 2603:1040:a01::1e/128, 2603:1040:c01::28/128, 2603:1040:e00:1::2f/128, 2603:1040:f00::1f/128, 2603:1050:1::cd/128, 2620:1ec:c::15/128, 2620:1ec:8fc::6/128, 2620:1ec:a92::171/128, 2a01:111:f100:2000::a83e:3019/128, 2a01:111:f100:2002::8975:2d79/128, 2a01:111:f100:2002::8975:2da8/128, 2a01:111:f100:7000::6fdd:6cd5/128, 2a01:111:f100:a004::bfeb:88cf/128 | TCP: 443, 80|
| 47 | Default Required | No | *.office.net | TCP:443, 80 |
| 49 | Default Required | No | *.onenote.com | TCP: 443 |
| 50 | Default Optional. Notes: OneNote notebooks (wildcards) | No | *.microsoft.com | TCP: 443 | 
| 51 | Default Required | No | *cdn.onenote.net | TCP: 443 |
| 53 | Default Required | No | ajax.aspnetcdn.com, apis.live.net, officeapps.live.com, www.onedrive.com | TCP: 443 |
| 56 | Allow Required | Yes | *.auth.microsoft.com, *.msftidentity.com, *.msidentity.com, account.activedirectory.windowsazure.com, accounts.accesscontrol.windows.net, adminwebservice.microsoftonline.com, api.passwordreset.microsoftonline.com, autologon.microsoftazuread-sso.com, becws.microsoftonline.com, ccs.login.microsoftonline.com, clientconfig.microsoftonline-p.net, companymanager.microsoftonline.com, device.login.microsoftonline.com, graph.microsoft.com, graph.windows.net, login.microsoft.com, login.microsoftonline.com, login.microsoftonline-p.com, login.windows.net, logincert.microsoftonline.com, loginex.microsoftonline.com, login-us.microsoftonline.com, nexus.microsoftonline-p.com, passwordreset.microsoftonline.com, provisioningapi.microsoftonline.com, 20.190.128.0/18, 40.126.0.0/18, 2603:1006:2000::/48, 2603:1007:200::/48, 2603:1016:1400::/48, 2603:1017::/48, 2603:1026:3000::/48, 2603:1027:1::/48, 2603:1036:3000::/48, 2603:1037:1::/48, 2603:1046:2000::/48, 2603:1047:1::/48, 2603:1056:2000::/48, 2603:1057:2::/48 | TCP: 443, 80 |
| 59 | Default Required | No | *.hip.live.com, *.microsoftonline.com, *.microsoftonline-p.com, *.msauth.net, *.msauthimages.net, *.msecnd.net, *.msftauth.net, *.msftauthimages.net, *.phonefactor.net, enterpriseregistration.windows.net, management.azure.com, policykeyservice.dc.ad.msft.net | TCP: 443, 80 |
| 64 | Allow Required | Yes | *.compliance.microsoft.com, *.protection.office.com, *.security.microsoft.com, compliance.microsoft.com, defender.microsoft.com, protection.office.com, security.microsoft.com, 52.108.0.0/14, 2603:1006:1400::/40, 2603:1016:2400::/40, 2603:1026:2400::/40, 2603:1036:2400::/40, 2603:1046:1400::/40, 2603:1056:1400::/40, 2a01:111:200a:a::/64, 2a01:111:2035:8::/64, 2a01:111:f406:1::/64, 2a01:111:f406:c00::/64, 2a01:111:f406:1004::/64, 2a01:111:f406:1805::/64, 2a01:111:f406:3404::/64, 2a01:111:f406:8000::/64, 2a01:111:f406:8801::/64, 2a01:111:f406:a003::/64 | TCP: 443 |
| 65 | Allow Required | Yes | account.office.net, 52.108.0.0/14, 2603:1006:1400::/40, 2603:1016:2400::/40, 2603:1026:2400::/40, 2603:1036:2400::/40, 2603:1046:1400::/40, 2603:1056:1400::/40, 2a01:111:200a:a::/64, 2a01:111:2035:8::/64, 2a01:111:f406:1::/64, 2a01:111:f406:c00::/64, 2a01:111:f406:1004::/64, 2a01:111:f406:1805::/64, 2a01:111:f406:3404::/64, 2a01:111:f406:8000::/64, 2a01:111:f406:8801::/64, 2a01:111:f406:a003::/64 | TCP: 443, 80 |
| 66 | Default Required | No | *.portal.cloudappsecurity.com | TCP: 443 |
| 67 | Default Optional. Notes: Security and Compliance Center eDiscovery export | No | *.blob.core.windows.net | TCP: 443 |
| 68 | Default Optional. Notes: Portal and shared: 3rd party office integration. (including CDNs) | No | firstpartyapps.oaspapps.com, prod.firstpartyapps.oaspapps.com.akadns.net, telemetryservice.firstpartyapps.oaspapps.com, wus-firstpartyapps.oaspapps.com | TCP: 443 |
| 69 | Default Required | No | *.aria.microsoft.com, *.events.data.microsoft.com | TCP: 443 |
| 70 | Default Required | No | *.o365weve.com, amp.azure.net, appsforoffice.microsoft.com, assets.onestore.ms, auth.gfx.ms, c1.microsoft.com, dgps.support.microsoft.com, docs.microsoft.com, msdn.microsoft.com, platform.linkedin.com, prod.msocdn.com, shellprod.msocdn.com, support.microsoft.com, technet.microsoft.com | TCP: 443 |
| 71 | Default Required | No | *.office365.com | TCP: 443, 80 |
| 72 | Default Optional. Notes: Azure Rights Management (RMS) with Office 2010 clients | No | *.cloudapp.net | TCP: 443 |
| 73 | Default Required | No | *.aadrm.com, *.azurerms.com, *.informationprotection.azure.com, ecn.dev.virtualearth.net, informationprotection.hosting.portal.azure.net | TCP: 443 |
| 75 | Default Optional. Notes: Graph.windows.net, Office 365 Management Pack for Operations Manager, SecureScore, Azure AD Device Registration, Forms, StaffHub, Application Insights, captcha services | No | *.sharepointonline.com, dc.services.visualstudio.com, mem.gfx.ms, staffhub.ms | TCP: 443 |
| 78 | Default Optional. Notes: Some Office 365 features require endpoints within these domains (including CDNs). Many specific FQDNs within these wildcards have been published recently as we work to either remove or better explain our guidance relating to these wildcards. | No | *.microsoft.com, *.msocdn.com, *.onmicrosoft.com | TCP: 443, 80 |
| 79 | Default Required | No | o15.officeredir.microsoft.com, officepreviewredir.microsoft.com, officeredir.microsoft.com, r.office.microsoft.com | TCP: 443, 80 |
| 83 | Default Required | No | activation.sls.microsoft.com | TCP: 443 |
| 84 | Default Required | No | crl.microsoft.com | TCP: 443, 80 |
| 86 | Default Required | No | office15client.microsoft.com, officeclient.microsoft.com | TCP: 443 |
| 89 | Default Required | No | go.microsoft.com | TCP: 443, 80
| 91 | Default Required | No | ajax.aspnetcdn.com, cdn.odc.officeapps.live.com | TCP: 443: 80 |
| 92 | Default Required | No | officecdn.microsoft.com, officecdn.microsoft.com.edgesuite.net | TCP: 443, 80 |
| 93 | Default Optional. Notes: ProPlus: auxiliary URLs | No | *.virtualearth.net, c.bing.net, excelbingmap.firstpartyapps.oaspapps.com, ocos-office365-s2s.msedge.net, peoplegraph.firstpartyapps.oaspapps.com, tse1.mm.bing.net, wikipedia.firstpartyapps.oaspapps.com, www.bing.com | TCP: 443, 80 |
| 95 | Default Optional. Notes: Outlook for Android and iOS | No | *.acompli.net, *.outlookmobile.com | TCP: 443 |
| 96 | Default Optional. Notes: Outlook for Android and iOS: Authentication | No | login.windows-ppe.net | TCP: 443 |
| 97 | Default Optional. Notes: Outlook for Android and iOS: Consumer Outlook.com and OneDrive integration | No | account.live.com, login.live.com | TCP: 443 |
| 105 | Default Optional. Notes: Outlook for Android and iOS: Outlook Privacy | No | www.acompli.com | TCP: 443 |
| 114 | Default Optional. Notes: Office Mobile URLs | No | *.appex.bing.com, *.appex-rf.msn.com, c.bing.com, c.live.com, d.docs.live.net, directory.services.live.com, docs.live.net, partnerservices.getmicrosoftkey.com, signup.live.com | TCP: 443, 80 |
| 116 | Default Optional. Notes: Office for iPad URLs | No | account.live.com, auth.gfx.ms, login.live.com | TCP: 443. 80 |
| 117 | Default Optional. Notes: Yammer | No | *.yammer.com, *.yammerusercontent.com | TCP: 443 |
| 118 | Default Optional. Notes: Yammer CDN | No | *.assets-yammer.com | TCP: 443 |
| 121 | Default Optional. Notes: Planner: auxiliary URLs | No | www.outlook.com | TCP: 443, 80 |
| 122 | Default Optional. Notes: Sway CDNs | No | eus-www.sway-cdn.com, eus-www.sway-extensions.com, wus-www.sway-cdn.com, wus-www.sway-extensions.com | TCP: 443 |
| 124 | Default Optional. Notes: Sway | No | sway.com, www.sway.com | TCP: 443 | 
| 125 | Default Required | No | *.entrust.net, *.geotrust.com, *.omniroot.com, *.public-trust.com, *.symcb.com, *.symcd.com, *.verisign.com, *.verisign.net, apps.identrust.com, cacerts.digicert.com, cert.int-x3.letsencrypt.org, crl.globalsign.com, crl.globalsign.net, crl.identrust.com, crl3.digicert.com, crl4.digicert.com, isrg.trustid.ocsp.identrust.com, mscrl.microsoft.com, ocsp.digicert.com, ocsp.globalsign.com, ocsp.msocsp.com, ocsp2.globalsign.com, ocspx.digicert.com, secure.globalsign.com, www.digicert.com, www.microsoft.com | TCP: 443, 80 |
| 126 | Default Optional. Notes: Notes: Connection to the speech service is required for Office Dictation features. If connectivity is not allowed, Dictation will be disabled. | No | officespeech.platform.bing.com | TCP: 443 |
| 128 | Default Required | No | *.manage.microsoft.com | TCP: 443 |
| 147 | Default Requried | No | *.office.com | TCP: 443, 80 |
| 148 | Default Required | No | cdnprod.myanalytics.microsoft.com, myanalytics.microsoft.com, myanalytics-gcc.microsoft.com | TCP: 443, 80 |
| 152 | Default Optional. Notes: These endpoints enables the Office Scripts functionality in Office clients available through the Automate tab.  This feature can also be disabled through the Office 365 Admin portal. | No | *.microsoftusercontent.com | TCP: 443 |
| 153 | Default Required | No | *.azure-apim.net, *.flow.microsoft.com, *.powerapps.com | TCP: 443 |
| 156 | Default Required | No | *.activity.windows.com, activity.windows.com | TCP: 80 |
| 157 | Default Required | No | ocsp.int-x3.letsencrypt.org | TCP: 80 |
| 158 | Default Required | No | *.cortana.ai | TCP: 443 |
| 159 | Default Required | No | admin.microsoft.com | TCP: 443, 80 |
| 160 | Default Required | No | cdn.odc.officeapps.live.com, cdn.uci.officeapps.live.com | TCP: 443, 80 |











## Microsoft Intune

| Domain(s)    | IP Address(es)  |
|:------|------------------|
| login.microsoftonline.com, *.officeconfig.msocdn.com, config.office.com, graph.windows.net, enterpriseregistration.windows.net, | |
| *.manage.microsoft.com,  manage.microsoft.com, | 20.43.129.0/24, 20.44.19.224/27, 20.49.93.160/27, 40.119.8.128/25, 40.67.121.224/27, 40.70.151.32/28, 40.71.14.96/28, 40.74.25.0/24, 40.78.245.240/28, 40.78.247.128/27, 40.79.197.64/27, 40.79.197.96/28, 40.80.180.208/28, 40.80.180.224/27, 40.80.184.128/25, 40.82.248.224/28, 40.82.249.128/25, 52.150.137.0/25, 52.162.111.96/28, 52.168.116.128/27, 52.182.141.192/27, 52.236.189.96/27, 52.240.244.160/27, 104.214.164.192/27, 104.46.162.96/27, 13.67.13.176/28, 13.67.15.128/27, 13.69.231.128/28, 13.69.67.224/28, 13.70.78.128/28, 13.70.79.128/27, 13.71.199.64/28, 13.73.244.48/28, 13.74.111.192/27, 13.75.39.208/28, 13.77.53.176/28, 13.86.221.176/28, 13.89.174.240/28, 13.89.175.192/28, 20.189.105.0/24, 20.189.172.160/27, 20.189.229.0/25, 20.191.167.0/25, 20.37.153.0/24, 20.37.192.128/25, 20.38.81.0/24, 20.41.1.0/24, 20.42.1.0/24, 20.42.130.0/24, 20.42.224.128/25|

## Teams Room Premium

| URL    |
|:------|
| agent.rooms.microsoft.com, global.azure-devices-provisioning.net, gj3ftstorage.blob.core.windows.net, mmrstgnoamiot.azure-devices.net, mmrstgnoamstor.blob.core.windows.net, mmrprodapaciot.azure-devices.net, mmrprodapacstor.blob.core.windows.net, mmrprodemeaiot.azure-devices.net, mmrprodemeastor.blob.core.windows.net, mmrprodnoamiot.azure-devices.net, mmrprodnoamstor.blob.core.windows.net |

# Vendor Specific URLs

## Poly

| URL    |
|:------|
| ntp.polycom.com, api.silica-prod01.io.lens.poly.com, zto.poly.com, firebaseremoteconfig.googleapis.com, connectivitycheck.android.com, firebaseinstallations.googleapis.com, 0.pool.ntp.org, in.appcenter.ms|


## Logitech

| URL    |
| :------|
| sync.logitech.com, updates.vc.logitech.com, raiden.vc.logitech.com, svcs.vc.logitech.com|

