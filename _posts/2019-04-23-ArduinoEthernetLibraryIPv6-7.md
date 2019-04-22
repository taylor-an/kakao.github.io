---
layout: post
title: 'DhcpChatServer'
author: taylor.An
date: 2019-04-23 13:00
tags: [arduino,IPv6,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/Wiznet/Ethernet/tree/IPv6"></a>

# [ArduinoEthernetLibraryIPv6] DhcpChatServer

[Original tutorial DhcpChatServer on Arduino Homepage](https://www.arduino.cc/en/Tutorial/DhcpChatServer).

## Open Arduino IDE

Run Arduino IDE and Open "DhcpChatServer.ino" sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/1-IDE-Open.JPG)

## Upload

Upload DhcpChatServer sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/2-IDE-Upload.JPG)

## Serial Monitor

Open serial monitor and you'll be able to see the your network information.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/3-Serial%20Monitor.JPG)

## ScriptCommunicator

Run TCP Client like [ScriptCommunicator](https://sourceforge.net/projects/scriptcommunicator/).

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/4-ScriptCommunicator-Empty.JPG)

## ScriptCommunicator - Setting

The DhcpChatServer is TCP application.

Set DhcpChatServer's LLA or GUA as destination address and port as destination port.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/5-ScriptCommunicator-Settings.JPG)

## ScriptCommunicator - Connect

Connect to DhcpChatServer.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/6-ScriptCommunicator-Connect.JPG)

## ScriptCommunicator - Send

Send a message to DhcpChatServer.

The DhcpChatServer will return your message including string "Hello, client!".

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/7-ScriptCommunicator-Send.JPG)

## Serial Monitor - Result

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/DhcpChatServer/8-Serial%20Monitor.JPG)

