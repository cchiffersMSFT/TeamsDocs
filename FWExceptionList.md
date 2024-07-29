# Microsoft 365 URL Firewall List

Here’s a handy list of URLs Windows-based MTRs access.

This list was captured using a Pi-hole, from the moment the MTR was turned on, registering with Intune and Azure AD, and signing in to Teams. Making calls and joining a meeting are also included. My test device is also registered with the Teams Meeting Room Premium service.

Note: The list only includes URLs and does not include IP addresses that are listed here: aka.ms/m365urls

## Poly Phones:

Here's a list of URLs the device accesses from the moment it is connected to PoE, through sign in and making a call


| Record   | Express Route | URL         |
|:------|------------|-------------| 
|     A |	| No | 0.pool.ntp.org |
|     SRV | No | _ntp._udp.time.windows.com |
|     A | No |a.manage.microsoft.com |
|     A |	No | aadcdn.msauth.net |
|     A | No | aadcdn.msftauth.net |
|     A | No | android.clients.google.com |
|     A |	Yes | api.flightproxy.teams.microsoft.com |
|     A |	No | api.microsoftstream.com |
|     A |	No | api3.cc.skype.com |
|     A |	Yes| au.ng.msg.teams.microsoft.com |
|     A |	No | auea-1.api.microsoftstream.com |
|     A |	Yes | authsvc.teams.microsoft.com |
|     A |	Yes | authsvc.teams.microsoft.com |
|     A |	Yes | config.teams.microsoft.com |
|     A |	No | connectivitycheck.android.com |
|     A |	Yes | devicemgmt-cdn.teams.microsoft.com |
|     A |	Yes | devicemgmt.teams.microsoft.com |
|     A |	No | enterpriseregistration.windows.net |
|     A |	No | fef.msud01.manage.microsoft.com |
|     A |	No | firebaseinstallations.googleapis.com |
|     A |	No | firebaseremoteconfig.googleapis.com |
|     A |	No | go.microsoft.com | 
|     A |	Yes | go.trouter.teams.microsoft.com |
|     A |	Yes | graph.microsoft.com |
|     A |	Yes | graph.windows.net |
|     A |	No | ic3.events.data.microsoft.com |
|     A |	No | in.appcenter.ms |
|     AAAA |	ipv4only.arpa |
|     A | Yes| japanwest-prod.notifications.teams.microsoft.com |
|     A |	No | login.live.com |
|     A |	Yes | login.microsoftonline.com |
|     A |	No | mamservice.manage.microsoft.com |
|     A |	No | mobile.pipe.aria.microsoft.com |
|     A |	No | mtalk.google.com |
|     A | No | odc.officeapps.live.com |
|     A |	No | outlook.office.com |
|     A |	Yes | presence.teams.microsoft.com |
|     A |	Yes | Teams.microsoft.com |
|     A |	No | time.windows.com |
|     A |	No | whiteboard.microsoft.com |
|     A |	Yes | worldaz.relay.teams.microsoft.com |
|     AAAA | Yes |trouter2-azsc-auea-0-a.trouter.teams.microsoft.com |
|     A |	Yes | auc.pptservicescast.officeapps.live.com |


## Poly MTR:

Here's a similar list for Windows-based MTRs:

| Record    | URL         |
|:------|-------------| 
|     A | pipe.skype.com
|     A | devicemgmt.teams.microsoft.com
|     A | teams.events.data.microsoft.com
|     A | ctldl.windowsupdate.com
|     A | presence.teams.microsoft.com
|     A | settings-win.data.microsoft.com
|     A | cdn.aiinfrastructure.teams.microsoft.com
|     AAAA | api.flightproxy.teams.microsoft.com
|     A | statics.teams.cdn.office.net
|     A | worldaz.relay.teams.microsoft.com
|     A | au.ng.msg.teams.microsoft.com
|     A | wpad.localdomain
|     A | outlook.office.com
|     A | login.microsoftonline.com
|     A | api.userstore.skype.com
|     AAAA | api3.cc.skype.com
|     A | teams.microsoft.com
|     AAAA | ic3.events.data.microsoft.com
|     A | config.teams.microsoft.com
|     A | au-v10.events.data.microsoft.com
|     A | fef.msud01.manage.microsoft.com
|     A | manage.microsoft.com
|     A | x1.c.lencr.org
|     A | au-prod.asyncgw.teams.microsoft.com
|     A | login.live.com
|     A | dc.services.visualstudio.com
|     A | japanwest-prod.notifications.teams.microsoft.com
|     A | trouter2-azsc-ince-1-b.trouter.teams.microsoft.com
|     A | fe3cr.delivery.mp.microsoft.com
|     A | fe2cr.update.microsoft.com
|     AAAA | 9.tlu.dl.delivery.mp.microsoft.com
|     AAAA | emdl.ws.microsoft.com
|     AAAA | download.windowsupdate.com
|     A | agent.rooms.microsoft.com
|     A | gj3ftstorage.blob.core.windows.net
|     A | slscr.update.microsoft.com
|     A | teams.nel.measure.office.net
|     A | licensing.mp.microsoft.com
|     A | client.wns.windows.com
|     A | dns.msftncsi.com
|     AAAA | go.trouter.teams.microsoft.com
|     A | mmrprodnoamiot.azure-devices.net
|     A | autologon.microsoftazuread-sso.com
|     A | trouter2-azsc-asse-3-a.trouter.teams.microsoft.com
|     A | au-v20.events.data.microsoft.com
|     A | r.manage.microsoft.com
|     A | au.download.windowsupdate.com
|     A | cp601.prod.do.dsp.mp.microsoft.com
|     A | kv601.prod.do.dsp.mp.microsoft.com
|     A | geo.prod.do.dsp.mp.microsoft.com
|     A | onegetcdn.azureedge.net
|     A | go.microsoft.com
|     A | browser.pipe.aria.microsoft.com
|     A | pti.store.microsoft.com
|     A | southeastasia-prod-2.notifications.teams.microsoft.com
|     A | time.windows.com
|     A | gameplayapi.intel.com
|     A | s-ring.msedge.net
|     A | csp.microsoft.com
|     A | substrate.office.com
|     A | fpc.msedge.net
|     A | graph.microsoft.com
|     A | mobile.pipe.aria.microsoft.com
|     A | outlook.office365.com
|     A | wdcp.microsoft.com
|     A | nexusrules.officeapps.live.com
|     A | ecs.office.com
|     A | has.spserv.microsoft.com
|     A | cdn.onenote.net
|     A | df.trap.teams.microsoft.com
