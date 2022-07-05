# Network Device
1. Hub : 여러개의 장비를 LAN에 접속할 수 있게 해주는 장비다. 한 장비로 프레임이 전송될 경우 다른 모든 장비로 프레임이 전송되는 Flooding이 발생하고 반이중 통신을 한다.

2. Switch : Hub와 마찬가지로 여러개의 장비를 LAN에 접속할 수 있게 해주는 장비다. 하지만 Hub와 ARP 테이블을 가지고 있기 때문에 Floding을 하지 않고 해당 MAC 주소의 장비로 전송 할 수 있으며 전이중 도 지원한다.

3. Router : IP 주소등 3계층의 주소를 확인하여 목적지로 연결되는 포트로 메시지를 전달하는 장비

4. 공유기 : 현재 가정에서 사용하는 공유기는 Router NAT기능에 Hub 기능, 무선 Wifi 기능이 추가된 것이다. 영어로는 그냥 위와 동일하게 Router라고 한다.

5. Modem(MOdulator and DEModulator) : 정보 전달을 위해 신호를 변조하여 송신하고 수신후 다시 복조하는 장치

* Flooding : 본래 Unicast인 것을 연결된 모든 경로로 메시지를 보내는 것
* Broadcast : Broadcast를 뜻하는 주소에 의해 같은 도메인 내에 모든 호스트에게 메시지를 보내는 것
* NAT(Network Address Translation) : IP 패킷의 TCP, UDP, 포트 번호나 목적지 IP주소를 재기록하고 Router를 통해 네트워크 트래픽을 주고받는 기술. 보통 이를 이용하여 1개의 IP주소로 여러 호스트가 동시 사용할 수 있게 해준다.
