---
layout: post
title: 'How to use Arduino Ethernet Library IPv6 (WIZnet Ethernet Library)'
author: taylor.An
date: 2019-05-07 15:00
tags: [arduino,IPv6,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/Wiznet/Ethernet/tree/IPv6"></a>

# Arduino Ethernet Library - Default

You already installed Arduino IDE, you can use Ethernet Library as default.

Just you can run the Arduino IDE, and Choose File -> Examples -> Ethernet -> AdvancedChatServer.

![](/files/posts/2019-05-07/Default/1.jpg)

The below is default Ethernet Library Example AdvancedChatServer.

![](/files/posts/2019-05-07/Default/2.jpg)

The default Ethernet Library are located on "C:\Program Files (x86)\Arduino\libraries\Ethernet"

![](/files/posts/2019-05-07/Default/3.jpg)

And the default User Library are located on "C:\Users\'Your ID'\Documents\Arduino\libraries".

![](/files/posts/2019-05-07/Default/4.jpg)

# WIZnet Ethernet Library - Arduino Ethernet Library IPv6

## Download

Go to the WIZnet Ethernet Github and choose the IPv6 branch.

[WIZnet Ethernet Library IPv6](https://github.com/Wiznet/Ethernet/tree/IPv6)

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/1.jpg)

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/2.jpg)

If you don't want to use any git client, you can choose Download ZIP.

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/3.jpg)

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/4-download.jpg)

## Extract

Copy Ethernet-IPv6.zip downloaded and paste to Arduino User Library directory.

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/5-copy-paste.jpg)

Extract Ethernet-IPv6.zip and rename to Ethernet. The directory name must be Ethernet.

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/6-extract.jpg)

Below is tree view after extracted and renamed.

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/6-extract-2.jpg)

## Run

Now you can run the Arduino IDE and just Choose File -> Examples -> Ethernet -> AdvancedChatServer.

You can see the AdvancedChatServer of WIZnet Ethernet Library(Arduino Ethernet Library IPv6).

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/7.jpg)

After Upload, you can see the network information messages via Serial Monitor.

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/19-done.jpg)

The IPv6 is yours now.

# Trouble Shooting

## Ethernet shield was not found

If you see the message of "Ethernet shield was not found.",

You probably use the MKRVIDOR-4000(or use not supported board on Ethernet Library).

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/16-unknown-board.jpg)

If you are, you should add your board on Ethernet Library.

Open the w5100.cpp, are locaed on "C:\Users\'Your ID'\Documents\Arduino\libraries\Ethernet\src\utility".

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/17-unknown-board-2.jpg)

The MKRVIDOR-4000 is not added yet in Ethernet Library as default.

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/17-unknown-board-3.jpg)

You should add the MKRVIDOR-4000 like below and save.

![](/files/posts/2019-05-07/Github-WIZnet-Ethernet-IPv6/17-unknown-board-4.jpg)

