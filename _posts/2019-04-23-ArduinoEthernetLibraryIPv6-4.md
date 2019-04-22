---
layout: post
title: 'BarometricPressureWebServer'
author: taylor.An
date: 2019-04-23 13:00
tags: [arduino,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/Wiznet/Ethernet/tree/IPv6"></a>

# [ArduinoEthernetLibraryIPv6] BarometricPressureWebServer

[Original tutorial BarometricPressureWebServer on Arduino Homepage](https://www.arduino.cc/en/Tutorial/BarometricPressureWebServer).

## Open Arduino IDE

Run Arduino IDE and Open "BarometricPressureWebServer.ino" sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/BarometricPressureWebServer/1-IDE-Open.JPG)

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
    
![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/BarometricPressureWebServer/2-IDE-SetNetworkInformation.JPG)

## Upload

Upload BarometricPressureWebServer sketch.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/BarometricPressureWebServer/3-IDE-Upload.JPG)

## Serial Monitor

Open serial monitor and you'll be able to see the your network information.

If defined NO_BAROMETRIC, temperature and pressure value will has increased by 1.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/BarometricPressureWebServer/4-Serial%20Monitor.JPG)

## Internet Browser

Run Internet Browser like Chrome.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/BarometricPressureWebServer/5-InternetBrowser.JPG)

## Internet Browser - Connect

Connect to BarometricPressureWebServer.

The BarometricPressureWebServer will has sent temperature and pressure value.

![](https://github.com/Wiznet/Ethernet/wiki/Jpg/IPv6/BarometricPressureWebServer/6-InternetBrowser-Connect.JPG)

