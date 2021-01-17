---
title: IP Multimedia Subsystem
---

From Wikipedia, the free encyclopedia

IP 멀티미디어 서브시스템 또는 IP 멀티미디어 코어 네트워크 서브시스템 (IMS)은 IP 멀티미디어 서비스를 제공하기위한 아키텍처 프레임워크입니다. 역사적으로 휴대폰은 IP 패킷 교환 네트워크를 통해서가 아니라 회선 교환 방식의 네트워크를 통해 음성 통화 서비스를 제공했습니다. 음성 (VoIP) 또는 기타 멀티미디어 서비스를 제공하는 대체 방법이 스마트 폰에서 사용 가능해졌지만 업계 전반에 걸쳐 표준화되지 않았습니다. IMS는 이러한 표준화를 제공하는 아키텍처 프레임워크입니다.

IMS는 원래 GSM을 넘어 진화하는 모바일 네트워크에 대한 비전의 일환으로 무선 표준기구 3GPP (3rd Generation Partnership Project)에 의해 설계되었습니다. 원래 공식 (3GPP Rel-5)은 GPRS를 통해 인터넷 서비스를 제공하기위한 접근 방식을 나타냅니다. 이 비전은 나중에 무선 LAN, CDMA2000 및 유선 회선과 같은 GPRS 이외의 네트워크 지원을 요구함으로써 3GPP, 3GPP2 및 ETSI TISPAN에 의해 업데이트되었습니다.

IMS는 가능하면 SIP (Session Initiation Protocol)와 같은 IETF 프로토콜을 사용합니다. 3GPP에 따르면 IMS는 응용 프로그램을 표준화하기위한 것이 아니라 무선 및 유선 터미널에서 멀티미디어 및 음성 응용 프로그램에 액세스하는 것을 지원하기위한 것입니다. 즉, 고정 모바일 컨버전스 (FMC)의 형태를 만드는 것입니다. [1] 이는 서비스 계층에서 액세스 네트워크를 분리하는 수평 제어 계층을 사용하여 수행됩니다. 논리적 아키텍처 관점에서 볼 때 제어 계층은 공통 수평 계층이므로 서비스에 자체 제어 기능이 필요하지 않습니다. 그러나 구현시 이것이 반드시 비용과 복잡성을 크게 줄이는 것은 아닙니다.

유선 및 무선 네트워크에서 서비스의 액세스 및 프로비저닝을위한 대체 및 중복 기술에는 일반 액세스 네트워크, 소프트 스위치 및 "네이 키드"SIP의 조합이 포함됩니다.

기존의 무선 / 고정 통신 사업자의 통제를 벗어난 메커니즘을 사용하여 콘텐츠 및 연락처에 액세스하는 것이 점점 더 쉬워지면서 IMS의 관심이 도전 받고 있습니다. [2]

IMS 기반 글로벌 표준의 예로는 VoLTE (Voice over LTE), Wi-Fi Calling (VoWIFI), SMS / MMS over WiFi 및 Joyn 또는 Advanced Messaging으로도 알려진 RCS (Rich Communication Services)의 기반이되는 MMTel이 있습니다. .

