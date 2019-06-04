---
layout: post
title: 'Arduino MQTT IPv6'
author: taylor.An
date: 2019-06-04 15:00
tags: [arduino,IPv6,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/WIZnet-ArduinoEthernet/arduino-mqtt/tree/IPv6"></a>

IPv6를 통한 MQTT가 필요하십니까?

이제 가능 합니다.

Do you have a need to use MQTT via IPv6?

Now it's ready to use.

"The WIZnet arduino-mqtt - IPv6 Branch"

![](/files/posts/2019-06-04/MQTT.jpg)

# WIZnet Ethernet Library

WIZnet arduino-mqtt IPv6 브랜치는 WIZnet Ethernet Library IPv6 브랜치가 필요합니다.

The WIZnet arduino-mqtt IPv6 branch requires the WIZnet Ethernet Library IPv6 branch.

* [WIZnet Ethernet Library IPv6 사용방법](https://github.com/Wiznet/Ethernet/wiki/Howtouse)

* [How to use Arduino Ethernet Library IPv6 (WIZnet Ethernet Library)](https://github.com/Wiznet/Ethernet/wiki/Howtouse)

# Download

WIZnet arduino-mqtt Github에서 IPv6 브랜치를 선택합니다.

Go to the WIZnet arduino-mqtt Github and choose the IPv6 branch.

[WIZnet arduino-mqtt IPv6](https://github.com/WIZnet-ArduinoEthernet/arduino-mqtt/tree/IPv6)

![](/files/posts/2019-06-04/1.jpg)

![](/files/posts/2019-06-04/2.jpg)

Git Client를 사용하지 않아도 ZIP으로 Download 할 수 있습니다.

If you don't want to use any git client, you can choose Download ZIP.

![](/files/posts/2019-06-04/3.jpg)

가입이나 로그인을 하지 않아도 가능 합니다.

No sign-in required and no sign-up required.

![](/files/posts/2019-06-04/4-download.jpg)

# Extract

Download한 arduino-mqtt-IPv6.zip을 복사하여 Arduino 사용자 Library 경로에 붙여 넣습니다.

Copy an arduino-mqtt-IPv6.zip downloaded and paste to Arduino User Library directory.

![](/files/posts/2019-06-04/5-copy-paste.jpg)

arduino-mqtt-IPv6.zip의 압축을 풀고, 이름을 arduino-mqtt로 변경합니다. arduino-mqtt의 이름으로만 사용할 수 있습니다.

Extract an arduino-mqtt-IPv6.zip and rename to arduino-mqtt. The directory name must be arduino-mqtt.

![](/files/posts/2019-06-04/6-extract.jpg)

압축을 풀고 이름을 바꾼후 Tree view는 아래와 같습니다

The following is tree view after extracted and renamed.

![](/files/posts/2019-06-04/6-extract-2.jpg)

# Run

이제 Arduino IDE를 실행하고, File -> Examples -> MQTT -> W6100EthernetShield를 선택 하면 됩니다.

Now you can run the Arduino IDE and just Choose File -> Examples -> MQTT -> W6100EthernetShield.

WIZnet arduino-mqtt(Arduino MQTT Library IPv6)의 W6100EthernetShield를 확인할 수 있습니다.

You can see the W6100EthernetShield of WIZnet arduino-mqtt.

![](/files/posts/2019-06-04/7.jpg)

Upload 후 Serial Monitor를 실행하면 network 정보를 확인할 수 있습니다.

After Upload, you can see the network information messages via Serial Monitor.

W6100EthernetShield 예제는 test.mosquitto.org에 IPv6로 접속합니다. 그리고 W6100 이름의 topic에 publish와 subscribe를 진행합니다.

This W6100EthernetShield example connects to test.mosquitto.org via IPv6. And it publishes to topic of W6100. It also subscribes topic of 
W6100.

![](/files/posts/2019-06-04/8.jpg)

# HIVEMQ Web Socket Client

또한 어느곳에서나 Web browser를 통해 subscribe할 수 있습니다.

You also subscribe it at any place via web browser.

Web browser를 실행하여 HIVEMQ Web Socket Client에 접속합니다.

Run web browser and access [HIVEMQ Web Socket Client](http://www.hivemq.com/demos/websocket-client/).

![](/files/posts/2019-06-04/9.jpg)

Host와 Port를 설정합니다.

Set Connection Host, Port

* Host : test.mosquitto.org
* Port : 8080

![](/files/posts/2019-06-04/10.jpg)

그리고 Connect로 접속합니다.

And Connect

![](/files/posts/2019-06-04/11.jpg)

이제 W6100 이름의 topic을 subscribe할 수 있습니다.

Finally, you can subscribe W6100 topic.

![](/files/posts/2019-06-04/12.jpg)

그리고 test.mosquitto.org를 통해 W6100EthernetShield 예제에서 publish한 메세지를 볼 수 있습니다.

And you can see the message from test.mosquitto.org which W6100EthernetShield published.

![](/files/posts/2019-06-04/13.jpg)

