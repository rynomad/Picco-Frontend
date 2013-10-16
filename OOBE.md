User opens her PiccoLabs box. Within the box is the router, cables, and a QuickStart Guide.

The QuickStart guide instructs her to to Connect the fiber, and power cables, and provides the SSID, and default password to the AP.

Once connected to the network (via wifi OR ethernet), she follows the prompts in the "Hello House" wizard, and is then presented with the PiccoLabs app appropriate for her platform (Iphone, android, windows, Mac, Linux...)

Upon completion of "Hello House", AP begins broadcasting a hidden SSID (connect to via PiccoLabs APP, gives full internet and Pod access) and a public, unprotected SSID (gives local only access to get guest-configured PiccoLabs app if authorized via Pod of trust)

PiccoLabs App manages network connections within Pod of Trust, runs human interface webserver on localhost


Connect Device to Internet
Plug in fiber (do we have to open a hatch like Calix ONT?).
Device accesses Internet, reports in and registers self (why? where?) and does a query to find out lots of things.

Power On
Is there anything user needs to capture from sticker, card, RTFM before plug in? Is an App needed? Example: typical practice is reading the SSID and a password from serialized sticker on bottom of device.

Device does POST.

Connect to Device
Wired? Wireless? How to insure no invaders cop the signal at moment of vulnerability? Will the SSID be open? Secure? Both?


“Hello House”
(One time only setup before Welcome Home)
Prompts:
1: Confirm Time of Day, Date and Location via user input
2: RTFM for PiccoPod Key and unlock Device
3: Choose new key passphrase (generate crypto key)
4: add client device to recognized devices 
5: forward to Welcome Home

Welcome Home
-Default Welcome screen appears
-Welcome to the PiccoPod
	1. Create/access Personal Pod?
	2. Create/access Shared Pod?
	3. Create/access Public Pod?
		
MVP/Demo Features:
1. Learn to Store
2. Learn to Share
3. Learn to Search

Welcome Visitors:
“POD Warming Party”
1. Gain access to PiccoPod (perhaps you are in a Pod of Trust).
2. Start action to Store, Share or Search
3. Leave your bit of “Information Potluck.”
4. Eat some “Information Potluck.”