## History
* 1999 년에 형성된 3G.IP라는 산업 포럼에서 정의한 IMS. 3G.IP는 UMTS 네트워크의 3G 이동 전화 시스템에 대한 표준화 작업의 일부로 3GPP (3rd Generation Partnership Project)에 도입된 초기 IMS 아키텍처를 개발했습니다. SIP 기반 멀티미디어가 추가된 Release 5 (2G에서 3G 네트워크로의 진화)에 처음 등장했습니다. 이전 GSM 및 GPRS 네트워크에 대한 지원도 제공되었습니다. [3]
* 3GPP2 (3GPP와 다른 조직)는 3GPP IMS에서 CDMA2000 멀티미디어 도메인 (MMD)을 기반으로 CDMA2000에 대한 지원을 추가합니다.
* 3GPP 릴리스 6은 WLAN과의 연동, 서로 다른 IP 연결 네트워크를 사용하는 IMS 간의 상호 운용성, 라우팅 그룹 ID, 다중 등록 및 분기, 프레즌스, 음성 인식 및 음성 지원 서비스 (Push to talk)를 추가했습니다.
* 3GPP 릴리스 7은 TISPAN 릴리스 R1.1과 함께 작동하여 고정 네트워크에 대한 지원을 추가했으며, AGCF (액세스 게이트웨이 제어 기능) 및 PES (PSTN 에뮬레이션 서비스) 기능이 서비스 상속을 위해 유선 네트워크에 도입되었습니다. 이는 PSTN 네트워크에서 제공 할 수 있습니다. AGCF는 IMS 네트워크와 Megaco / H.248 네트워크를 연결하는 다리 역할을합니다. Megaco / H.248 네트워크는 기존 레거시 네트워크의 터미널을 IP 네트워크를 기반으로 한 차세대 네트워크에 연결할 수있는 가능성을 제공합니다. AGCF는 IMS에 대한 SIP 사용자 에이전트 역할을하며 P-CSCF의 역할을 수행합니다. SIP 사용자 에이전트 기능은 AGCF에 포함되며 고객 장치가 아니라 네트워크 자체에 포함됩니다. 또한 회선 스위칭과 패킷 스위칭 도메인 (VCC) 간의 음성 통화 연속성, IMS에 대한 고정 광대역 연결, 비 IMS 네트워크와의 연동, 정책 및 충전 제어 (PCC), 비상 세션이 추가되었습니다.
* 3GPP 릴리스 8은 LTE / SAE, 멀티미디어 세션 연속성, 향상된 비상 세션 및 IMS 중앙 집중식 서비스에 대한 지원을 추가했습니다.
* 3GPP 릴리스 9에는 GPRS 및 EPS를 통한 IMS 긴급 통화 지원, 멀티미디어 전화 통신 향상, IMS 미디어 플레인 보안, 서비스 중앙 집중화 및 연속성 향상이 추가되었습니다.
* 3GPP 릴리스 10은 장치 간 전송 지원, SRVCC (단일 무선 음성 통화 연속성) 향상, IMS 비상 세션 향상을 추가했습니다.
* 3GPP 릴리스 11에는 USSD 시뮬레이션 서비스, IMS에 대한 네트워크 제공 위치 정보, IMS에서 MSISDN없이 SMS 제출 및 전달, 과부하 제어가 추가되었습니다.

일부 운영자는 IMS가 복잡하고 비싸기 때문에 반대했습니다. 이에 대응하여 LTE 네트워크를 통한 음성 및 SMS를 지원하기에 충분한 IMS 인 IMS의 축소 버전이 2010 년에 VoLTE (Voice over LTE)로 정의되고 표준화되었습니다. [4]

