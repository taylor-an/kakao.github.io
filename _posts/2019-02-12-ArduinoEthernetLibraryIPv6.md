---
layout: post
title: 'WIZnet Arduino Ethernet Library IPv6'
author: taylor.An
date: 2019-02-12 13:00
tags: [arduino,IPv6,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/Wiznet/Ethernet/tree/IPv6"></a>

# 1. WIZnet Arduino Ethernet Library IPv6

WIZnet Arduino Ethernet Library IPv6 (https://github.com/Wiznet/Ethernet/tree/IPv6)

W6100의 IPv6 지원을 위하여 W6100에서 IPv6로 Branch하여 개발 진행 중입니다.

![](/files/posts/2019-02-12/Wiznet-Ethernet-IPv6-2.png)

WIZnet Arduino Ethernet Library의 TortoiseGit Revision Graph (https://tortoisegit.org/) 입니다.

![](/files/posts/2019-02-12/Wiznet-Ethernet-IPv6-RevisionGraph.png)

# 2. W6100 vs IPv6

W6100 Branch에서 파생된 IPv6 Branch는 아래와 같은 변경점을 갖고 있습니다.

현재 IPv6만 가능 합니다.

![](/files/posts/2019-02-12/Wiznet-Ethernet-IPv6-W6100vsIPv6.png)

IPv6의 지원을 위해서는 ArduinoCore-API (https://github.com/arduino/ArduinoCore-API)도 개발이 필요합니다.

WIZnet Arduino Ethernet Library IPv6에 Source Code를 포함하는 방향으로 개발 진행 중 입니다.

![](/files/posts/2019-02-12/ArduinoCore-API.png)

# 3. IPv6 Test

### 1) IPv6 Connectivity

IPv6 Connectivity (http://www.test-ipv6.cz/)

먼저 IPv6를 사용할 수 있는 환경인지 확인 합니다.

![](/files/posts/2019-02-12/TestyourIPv6connectivity.png)

### 2) WIZnet Arduino Ethernet Library IPv6

Github WIZnet Arduino Ethernet Library (https://github.com/Wiznet/Ethernet)

IPv6 Branch를 선택합니다.

Arduino IDE를 Default로 설치하면 Library Manager를 통해 Download한 Library는

'C:\Users\Your ID\Documents\Arduino\libraries'에 위치 합니다.

Download한 WIZnet Arduino Ethernet Library가 아래와 같은 경로를 갖도록 합니다.

C:\Users\Your ID\Documents\Arduino\libraries\Ethernet

### 3) ChatServer

Arduino Board와 Ethernet Shield가 사용가능 한지 확인 하고, ChatServer Example을 실행 합니다.

![](/files/posts/2019-02-12/ArduinoIDE-1Open-EthernetChatServer.png)

![](/files/posts/2019-02-12/ArduinoIDE-2Ethernet-ChatServer.png)

사용자 환경에 맞도록 Network를 설정 합니다.

![](/files/posts/2019-02-12/ArduinoIDE-3Ethernet-ChatServer-GUALLA.png)

Upload를 통해 Compile하고 Arduino Board에 Download 합니다.

![](/files/posts/2019-02-12/ArduinoIDE-4Ethernet-ChatServer-Uploading2.png)

Serial Monitor를 눌러 실행 합니다.

![](/files/posts/2019-02-12/ArduinoIDESerialMonitor-1.png)

### 4) Ping

ChatClient를 실행하기 전에 IPv6NOW(http://www.ipv6now.com.au/pingme.php)에서 Ping을 확인할 수 있습니다.

설정한 GUA를 입력하고 Ping now를 클릭하면 정상적으로 Ping이 이루어 지는 것을 확인 할 수 있습니다.

![](/files/posts/2019-02-12/IPv6NOW-2-EnterHostname.png)

![](/files/posts/2019-02-12/IPv6NOW-3-done.png)

네트워크 환경에 따라 Wireshark(https://www.wireshark.org/) 같은 Tool을 통해 Ping Packet을 확인할 수도 있습니다.

![](/files/posts/2019-02-12/WIRESHARK-2-ping.png)

### 4) ChatClient

ChatClient를 실행하여 ChatServer에 접속합니다.

여기서는 ScriptCommunicator(https://sourceforge.net/projects/scriptcommunicator/)를 사용합니다.

![](/files/posts/2019-02-12/ScriptCommunicator-1.png)

GUA로 설정.

![](/files/posts/2019-02-12/ScriptCommunicator-2-sockets-GUA.png)

또는 LLA로 설정.

![](/files/posts/2019-02-12/ScriptCommunicator-2-sockets-LLA.png)

ChatServer로 전송할 Message를 준비합니다.

![](/files/posts/2019-02-12/ScriptCommunicator-3-Message.png)

ChatServer는 Client가 접속 후 첫 전송하는 Message를 수신하여 'Hello, client!' Message를 앞에 붙여 전송 합니다.

![](/files/posts/2019-02-12/ScriptCommunicator-4-SendMessageandReceiveMessage.png)

Serial Monitor에서는 Client가 접속 후 첫 전송하는 Message를 수신하면 'We have a new client'를 출력하고 수신한 Message를 출력합니다.

![](/files/posts/2019-02-12/ArduinoIDESerialMonitor-2-ReceiveMessageandSendMessage.png)


### 5) Examples

[20190422] 현재 사용가능한 Example은 아래와 같습니다.

* [AdvancedChatServer](https://github.com/Wiznet/Ethernet/wiki/AdvancedChatServer)

* [BarometricPressureWebServer](https://github.com/Wiznet/Ethernet/wiki/BarometricPressureWebServer)

* [ChatServer](https://github.com/Wiznet/Ethernet/wiki/ChatServer)

* [DhcpAddressPrinter](https://github.com/Wiznet/Ethernet/wiki/DhcpAddressPrinter)

* [DhcpChatServer](https://github.com/Wiznet/Ethernet/wiki/DhcpChatServer)

* [LinkStatus](https://github.com/Wiznet/Ethernet/wiki/LinkStatus)

* [TelnetClient](https://github.com/Wiznet/Ethernet/wiki/TelnetClient)

* [UdpNtpClient](https://github.com/Wiznet/Ethernet/wiki/UdpNtpClient)

* [UDPSendReceiveString](https://github.com/Wiznet/Ethernet/wiki/UDPSendReceiveString)

* [WebClient](https://github.com/Wiznet/Ethernet/wiki/WebClient)

* [WebClientRepeating](https://github.com/Wiznet/Ethernet/wiki/WebClientRepeating)

* [WebServer](https://github.com/Wiznet/Ethernet/wiki/WebServer)
