# LG-WebOS-AdGuard-blocklist

Remove all the ADs and menu clutter from your LG Web OS 6 TV

Tested in the UK on an LG C1 Webos 6.3 although it should work ok on other regions + models

1. Setup an AdGuard DNS instance on your network and make sure it is resolving the TV's queries

2. Copy the URL to the raw blocklist in the repo and add to AdGuard's blocklist section 


Please Note: 

lgtvsdp.com
lgappstv.com

These two  entries are what seem to be required for the store to minimally work and fetch app updates 
but if unblocked they fetch information for the trending section on the home screen 

What I would reccomend is disabling the blocklist in AdGuard, updating the apps and then re-enabling it