## Architecture
![3GPP / TISPAN IMS architectural overview](https://upload.wikimedia.org/wikipedia/commons/6/60/Ims_overview.png)
*3GPP / TISPAN IMS architectural overview*

![3GPP / TISPAN IMS architectural overview – HSS in IMS layer (as by standard)](https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Ims_overview-2.png/825px-Ims_overview-2.png)
*3GPP / TISPAN IMS architectural overview – HSS in IMS layer (as by standard)*

다이어그램의 각 기능은 아래에 설명되어 있습니다.

IP 멀티미디어 핵심 네트워크 하위 시스템은 하나의 IMS 관리 네트워크를 구성하는 표준화 된 인터페이스로 연결된 다양한 기능의 모음입니다. [5] 기능은 노드가 아닙니다 (하드웨어 상자) : 구현자는 자유롭게 하나의 노드에 두 개의 기능을 결합하거나 단일 기능을 두 개 이상의 노드로 분할 할 수 있습니다. 각 노드는 차원,로드 균형 조정 또는 조직 문제를 위해 단일 네트워크에 여러 번 존재할 수도 있습니다.

## Access network
사용자는 대부분 표준 IP를 사용하는 다양한 방법으로 IMS에 연결할 수 있습니다. IMS 단말기 (예 : 휴대폰, PDA 및 컴퓨터)는 다른 네트워크 또는 국가 (방문 네트워크)에서 로밍 중일 때도 IMS에 직접 등록 할 수 있습니다. 유일한 요구 사항은 IP를 사용하고 SIP 사용자 에이전트를 실행할 수 있다는 것입니다. 고정 액세스 (예 : 디지털 가입자 회선 (DSL), 케이블 모뎀, 이더넷), 모바일 액세스 (예 : W-CDMA, CDMA2000, GSM, GPRS) 및 무선 액세스 (예 : WLAN, WiMAX)가 모두 지원됩니다. 일반 구형 전화 서비스 (POTS-구형 아날로그 전화), H.323 및 비 IMS 호환 시스템과 같은 기타 전화 시스템은 게이트웨이를 통해 지원됩니다.

## Core network

### HSS - Home subscriber server:
HSS (Home Subscriber Server) 또는 UPSF (User Profile Server Function)는 실제로 호출을 처리하는 IMS 네트워크 엔티티를 지원하는 마스터 사용자 데이터베이스입니다. 여기에는 구독 관련 정보 (구독자 프로필)가 포함되어 있고 사용자의 인증 및 권한 부여를 수행하며 구독자의 위치 및 IP 정보에 대한 정보를 제공 할 수 있습니다. GSM 홈 위치 레지스터 (HLR) 및 인증 센터 (AuC)와 유사합니다.

여러 HSS가 사용되는 경우 사용자 주소를 매핑하려면 SLF (가입자 위치 기능)가 필요합니다.

### User identities
다양한 ID(identities)가 IMS와 연관 될 수 있습니다 : IP 멀티미디어 사설 ID (IMPI), IP 멀티미디어 공용 ID (IMPU), 글로벌 라우팅 가능 사용자 에이전트 URI (GRUU), 와일드 카드 공용 사용자 ID. IMPI와 IMPU는 모두 전화 번호나 다른 일련의 숫자가 아니라 숫자 (tel : + 1-555-123-4567과 같은 Tel URI) 또는 영숫자 식별자(sip:john.doe@example.com 와 같은 SIP URI)로 된 Uniform Resource Identifier 입니다.

### IP Multimedia Private Identity:
IMPI (IP Multimedia Private Identity)는 홈 네트워크 운영자가 할당 한 고유 한 영구적으로 할당 된 글로벌 ID로, NAI (Network Access Identifier), 즉 user.name@domain의 형태를 가지며, 예를 들어 등록, 권한 부여, 관리 및 회계 목적에 사용됩니다. 모든 IMS 사용자는 하나의 IMPI를 가져야합니다.

### IP Multimedia Public Identity:
IMPU (IP Multimedia Public Identity)는 모든 사용자가 다른 사용자에게 통신을 요청하는 데 사용됩니다 (예 : 명함에 포함될 수 있음). AOR (Address of Record)이라고도합니다. IMPI 당 여러 IMPU가있을 수 있습니다. IMPU는 다른 전화와 공유 할 수도 있으므로 두 전화 모두 동일한 ID (예 : 전체 가족을위한 단일 전화 번호)로 연결할 수 있습니다.

### Globally Raoutable User Agent URI:
GRUU (Globally Routable User Agent URI)는 IMPU 및 UE 인스턴스의 고유 한 조합을 식별하는 ID입니다. GRUU에는 Public-GRUU (P-GRUU)와 Temporary GRUU (T-GRUU)의 두 가지 유형이 있습니다.
* P-GRUU는 IMPU를 공개하고 매우 오래 살았습니다.
* T-GRUU는 IMPU를 공개하지 않으며 연락처가 명시적으로 등록 취소되거나 현재 등록이 만료 될 때까지 유효합니다.

### Wildcarded Public User Identity:
와일드 카드 공용 사용자 ID(Wildcarded Public User Identity)는 함께 그룹화 된 IMPU 집합을 나타냅니다.

HSS 구독자 데이터베이스에는 IMPU, IMPI, IMSI, MSISDN, 구독자 서비스 프로필, 서비스 트리거 및 기타 정보가 포함됩니다.

## Call Session Control Function (CSCF)
총괄적으로 통화 세션 제어 기능 (CSCF)이라고하는 SIP 서버 또는 프록시의 여러 역할은 IMS에서 SIP 신호 패킷을 처리하는 데 사용됩니다.

* Proxy-CSCF (P-CSCF)는 IMS 터미널에 대한 첫 번째 접점인 SIP 프록시입니다. 방문한 네트워크 (전체 IMS 네트워크에서) 또는 홈 네트워크 (방문한 네트워크가 아직 IMS를 준수하지 않는 경우)에 위치 할 수 있습니다. 일부 네트워크는 이 기능을 위해 SBC (Session Border Controller)를 사용할 수 있습니다. P-CSCF는 네트워크를 보호 할뿐만 아니라 IMS 터미널을 보호하는 사용자 네트워크 인터페이스를 위한 특수 SBC의 핵심입니다. IMS 터미널과 P-CSCF 사이에 추가 SBC를 사용하는 것은 이 레그에서 암호화되는 시그널링으로 인해 불필요하고 실행 불가능합니다. 터미널은 DHCP를 사용하여 P-CSCF를 발견하거나 구성되거나(예 : 초기 프로비저닝 중 또는 3GPP IMS 관리 개체 (MO)를 통해) ISIM에 있거나 PDP 컨텍스트에 할당 될 수 있습니다(GPRS (General Packet Radio Service) 상에서).
    * 등록 전에 IMS 단말기에 할당되며 등록 기간 동안 변경되지 않습니다.
    * 모든 신호 경로에 있으며 모든 신호를 검사 할 수 있습니다. IMS 터미널은 다른 암호화되지 않은 신호를 무시해야합니다.
    * 가입자 인증을 제공하고 IMS 터미널과 IPsec 또는 TLS 보안 연결을 설정할 수 있습니다. 이를 통해 스푸핑 공격 및 재생 공격을 방지하고 가입자의 개인 정보를 보호합니다.
    * 신호를 검사하고 IMS 터미널이 오작동하지 않는지 확인합니다 (예 : 일반 신호 경로SigComp를 사용하여 SIP 메시지를 압축 및 압축 해제 할 수 있으므로 느린 무선 링크를 통한 왕복이 줄어 듭니다. 변경, 홈 네트워크의 라우팅 정책 위반).
    * SigComp를 사용하여 SIP 메시지를 압축 및 압축 해제 할 수 있으므로 느린 무선 링크를 통한 왕복이 줄어 듭니다.
    * 여기에는 미디어 플레인에 대한 서비스 품질 (QoS)과 같은 미디어 플레인 리소스를 승인하는 정책 결정 기능 (PDF)이 포함될 수 있습니다. 정책 제어, 대역폭 관리 등에 사용됩니다. PDF는 별도의 기능이 될 수도 있습니다.
    * 또한 청구 기록을 생성합니다.

* I-CSCF (Interrogating-CSCF)는 관리 도메인의 가장자리에있는 또 다른 SIP 기능입니다. 해당 IP 주소는 도메인의 DNS (Domain Name System)에 게시되어 (NAPTR 및 SRV 유형의 DNS 레코드 사용) 원격 서버에서 이를 찾아 이 도메인에 대한 SIP 패킷에 대한 전달 지점 (예 : 등록)으로 사용할 수 있습니다. 
    * HSS에 쿼리하여 S-CSCF의 주소를 검색하고 SIP 등록을 수행하는 사용자에게 할당합니다.
    * 또한 SIP 요청 또는 응답을 S-CSCF로 전달합니다.
    * 릴리스 6까지는 외부 세계 (SIP 메시지의 일부를 암호화)로부터 내부 네트워크를 숨기는 데 사용할 수도 있습니다. 이 경우이를 THIG (Topology Hiding Inter-Network Gateway)라고합니다. 릴리스 7부터는 이 "진입 점"기능이 I-CSCF에서 제거되었으며 이제 IBCF (Interconnection Border Control Function)의 일부입니다. IBCF는 외부 네트워크에 대한 게이트웨이로 사용되며 NAT 및 방화벽 기능 (핀 홀링)을 제공합니다. IBCF는 NNI (Network-to-Network Interface)에 특화된 세션 경계 컨트롤러입니다.

* Serving-CSCF (S-CSCF)는 신호 평면의 중심 노드입니다. SIP 서버이지만 세션 제어도 수행합니다. 항상 홈 네트워크에 있습니다. HSS에 대한 Diameter Cx 및 Dx 인터페이스를 사용하여 사용자 프로필을 다운로드하고 user-to-S-CSCF 연결을 업로드합니다 (사용자 프로필은 처리 이유로 로컬로만 캐시되며 변경되지 않음). 필요한 모든 가입자 프로필 정보는 HSS에서로드됩니다.
    * 사용자 위치 (예 : 터미널의 IP 주소)와 SIP 주소를 바인딩 할 수있는 SIP 등록을 처리합니다.
    * 로컬에 등록된 사용자의 모든 신호 메시지 경로에 있으며 모든 메시지를 검사 할 수 있습니다.
    * 서비스를 제공하기 위해 SIP 메시지를 전달할 애플리케이션 서버를 결정합니다.
    * 일반적으로 ENUM (Electronic Numbering) 조회를 사용하는 라우팅 서비스를 제공합니다.
    * 네트워크 운영자의 정책을 시행합니다.
    * 부하 분산 및 고 가용성을 위해 네트워크에 여러 S-CSCF가있을 수 있습니다. I-CSCF에서 쿼리 할 때 S-CSCF를 사용자에게 할당하는 것은 HSS입니다. 이를 위해 가입자와 S-CSCF간에 일치시킬 필수 / 선택 기능을 포함하여 여러 옵션이 있습니다.

## Application servers
참조 : 차세대 네트워크 서비스

SIP AS (Application Server)는 서비스를 호스팅하고 실행하며 SIP를 사용하여 S-CSCF와 인터페이스합니다. 3GPP에서 개발중인 애플리케이션 서버의 예로는 VCC 서버 (Voice call continuity Function)가 있습니다. 실제 서비스에 따라 AS는 SIP 프록시 모드, SIP UA (사용자 에이전트) 모드 또는 SIP B2BUA 모드에서 작동 할 수 있습니다. AS는 홈 네트워크 또는 외부 타사 네트워크에 있을 수 있습니다. 홈 네트워크에있는 경우 Diameter Sh 또는 Si 인터페이스 (SIP-AS 용)를 사용하여 HSS를 쿼리 할 수 있습니다.

* SIP AS : IMS 특정 서비스 호스팅 및 실행
* IP 멀티미디어 서비스 스위칭 기능 (IM-SSF) : SIP와 CAP를 인터페이스하여 CAMEL 애플리케이션 서버와 통신
* OSA 서비스 기능 서버 (OSA SCS) : SIP를 OSA 프레임 워크에 인터페이스합니다.

## Public Service Identity
PSI (Public Service Identities)는 응용 프로그램 서버에서 호스팅하는 서비스를 식별하는 ID입니다. 사용자 ID로서 PSI는 SIP 또는 Tel URI의 형태를 취합니다. PSI는 고유 한 PSI 또는 와일드 카드 PSI로 HSS에 저장됩니다:
* 고유 한 PSI에는 라우팅에 사용되는 PSI가 포함됩니다.
* 와일드 카드 PSI는 PSI 모음을 나타냅니다.

## Media servers
MRF (Media Resource Function)는 미디어 조작 (예 : 음성 스트림 믹싱) 및 톤 및 알림 재생과 같은 미디어 관련 기능을 제공합니다.

각 MRF는 미디어 리소스 기능 컨트롤러 (MRFC)와 미디어 리소스 기능 프로세서 (MRFP)로 더 나뉩니다.

* MRFC는 AS 및 S-CSCF에서 오는 정보를 해석하여 MRFP를 제어하는 신호 평면 노드입니다.
* MRFP는 미디어 스트림을 혼합, 소싱 또는 처리하는데 사용되는 미디어 플레인 노드입니다. 또한 공유 리소스에 대한 액세스 권한을 관리 할 수 있습니다.

미디어 리소스 브로커 (MRB)는 게시된 적절한 MRF 정보를 수집하고 AS와 같은 소비 엔티티에 적절한 MRF 정보를 제공하는 역할을하는 기능적 엔티티입니다. MRB는 두 가지 모드로 사용할 수 있습니다.
* 쿼리 모드 : AS는 MRB에 미디어를 쿼리하고 MRB의 응답을 사용하여 호출을 설정합니다.
* 인라인 모드 : AS는 SIP INVITE를 MRB로 보냅니다. MRB가 통화 설정합니다.

## Breakout gateway
BGCF (Breakout Gateway Control Function)는 S-CSCF가 DNS 또는 ENUM / DNS를 사용하여 세션을 라우팅 할 수 없다고 결정한 경우 S-CSCF의 라우팅 요청을 처리하는 SIP 프록시입니다. 전화 번호를 기반으로 한 라우팅 기능이 포함되어 있습니다.

## Reference
[WIKIPEDIA IP Multimedia Subsystem](https://en.wikipedia.org/wiki/IP_Multimedia_Subsystem)
