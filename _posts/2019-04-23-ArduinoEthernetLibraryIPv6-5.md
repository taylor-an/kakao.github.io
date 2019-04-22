---
layout: post
title: 'ChatServer'
author: taylor.An
date: 2019-04-23 13:00
tags: [arduino,IPv6,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/Wiznet/Ethernet/tree/IPv6"></a>

# [ArduinoEthernetLibraryIPv6] ChatServer

[Original tutorial ChatServer on Arduino Homepage](https://www.arduino.cc/en/Tutorial/ChatServer).

## Open Arduino IDE

Run Arduino IDE and Open "ChatServer.ino" sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/1-IDE-Open.JPG)

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
    
![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/2-IDE-SetNetworkInformation.JPG)

## Upload

Upload ChatServer sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/3-IDE-Upload.JPG)

## Serial Monitor

Open serial monitor and you'll be able to see the your network information.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/4-Serial%20Monitor.JPG)

## ScriptCommunicator

Run TCP Client like [ScriptCommunicator](https://sourceforge.net/projects/scriptcommunicator/).

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/5-ScriptCommunicator-Empty.JPG)

## ScriptCommunicator - Setting

The ChatServer is TCP application.

Set ChatServer's LLA or GUA as destination address and port as destination port.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/6-ScriptCommunicator-Settings.JPG)

## ScriptCommunicator - Connect

Connect to ChatServer.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/7-ScriptCommunicator-Connect.JPG)

## ScriptCommunicator - Send

Send a message to ChatServer.

The ChatServer will return your message including string "Hello, client!".

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/8-ScriptCommunicator-Send.JPG)

## Serial Monitor - Result

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/ChatServer/9-Serial%20Monitor.JPG)

