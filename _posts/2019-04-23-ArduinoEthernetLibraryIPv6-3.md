---
layout: post
title: 'AdvancedChatServer'
author: taylor.An
date: 2019-04-23 13:00
tags: [arduino,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/Wiznet/Ethernet/tree/IPv6"></a>

# [ArduinoEthernetLibraryIPv6] AdvancedChatServer

[Original tutorial AdvancedChatServer on Arduino Homepage](https://www.arduino.cc/en/Tutorial/AdvancedChatServer).

## Open Arduino IDE

Run Arduino IDE and Open "AdvancedChatServer.ino" sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/1-IDE-Open.JPG)

## Set Network Information

Set your IPv6 Network information.

* mac

    MAC Address

* ip6_lla

    Link Local Address

* ip6_gua

    Global Unicast Address

* ip6_sn6

    Subnet Mask IPv6 Address
    
* ip6_gw6

    Gate Way IPv6 Address
    
* ip6_dns6

    Link Local Address
    
![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/2-IDE-SetNetworkInformation.JPG)

## Upload

Upload AdvancedChatServer sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/3-IDE-Upload.JPG)

## Serial Monitor

Open serial monitor and you'll be able to see the your network information.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/4-Serial%20Monitor.JPG)

## ScriptCommunicator

Run TCP Client like [ScriptCommunicator](https://sourceforge.net/projects/scriptcommunicator/).

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/5-ScriptCommunicator-Empty.JPG)

## ScriptCommunicator - Setting

The AdvancedChatServer is TCP application.

Set AdvancedChatServer's LLA or GUA as destination address and port as destination port.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/6-ScriptCommunicator-Settings.JPG)

## ScriptCommunicator - Connect

Connect to AdvancedChatServer.

The AdvancedChatServer will has sent your connection number.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/7-ScriptCommunicator-Connect.JPG)

## Serial Monitor - Result

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/AdvancedChatServer/8-Serial%20Monitor.JPG)

    