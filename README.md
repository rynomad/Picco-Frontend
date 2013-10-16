Picco-Frontend
==============

This Repository hosts work-in-progress frontend html/javascript/css for the PiccoPod personal Server.

in BootStrap/

*Choose.html/Login.html - Prompt for choosing/entering a passphrase
*full-slider.html - Skeleton interface for PiccoPods


Full-slider.html
================

Currently Populated with "template pods", giving a brief description of the types of pods available

*Private - Safe, accessible, just for you
*Trusted - For You and your trusted peers
*Public - Broadcast to the world

These placeholders will be repopulated with real user pods upon access of the server side REST API; each pod gets a spot on the carousel and a menu item in the sidebar. When accessed, the <div> below the Pod-Header (still within its respective carousel item) will serve as a stream container for content relevant to that pod, as well as an input option for that pod. 
