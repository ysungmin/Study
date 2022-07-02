# 인터넷
## 1.인터넷의 유래
* 인터넷은 미국방부의 ARPANET에서 유래했다. 
* ARPANET은 1969년 미국방부의 고등 연구 계획부 (Advanced Research Project Agency)에서 시작했다. 당시 만드려고 한 이유는 소련의 핵공격에도 무너지지 않는 통신 체계를 구축하기 위함 이었다.
* 당시 프로젝트의 리더는 Robert Wiliam Taylor (Bob Tayler) 였다.
* 이러한 ARPANET은 최초의 패킷 스위칭 내트워크였고 이 ARPANET의 수요가 증가함에 따라 ARPANET에서 군용 MILNET이 분리되고 학술용의 ARPANET이 남게 되었다. 
* 1973년 ARPANET을 위한 네트워크 개발을 위해 Robert Karn(Bob Karn), Vint Cerf가 TCP/IP 를 만들게 되었다.
*  1983년 ARPANET이 TCP/IP를 채택하게 되면서 지금의 인터넷이 되었다.

## 2. Word Wide Web
* WWW(Word wide Web)은 인터넷에 정보를 게시하기위해 가장 많이 쓰는 방식이다.
* WWW는 1989년 CERN의 Tim Berners-Lee가 당시 CERN의 문서의 유실문제로 문서를 전산화 하기위해 만들어 졌고 1991년에 오픈 되었다.
* WWW는 HTTP 기반으로 HTML문서를 Web Browser로 열 수 있게 되어있는 것이 특징이다.
* Web은 URL이 있는 Hyper Link를 지원하여 사용자가 쉽게 다른 문서를 찾는 것을 지원한다.
* Web은 인터넷 과는 다르며 그저 인터넷을 통해 제공되고 있을 뿐이다.


## 3.Packet
* Packet은 인터넷에서 데이터를 전송하는 기본 단위다.
* TCP 기준으로 Window 크기에 따라 최대 64KB까지 가능하지만 802.3표준에 따라 최소 크기 64Byte 최대 1518Byte(확장 : 1522Byte)로 제한하고 있다. 
* 이러한 제한은 802.3 이더넷 표준이 생길 당시 통신 매체, 속도, 안정성 등을 고려할 때 최적인 크기였다고 한다.


## 4. DNS
* 사용자가 ip 주소가 아닌 문자들(www.abcde.com)로 구성된 주소를 통해 접근하게 해주는 데이터 베이스 시스템이다. DNS는 입력된 도메인 이름을 입력받으면 대응되는 IP주소를 제공한다. 
*  **DNSSEC** (Domain Name System Security Extension) : DNS의 데이터 위변조를 막기위해 사용되는 기술로 공개키 DNS에 공개키 암호화 방식의 인증서를 적용한 것이다.

* **ICANN**(Internet Corporation for Assigned Name And Number)은 1998년 설립된 비영리 기관으로 도메인 이름들을 관리한다.
* 
* 도메인 이름의 종류는 크게 2가지로 나누어진다. 하나는 .com, .edu, .org 와 같은 gTLD(generic Top Level Domains)와 .us, .kr과 같이 각 나라마다 나라이름을 두자 씩 딴 ccTLD(country-code Top Level Domain) 이다.
 



## 3. 관련 용어
* The Last Mile : 네트워크에서 인터넷이 가정 혹은 사무실의 PC와 연결되는 1마일 내외의 마지막 구간을 말한다. 전화선, DSL, ISDN, 광섬유 등이 이에 포함된다. 무선 또한 이에 포함 될 수 있다.

* Backbone : 여러 소형 네트워크를 묶어서 다른 네트워크와 연결되는 네트워크

* IEP (Internet Exchenge Point) : ISP들의 네트워크들이 서로 만나는 지점에서 각 네트워크의 트래픽을 조절하는 역할을 하는 곳을 말한다.

* ISP (Internet Service Provider) : 인터넷에 접속하는 서비스를 제공하는 기관들을 말한다. 

* Data Center : 인터넷 사용자에게 웹서비스나 클라우드 서비스등을 제공하기 위해 서버가 모여 있는 곳

* SSL(Secure Socket Layer) : 1994 Netscape사에 의해 도입된 웹 사용자가 인터넷을 사용할 때 사용자의 정보를 암호화 하는 기술이다. 현재는 TLS로 대체되었고 SSL2.0과 SSL3.0은 더 이상 사용하지 않는 것이 권장된다.

* TLS(Transport Layer Security) : 시작은 SSL 3.1이었지만 Netscape가 빠지게 되면서 명칭을 TLS로 변경하게 되었다. 
