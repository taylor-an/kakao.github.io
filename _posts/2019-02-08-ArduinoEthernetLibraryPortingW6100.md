---
layout: post
title: 'Poting W6100 on Arduino Ethernet Library v2.0.0 IPv4'
author: taylor.An
date: 2019-02-08 13:00
tags: [tag-test]
image: /files/covers/head-tail.jpg
---
# 1. Arduino Ethernet Library

Arduino Ethernet Library (https://www.arduino.cc/en/Reference/Libraries)

Arduino IDE에 기본 포함되어 있는 Ethernet Library로

현재 v2.0.0이 포함되어 있고, WIZnet W5100, W5200, W5500을 지원 합니다.

![](/files/posts/2018-11-15/ArduinoEthernetLibrary.png)

# 2. Github

Github (https://github.com/arduino-libraries/Ethernet)

개발은 Github에서 이뤄 지고 있으며, PaulStoffregen(https://github.com/PaulStoffregen)에 의해 관리됩니다.

![](/files/posts/2018-11-15/Github.png)

# 3. PJRC

PJRC (https://www.pjrc.com/arduino-ethernet-library-2-0-0)

PaulStoffregen이 운영하는 Site에서 Arduino Ethernet Library 2.0.0 Release 소식과 Test 한 내용을 볼 수 있습니다.

다양한 Arduino Board와 WIZnet Chip을 사용한 Ethernet Shield의 Test를 거쳐 Release 되었습니다.

![](/files/posts/2018-11-15/PJRC.jpg)

# 4. W6100

W6100 (https://wizwiki.net/wiki/doku.php?id=products:w6100:start)

IPv4와 IPv6를 지원하는 W6100가 출시 예정입니다.

![](/files/posts/2019-02-08/W6100.png)

# 5. W6100 Ethernet Shield

곧 W6100 Ethernet Shield 제품도 출시하거나, 다른 Maker에 의해 출시되길 기원합니다.


# 6. W6100 Porting on Arduino Ethernet Library v2.0.0

Arduino Ethernet Library v2.0.0은 W5100, W5200, W5500을 지원하며 이런 정책에 따라 새로 출시한 W6100도 지원하기 위해서는 Library에 추가하는 작업이 필요 합니다.

Github WIZnet Arduino Ethernet Library (https://github.com/Wiznet/Ethernet)

Master Branch 또는 W6100 Branch를 선택합니다.

Source Code를 Doxygen (http://www.doxygen.org)을 사용하여 살펴 보면 쉽게 파악할 수 있습니다.

Arduino Ethernet Library v2.0.0의 W5100Class:Init

![](/files/posts/2018-11-15/W5100Class-Init.png)

W5100Class::isWXXXX(W5100, W5200, W5500)의 존재를 확인 할 수 있습니다.

W6100을 위해 기타 추가 작업을 진행 합니다.

Arduino Ethernet Library v2.0.0에 W6100을 추가한 후 W5100Class:Init

![](/files/posts/2019-02-08/W5100Class-Init-Added-W6100.jpg)

작업이 완료되면 Test 과정을 꼭 진행해야합니다.

Aduino Ethernet Library에서는 아래와 같이 Example을 함께 제공합니다.

모두 Test해 봅니다.

![](/files/posts/2019-02-08/Examples.png)

Test가 되면 Arduino Ethernet Library에 공식 적용을 위한 절차를 밟습니다.

Arduino의 Ethernet Library는 Github에서 Pull request를 통해 head version에 반영 됩니다.

![](/files/posts/2019-02-08/PullRequest.png)
