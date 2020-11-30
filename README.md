# Awesome Scapy [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme)

A curated list of tools, add-ons, articles or cool exploits using **[Scapy](https://scapy.net)**. Feel free to [contribute](https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2Fsecdev%2Fawesome-scapy%2Fedit%2Fmaster%2FREADME.md ) !

## Contents

- [Tools](#tools)
- [Exploits](#exploits)

### Tools

*Tools that use Scapy (a lot) or extend it*

DDoS
- [ufonet](https://github.com/epsylon/ufonet): create your own botnet to send untraceable DDoS attacks

Wi-Fi
- [trackerjacker](https://github.com/calebmadrigal/trackerjacker): Maps and tracks Wi-Fi networks and devices through raw 802.11 monitoring.
- [wifiphisher](https://github.com/wifiphisher/wifiphisher): create rogue access point

IPv6
- [Chiron](https://github.com/aatlasis/Chiron): an IPv6 security assessment framework
- [mitm6](https://github.com/fox-it/mitm6): performs MiTM for IPv6

Measurements
- [mtraceroute](https://github.com/rwhalb/mtraceroute): create cool graphs over multiple traceroute analysis
- [Network Security Toolkit (NST)](https://wiki.networksecuritytoolkit.org/nstwiki/index.php?title=HowTo_Use_The_Scapy:_Multi-Traceroute_-_MTR): Includes an enhanced version of `mtraceroute` with IP Geolocation and GUI management

Protocols
- [TorPylle](https://github.com/cea-sec/TorPylle): implementation of the OR (TOR) protocol

Unit Tests
- [Linux Kernel](https://github.com/torvalds/linux/blob/master/tools/testing/selftests/tc-testing/plugin-lib/scapyPlugin.py): Linux Traffic Control (tc) testing suite
- [OpenBSD](https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2Fsearch%3Fq%3Dscapy%2Brepo%253Aopenbsd%252Fsrc%2Bpath%253Aregress%252F%26type%3DCode%26ref%3Dadvsearch%26l%3D%26l%3D): IPv6 stack testing suite
- [RIOT-OS](https://github.com/RIOT-OS/RIOT/search?l=Python&q=scapy&type=Code): RIOT OS networking testing suite

Misc
- [aioblescan](https://github.com/frawau/aioblescan): scan and decode advertised BLE info
- [fenrir](https://github.com/Orange-Cyberdefense/fenrir-ocd): bypass wired 802.1x protection
- [flowsynth](https://github.com/secureworks/flowsynth): tool for rapidly modeling network traffic
- [Fragscapy](https://github.com/AMOSSYS/Fragscapy): fuzz network protocols by automating the modification of outgoing network packets
- [net-creds](https://github.com/DanMcInerney/net-creds): sniff and catch all sensitive data on an interface
- [packetweaver](https://github.com/ANSSI-FR/packetweaver): a Python framework for script filing and task sequencing
- [p0f3plus](https://github.com/FlUxIuS/p0f3plus): an implementation of with extra analysis features
- [pysap](https://github.com/SecureAuthCorp/pysap): interact with SAP using custom built frames & tools
- [Responder](https://github.com/SpiderLabs/Responder):  LLMNR, NBT-NS and MDNS poisoner
- [scapy_unroot](https://github.com/scapy-unroot/scapy_unroot): tooling to use Scapy without root permissions
- [scapy-benchmarks](https://github.com/gpotter2/scapy-benchmarks): a small test suite that tracks the evolution of Scapy's performance.
- [sshame](https://github.com/HynekPetrak/sshame): tool to brute force SSH public-key authentication
- [TIDoS Framework](https://github.com/0xInfection/TIDoS-Framework): The Offensive Manual Web Application Penetration Testing Framework

### Exploits

*Exploits that use Scapy. This does not count the ones included by default*

2019
- [CVE-2019-5597](https://www.synacktiv.com/ressources/Synacktiv_OpenBSD_PacketFilter_CVE-2019-5597_ipv6_frag.pdf): IPv6 fragmentation vulnerability in OpenBSD Packet Filter
2018

- [CVE-2018-4407](https://github.com/r3dxpl0it/CVE-2018-4407): a heap buffer overflow in the networking code in the XNU operating system kernel (iOS and macOS)

2017
- [krackattacks-scripts](https://github.com/vanhoefm/krackattacks-scripts): test if clients or access points (APs) are affected by the KRACK attack against WPA2

2016
- [CVE-2016-6366](https://github.com/RiskSense-Ops/CVE-2016-6366): the EXTRABACON exploit, a remote code execution for Cisco ASA written by the Equation Group (NSA) and leaked by the Shadow Brokers

Misc
- [isf](https://github.com/dark-lbp/isf): ISF (Industrial Control System Exploitation Framework). A suite that provides exploits various industrial protocols
