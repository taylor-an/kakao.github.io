---
layout: post
title: 'Riots Affordable wireless IoT microcontrollers and sensors'
author: taylor.An
date: 2019-03-06 13:00
tags: [arduino,WIZnet]
image: /files/covers/head-tail.jpg
---

<a id="forkme" href="https://github.com/myriots"></a>

WIZnet의 W5500 (https://www.wiznet.io/ko/product-item/w5500/)을 사용한 Riots Instrument Inc.의 IoT Platform Riots 를 소개 합니다.

# 1. Riots

Riots는 Kickstarter에서 Affordable wireless IoT microcontrollers and sensors (https://www.kickstarter.com/projects/riotsinstruments/riots-aware-for-you)로

2015년 12월 23일부터 2016년 2월 1일까지 39일 동안 375명의 후원자로 부터 $43,037를 후원받았습니다.

![](/files/posts/2019-03-06/Riots-2.jpg)

Riots는 성공적으로 Project를 진행했고, 후원자와의 약속을 지켰으며 상품화에 성공하였습니다.

![](/files/posts/2019-03-06/Riots-1.jpg)

# 2. Affordable wireless IoT microcontrollers and sensors

Riots Patform은 작고 쉽게 사용가능한 IoT Sensor Network Solution입니다.

![](/files/posts/2019-03-06/Riots-3.jpg)

### Riots Mama

Riots Mama는 WIZnet의 W5500을 사용한 Gateway로 Riots Cloud에 접속 가능하게 합니다.

![](/files/posts/2019-03-06/Riots-8-mama.png)

W5500은 Hardwired TCP/IP Stack을 내장한 Ethernet Chip 입니다.

Microcontroller로 시스템을 구성함에 있어 Software로 TCP/IP Stack을 운용하는 것은 상당한 부담이었습니다.

W5500과 같은 iEthernet Chip을 통해 Microcontroller는 간단한 Data 전송만으로 이를 가능하게 합니다.

### Riots Babies

Riots Babies는 Network Node이며 Sensor(Riots Gyro, Riots Light, Riots Air)를 포함할 수 있습니다.

하나의 Riots Mama는 수백의 Riots Babies를 Monitoring하고 관리할 수 있습니다.

![](/files/posts/2019-03-06/Riots-4.png)

Riots의 Babies는 Nordic Semiconductor (https://www.nordicsemi.com/)

2.4GHz proprietary RF 기반의 무선 Protocol을 사용합니다.

![](/files/posts/2019-03-06/Riots-7-nodes.jpg)

Riots의 Babies는 여러 Network 형태를 가질수 있습니다. Mama를 통하지 않고 Babies 간의 통신도 가능합니다.

전원으로 CR2032 배터리를 사용하며 실시간 데이터 클라우드 전송일 때 1년 정도로 다른 배터리 지원 계획을 가지고 있습니다.

# 3. Open Hardware Open Source

Riots는 Open Hardware / Open Source 이며 부분적으로 공개 되었고 추후 공개될 예정입니다.

아래는 Riots Core의 Description 으로 Kickstarter에 공개 되어 있습니다.

![](/files/posts/2019-03-06/Riots-5-core.PNG)

Source는 Github를 통해 공개하고 있습니다.

![](/files/posts/2019-03-06/Riots-6-Github.png)

Riots의 제품은 Arduino Project 중 하나 입니다.

![](/files/posts/2019-03-06/ArduinoIDE.png)

누구든 개발하고 사용할 수 있습니다.

![](/files/posts/2019-03-06/Riots-Github-Product.png)

IoT Network에 관심 있는 분들에게 좋은 자료가 될 것같습니다.

# 4. Cloud

Riots Mama를 통해 수집된 Data는 Riots Cloud나 개인 Network를 통해 관리할 수 있습니다.

현재 Cloud는 2가지 Option으로 제공됩니다.

* 제한된 데이터 저장 및 대역폭을 포함하여 99% 서비스 수준의 무료 Cloud

* 무제한 데이터 저장 및 대역폭을 포함하고 외부 서비스에 통합하기 위한 인터페이스를 포함한 100% 서비스 수준의 고급 Cloud

![](/files/posts/2019-03-06/Riots-Cloud.png)

Moblie로도 가능 합니다.

![](/files/posts/2019-03-06/Riots-Mobile.png)

# 5. WIZnet IoT 서비스

WIZnet은 IoT에 많은 관심을 가지고 있으며 IoT 시대를 준비하고 있습니다.

그리고 IoT 서비스 (https://www.wiznet.io/ko/home/iot서비스/)를 진행하고 있습니다.

삶을 풍요롭게 해줄 IoT 시대를 상상해 봅니다.

![](/files/posts/2019-03-06/WIZnetIoT.png)
