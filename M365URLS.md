# Microsoft 365 URL List

## Microsoft Teams (& Skype for Business)

| ID    | Category         | ER | Addresses                                                    | Ports                       |
|------:|------------------| -- | -------------------------------------------------------------| --------------------------- |
|     11| Optimize Required| Yes| 13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 2603:1063::/38| UDP: 3478, 3479, 3480, 3481  |
|     12| Allow Required   | Yes| *.lync.com, *.teams.microsoft.com, teams.microsoft.com 13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 52.238.119.141/32, 52.244.160.207/32, 2603:1027::/48, 2603:1037::/48, 2603:1047::/48, 2603:1057::/48, 2603:1063::/38, 2620:1ec:6::/48, 2620:1ec:40::/42| TCP: 443, 80 |
|     13| Allow Required   | Yes| *.broadcast.skype.com, broadcast.skype.com 13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 52.238.119.141/32, 52.244.160.207/32, 2603:1027::/48, 2603:1037::/48, 2603:1047::/48, 2603:1057::/48, 2603:1063::/38, 2620:1ec:6::/48, 2620:1ec:40::/42| TCP: 443 |
|     15| Default Required | No | *.sfbassets.com | TCP: 443, 80 |
|     16| Default Required | No | *.keydelivery.mediaservices.windows.net, *.streaming.mediaservices.windows.net, mlccdn.blob.core.windows.net| TCP:443|
|     17| Default Required | No | aka.ms | TCP: 443 |
|     18| Default Optional. Notes: Federation with Skype and public IM connectivity: Contact picture retrieval | No | *.users.storage.live.com | TCP: 443 |
|     19| Default Optional. Notes: Applies only to those who deploy the Conference Room Systems. | *.adl.windows.com | TCP: 443, 80|
|     22| Allow Optional. Notes: Teams: Messaging interop with Skype for Business. | Yes | *.skypeforbusiness.com
13.107.64.0/18, 52.112.0.0/14, 52.122.0.0/15, 52.238.119.141/32, 52.244.160.207/32, 2603:1027::/48, 2603:1037::/48, 2603:1047::/48, 2603:1057::/48, 2603:1063::/38, 2620:1ec:6::/48, 2620:1ec:40::/42 | TCP: 443 |
|     26| Default Optional. Notes: Wildcard being moved to optional prior to being removed. | No| *.msedge.net | TCP: 443|
|     27| Default Required | No | *.mstea.ms, *.secure.skypeassets.com, mlccdnprod.azureedge.net | TCP: 443|
|    127| Default Required | No | *.skype.com | TCP: 443, 80 |
|    180| Default Requried | No | compass-ssl.microsoft.com | TCP:443|

