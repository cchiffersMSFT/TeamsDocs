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
