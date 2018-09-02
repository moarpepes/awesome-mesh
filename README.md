# Awesome-Mesh

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a list for mesh networking: Documentation, Free Software mesh protocols, and applications. A mesh network is a network topology in which each node relays data for the network. All mesh nodes cooperate in the distribution of data in the network.

--------------------
  - [Documentation](#documentation)
  - [Protocols](#protocols)
    - [Routing](#routing)
    - [Stack](#stack)
  - [Software](#software)
    - [AllInOne](#allinone)
    - [Desktop](#desktop)
    - [Mobile](#mobile)
    - [Router](#router)
  - [License](#license)


-----------------------------------------------------------------------------

<!-- BEGIN SOFTWARE LIST -->

## Documentation
**[`^        back to top        ^`](#)**
* [Wireless Mesh Networking](https://en.wikibooks.org/wiki/Wireless_Mesh_Networks) - A wikibook dedicated to the subject.

* [Wireless Networking in the Development World](http://wndw.net/) - Wireless Networking in the Developing World is a free book about designing, implementing, and maintaining low-cost wireless networks. Chapter 8 is dedicated to Mesh Networking.

* [open80211s](https://github.com/o11s/open80211s/wiki/HOWTO) - This page provides a quick introduction to open80211s and gives step by step guide on how to set up a mesh network using open80211s and a supported driver.

## Protocols
**[`^        back to top        ^`](#)**

### Routing
**[`^        back to top        ^`](#)**
* [babled](http://www.pps.univ-paris-diderot.fr/~jch/software/babel/) - Babel is a loop-avoiding distance-vector routing protocol for IPv6 and IPv4 with fast convergence properties. It is based on the ideas in DSDV, AODV and Cisco's EIGRP, but is designed to work well not only in wired networks but also in wireless mesh networks, and has been extended with support for overlay networks. [Source Code](https://github.com/jech/babeld) `MIT` `C`

* [batman-adv](https://github.com/torvalds/linux/blob/master/Documentation/networking/batman-adv.rst) - Batman advanced is a new approach to wireless networking which does no longer operate on the IP basis. [Source Code](https://www.open-mesh.org/projects/open-mesh/wiki/Download) `GPLv2` `C`

* [cjdns](https://github.com/cjdelisle/cjdns/) - An encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. [Source Code](https://github.com/cjdelisle/cjdns/) `GPLv3` `Assembly`

* [GNUnet](https://gnunet.org/) - A mesh routing layer for end-to-end encrypted networking and a framework for distributed applications designed to replace the old insecure Internet protocol stack. [Source Code](https://gnunet.org/git/) `GPLv3` `Java` (Various)

* [OLSR](http://olsr.org/) - The Optimized Link State Routing Protocol (OLSR) is an IP routing protocol optimized for mobile ad hoc networks, which can also be used on other wireless ad hoc networks. [Source Code](https://github.com/OLSR/OONF)  `BSD` `C`

### Stack
**[`^        back to top        ^`](#)**


* [BLEMP](https://github.com/aanon4/BLEMP) - Bluetooth Low Energy Mesh Protocol for nRF51 Nordic chips. [Source Code](https://github.com/aanon4/BLEMP) `BSD` `C`

* [FruityMesh](https://github.com/mwaylabs/fruitymesh/wiki) - The first completely connection-based open source mesh on top of Bluetooth Low Energy 4.1. [Source Code](https://github.com/mwaylabs/fruitymesh) `GPLv3` `C++`

* [Mesh Bee](https://www.seeedstudio.com/Mesh-Bee-Open-Source-Zigbee-Pro-Module-with-MCU-%28JN5168%29-p-1751.html) - MeshBee® is a 2.4 GHz wireless zigbee RF module. It use microchip JN516x from NXP that enables several different flavors of standards-based zigbee mesh networking. [Source Code](https://github.com/Seeed-Studio/Mesh_Bee) `MIT` `C`

## Software
**[`^        back to top        ^`](#)**

### AllInOne
**[`^        back to top        ^`](#)**

* [LifeNet](http://thelifenetwork.org/about.html) - LifeNet is a WiFi-based data communication solution designed for post-disaster scenarios. It is open-source software and designed to run on consumer devices such as laptops, smart-phones and wireless routers. [Source Code](https://github.com/hrushim/LifeNet) `GPLv3` `C`

* [Commotion Wireless](https://commotionwireless.net/) - Commotion is an open-source communication tool that uses wireless devices to create decentralized mesh networks on routers, mobiles, and desktops. [Source Code](https://github.com/opentechinstitute) `GPLv3` `C`

### Desktop
**[`^        back to top        ^`](#)**

* [FreeNet](https://freenetproject.org/) - Communications by Freenet nodes are encrypted and are routed through other nodes to make it extremely difficult to determine who is requesting the information and what its content is, data is shared by all users on the network. [Source Code](https://github.com/freenet/fred) `GPLv2` `Java`

* [Go-IPFS](https://ipfs.io/) - IPFS is a global, versioned, peer-to-peer filesystem. It combines good ideas from Git, BitTorrent, Kademlia, SFS, and the Web. It is like a single bittorrent swarm, exchanging git objects. [Source Code](https://github.com/ipfs/go-ipfs) `MIT` `Go`

* [Project Byzantium](http://project-byzantium.org/) - Ad-hoc wireless mesh networking for the zombie apocalypse. Unlike most mesh implementations, a Byzantium Mesh requires no specialized equipment that may not be easy to get during an emergency, just an x86 computer with at least one 802.11 a/b/g/n wireless interface. [Source Code](https://github.com/Byzantium/Byzantium) `GPLv3` `C`

* [ZeroNet](https://zeronet.io/) - ZeroNet is a decentralized Internet-like network of peer-to-peer users. Each visitor is also a host. [Source Code](https://github.com/HelloZeroNet/ZeroNet) `GPLv2` `Python`

### Mobile
**[`^        back to top        ^`](#)**

* [Briar](https://briarproject.org) - Briar is a messaging app designed for activists, journalists, and anyone else who needs a safe, easy and robust way to communicate. If the internet is down, Briar can sync via Bluetooth or Wi-Fi between trusted clients. However, Briar does not relay messages through untrusted clients [Talk Torsten Grote @ 34C3](https://media.ccc.de/v/34c3-8937-briar), such that it is not suitable for desaster communication, where any (untrusted) client needs to work relay to build an efficient mesh network. [Source Code](https://code.briarproject.org/akwizgran/briar/tree/master) `GPLv3` `Java`

* [Disaster.radio](https://disaster.radio/) - A disaster-resilient communications network powered by the sun. [Source Code](https://github.com/sudomesh/disaster-radio/) `GPLv3` `Python`

* [ServalMesh Batphone](http://www.servalproject.org/) - This app assumes zero infrastructure. The phones talk to each other using WiFi; relaying calls and messages and figuring out how to resolve numbers. In other words, it lets your phone communicate with other Android phones running Serval Mesh within WiFi range. [Source Code](https://github.com/servalproject/batphone) `GPLv3` `Java`

* [Splinternet](https://github.com/megamattron/SplinterNet) - A serverless, unblockable messaging system for Android. [Source Code](https://github.com/megamattron/SplinterNet)  `MIT`[?](https://github.com/megamattron/SplinterNet/issues/6) `Java`

* [Underdark](http://underdark.io/) - Mobile peer-to-peer mesh networking library. Integrates into iOS and Android apps and works over Wi-Fi and Bluetooth. Demo app called Solidarity available for download. [Source Code](https://github.com/udark/underdark-android) `modified-Apache 2.0`[(With Extra Clause)](http://underdark.io/LICENSE.txt) `Java`

* [AirChat](https://github.com/lulzlabs/AirChat) - Free Communications For Everyone. Each node only cares for what is being received. No hardware identification, no transmitter plain identification. only packets matter. transmissions are anonymous. whenever an address is needed to reply to a packet, it is encrypted inside the packet. [Source Code](https://github.com/lulzlabs/AirChat) `modified-WTFPL` `Perl`

* [The SPAN Project](https://projectspan.github.io) - Smart Phone Ad-hoc Networking is a mobile ad hoc network (MANET) project which provides a push-to-talk (PPT) service on android devices ([Google Play](https://play.google.com/store/apps/developer?id=stoker)). The project seems to be abandoned. [Source Code](https://github.com/ProjectSPAN) `C` `Java` `HTML`

### Router
**[`^        back to top        ^`](#)**

* [Quick Mesh Project](https://qmp.cat/Home) - Quick Mesh Project (qMp) is a system for easily deploying Mesh/MANET networks using Wi-Fi technology. [Source Code](http://dev.qmp.cat/projects/qmp/repository) `GPLv2` `C`

* [LibreMesh](http://www.libremesh.org/) - LibreMesh is a modular framework for creating OpenWrt/LEDE-based firmwares for wireless mesh nodes. Several communities around the world use LibreMesh as the foundation of their local mesh firmwares. [Source Code](https://github.com/libremesh/) `AGPLv3` `Lua`

## Communities
**[`^        back to top        ^`](#)**

### Online
**[`^        back to top        ^`](#)**
* [DarkNetPlan](https://www.reddit.com/r/darknetplan/) - A Reddit community for discussion of off-grid communications and mesh networking.

* [Hyperboria](https://hyperboria.net/)  - A community of local Wifi initiatives, programmers, and enthusiasts. Largest public cjdns network.

* [MeshLocals](https://github.com/phillymesh/meshlocals/blob/master/meshlocals.md) - A list of all of the meshlocals, working on mesh networks. Have an update? Send a pull request!

### Offline
**[`^        back to top        ^`](#)**
* [Battle of the Mesh](http://battlemesh.org/) - A European-based tournament with a social character. If you are a mesh networking enthusiast, community networking activist, or have an interest in mesh networks you might want to check this out! 

* [Broadband-Hamnet](http://www.broadband-hamnet.org/) - A high speed, self discovering, self configuring, fault tolerant, wireless computer network that can run for days from a fully charged car battery, or indefinitely with the addition of a modest solar array or other supplemental power source. The focus is on emergency communications for HAM operators.

* [Freifunk](https://freifunk.net/en/) - Germany's largest community wifi project. 

* [Guifi.net](https://guifi.net/en) - Spain's largest community wifi project.

* [SudoRoom's Mesh Group](https://sudoroom.org/wiki/Mesh) - A collective of collectives stewarding a large community space in Oakland, California.

## License
**[`^        back to top        ^`](#)**

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.
