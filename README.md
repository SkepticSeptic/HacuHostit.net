# HacuHostit.net is a free hosting service for members of Hack Club!

Essentially, you get an ssh connection to your own little VPS running Debian Linux, with full root permissions to host whatever your heart desires! 

Install additional packages? Go for it! 

```sudo rm -rf /* --no-preserve-root```? I mean... you can... (make sure to maintain your own backups, resetting a server must be done through #hacuhostit-support)

# What can I host?
You can host anything from a personal website to your very own app, a webshell for CTFs, a virtual backup, or anything else you could ever want!


# What is provided?
As of the alpha release, you will be provided with a system configured as such. 
Note, specs are subject to change for the better or worse. Please remember RAM is typically more important than CPU power when hosting basic services:
 - Debian Linux (server release) or a personal OS (manually set up in #hacuhostit-support)
 - 1-2 CPU cores
 - 2-3 gigabytes of RAM
 - 20-50 gigabytes of storage
 - Ports 1337-2000 (any other ports will not be forwarded to the internet)
 - Privacy: we pledge to not analyze your VPS, making it safe* to host personal services. *NOTE: We are NOT subject to outside intrusion to your VPS. Your VPS, you secure it.
# What is not provided?
 - VPS Backups, please maintain your own in case anything goes wrong
 - Security features, your VPS by default will be secure, but the more you host and the more you download, the bigger your chances of security misconfigurations are. Be curious but mindful.


# What can't I host?
This is more specifically detailed in the terms of service, but generally, anything that is illegal or takes up an unreasonable amount of network input/output such as a VPN. You are subject to network-based restrictions if so.

Additionally, malware is a very sensitive issue. While static analysis of malware **for research purposes** is okay, any kind of dynamic analysis (executing, running through GDB, etc.) is strictly forbidden and can subject you to being permanently banned from hosting.
As security improves, this may change, but currently absolutely no dynamic analysis of malware is allowed.

To sign up, join the slack if you are not already and go to #hacuhostit-signup


# Bug bounty / submit a vulnerability

Unfortunately, as this is a volunteer project ran without any funds, so there are no *paid* bug bounty programs.
However, if you do find a misconfiguration, vulnerability, or bug, please email me at bugbounty@hacuhostit.net or DM me in the slack, and I will try my best to fix it ASAP. Hack the planet!


# Wishlist
This is the current list of items that may improve service one way or the other:

