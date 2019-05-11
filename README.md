# unitscan - WoW 1.12 addOn 

![Alt text](http://i.imgur.com/d7TLkZm.png)

This addOn automatically scans for any targetable units of your choice by name and alerts you upon finding one. Instead of the modern scanning methods which don't work for Vanilla it uses the API function *TargetByName* which was removed with TBC.

The alert is visually and acoustically an exact copy of the famous addOn *_NPCScan* which first appeared during WotLK.

Once unit detected, addon will ignore that unit for 5 minutes. To reset ignore list, use `/unitscan i`.

There are two commands:<br/>
`/unitscan` prints help<br/>
`/unitscan a <name>` adds **name** to the scan targets<br/>
`/unitscan r <name>` removes **name** from the scan targets<br/>
`/unitscan p` prints list of all scanned targets<br/>
`/unitscan u` enables unmute in case of target detection, so alert would be heard<br/>
`/unitscan i` reset ignore list<br/>
When a target is detected it is removed and has to be readded to continue scanning for it.
