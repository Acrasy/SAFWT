# Project G-Cloud Setup

|Name|value
|---|---|
| Project | SAWFT |
| Project ID | sawft-275017 |
| | |
|Cloudguard Admin User|admin|
|Cloudguard Admin PW|MesvQPH5h95c|
|Cloudguard internalIP(default)|10.128.0.2|
|Cloudguard internalIP(my-vpc)|192.168.23.2|
|Cloudguard externalIP|34.71.14.71|
|LinuxHost IP| 192.168.23.50|

# Lab 4: IPSec VPN

Nach aktivieren des IP-Sec VPN Blades wurde unter "Always use this IP address" die fuer die Firewall extern IP Adresse gewaehlt. G-Cloud routet diese automatisch auf die vom WAN aus erreichbare IP Adresse. Daher glaubt die Firewall ihre externe Adresse sei 10.128.0.2 . Dies soll durch das automatische NAT'ing dieser auf die externe IP 34.71.14.71 fuer uns kein weiteres Hindernis darstellen.

![4.1](screenshots4/4.1rout.png)
