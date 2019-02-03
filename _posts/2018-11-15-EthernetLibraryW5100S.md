---

---

<h2 id="arduino-ethernet-library">1. Arduino Ethernet Library</h2>
<p>Arduino Ethernet Library(<a href="https://www.arduino.cc/en/Reference/Libraries">https://www.arduino.cc/en/Reference/Libraries</a>)</p>
<p>Arduino IDE에 기본 포함되어 있는 Ethernet Library로</p>
<p>현재 v2.0.0이 포함되어 있고, WIZnet W5100, W5200, W5500을 지원 합니다.</p>
<p><img src="http://pds21.egloos.com/pds/201811/15/64/f0122164_5bed03a8f40ae.png" alt=""></p>
<h2 id="github">2. Github</h2>
<p>Github(<a href="https://github.com/arduino-libraries/Ethernet">https://github.com/arduino-libraries/Ethernet</a>)</p>
<p>개발은 Github에서 이뤄 지고 있으며, PaulStoffregen(<a href="https://github.com/PaulStoffregen">https://github.com/PaulStoffregen</a>)에 의해 관리됩니다.</p>
<p><img src="http://pds21.egloos.com/pds/201811/15/64/f0122164_5bed051076b24.png" alt=""></p>
<h2 id="pjrc">3. PJRC</h2>
<p>PJRC(<a href="https://www.pjrc.com/arduino-ethernet-library-2-0-0">https://www.pjrc.com/arduino-ethernet-library-2-0-0</a>)</p>
<p>PaulStoffregen이 운영하는 Site에서 Arduino Ethernet Library 2.0.0 Release 소식과 Test 한 내용을 볼 수 있습니다.</p>
<p>다양한 Arduino Board와 WIZnet Chip을 사용한 Ethernet Shield의 Test를 거쳐 Release 되었습니다.</p>
<p><img src="http://pds21.egloos.com/pds/201811/15/64/f0122164_5bed041864db4.jpg" alt=""></p>
<h2 id="w5100s">4. W5100S</h2>
<p>W5100S (<a href="https://www.wiznet.io/ko/product-item/w5100s/">https://www.wiznet.io/ko/product-item/w5100s</a>)</p>
<p>W5100 (<a href="https://www.wiznet.io/ko/product-item/w5100/">https://www.wiznet.io/ko/product-item/w5100</a>)을 개선한 W5100S가 출시 되었습니다.</p>
<p><img src="http://pds25.egloos.com/pds/201811/15/64/f0122164_5bed071d13dcc.png" alt=""></p>
<h2 id="w5100s-ethernet-shield">5. W5100S Ethernet Shield</h2>
<p>곧 W5100S Ethernet Shield 제품도 출시하거나, 다른 Maker에 의해 출시되길 기원합니다.</p>
<h2 id="w5100s-porting-on-arduino-ethernet-library-v2.0.0">6. W5100S Porting on Arduino Ethernet Library v2.0.0</h2>
<p>Arduino Ethernet Library v2.0.0은 W5100, W5200, W5500을 지원하며 이런 정책에 따라 새로 출시한 W5100S도 지원하기 위해서는 Library에 추가하는 작업이 필요 합니다.</p>
<p>Github WIZnet Arduino Ethernet Library (<a href="https://github.com/Wiznet/Ethernet">https://github.com/Wiznet/Ethernet)</a></p>
<p>Source Code를 Doxygen (<a href="http://www.doxygen.org/">http://www.doxygen.org</a>)을 사용하여 살펴 보면 쉽게 파악할 수 있습니다.</p>
<p>Arduino Ethernet Library v2.0.0의 W5100Class:Init</p>
<p><img src="http://pds21.egloos.com/pds/201811/15/64/f0122164_5bed09e9dd37f.png" alt="">W5100Class::isWXXXX(W5100, W5200, W5500)의 존재를 확인 할 수 있습니다.</p>
<p>W5100S를 위해 기타 추가 작업을 진행 합니다.</p>
<p>Arduino Ethernet Library v2.0.0에 W5100S를 추가한 후 W5100Class:Init</p>
<p><img src="http://pds21.egloos.com/pds/201811/15/64/f0122164_5bed0a0866cff.jpg" alt=""></p>
<p>작업이 완료되면 Test 과정을 꼭 진행해야합니다.</p>
<p>Aduino Ethernet Library에서는 아래와 같이 Example을 함께 제공합니다.</p>
<p>모두 Test해 봅니다.</p>
<p><img src="http://pds25.egloos.com/pds/201811/15/64/f0122164_5bed0af3aef69.png" alt="">Test가 되면 Arduino Ethernet Library에 공식 적용을 위한 절차를 밟습니다.</p>
<p>Arduino의 Ethernet Library는 Github에서 Pull request를 통해 head version에 반영 됩니다.</p>
<p><img src="http://pds21.egloos.com/pds/201811/15/64/f0122164_5bed0b803dcb6.png" alt=""></p>
<p>하루 빨리, 공식 Ethernet Library에 포함되어 배포되길 바랍니다.</p>

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIwMTI5OTk4M119
-->