---
layout: post
title: 'UDPSendReceiveString'
author: taylor.An
date: 2019-04-23 13:00
tags: [arduino,IPv6,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/Wiznet/Ethernet/tree/IPv6"></a>

# [ArduinoEthernetLibraryIPv6] UDPSendReceiveString

[Original tutorial UDPSendReceiveString on Arduino Homepage](https://www.arduino.cc/en/Tutorial/UDPSendReceiveString).

## Open Arduino IDE

Run Arduino IDE and Open "UDPSendReceiveString.ino" sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/1-IDE-Open.JPG)

## Upload

Upload UDPSendReceiveString sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/2-IDE-Upload.JPG)

## Serial Monitor

Open serial monitor and you'll be able to see the your network information.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/3-Serial%20Monitor.JPG)

## ScriptCommunicator

Run TCP Client like [ScriptCommunicator](https://sourceforge.net/projects/scriptcommunicator/).

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/4-ScriptCommunicator-Empty.JPG)

## ScriptCommunicator - Setting

The UDPSendReceiveString is UDP application.

Set UDPSendReceiveString's LLA or GUA as destination address and port as destination port.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/5-ScriptCommunicator-Settings.JPG)

## ScriptCommunicator - Connect

Connect to UDPSendReceiveString.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/6-ScriptCommunicator-Connect.JPG)

## ScriptCommunicator - Send

Send a message to UDPSendReceiveString.

The UDPSendReceiveString will send a string "acknowledged".

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/7-ScriptCommunicator-Send.JPG)

## Serial Monitor - Result

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/UDPSendReceiveString/8-Serial%20Monitor.JPG)

