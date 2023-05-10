NDN에 대한 개념 정리
====================
Lastest Update : 2023.05.02.
-------------------
1. NDN의 개념
- NDN(Named Data Networking)은 현재 인터넷 아키텍처에 대해 제안된 대체 접근 방식으로 위치 대신 데이터 이름을 지정한다는 아이디어를 기반으로 생성된 프로토콜 개념이다.
- 현재 인터넷에서 장치 간 통신은 네트워크의 특정 위치에 해당하는 특정 IP 주소로 패킷을 보내는 것을 기반으로 한다.
  + 반대로 NDN은 콘텐츠 이름을 통신의 기본 구성 요소로 사용한다.
    + 콘텐츠 이름을 기본 구성 요소로 사용하면 좋은 점
      + 콘텐츠 이름은 사람이 읽을 수 있고 표현력이 있어 위치가 아닌 콘텐츠를 기반으로 데이터를 식별하고 액세스하기 좋다.   
        즉, 사용자는 콘텐츠가 저장된 특정 위치를 알 필요 없이 이름으로 콘텐츠를 요청할 수 있습니다.


NDN에서 데이터는 여러 구성 요소로 구성된 계층적 식별자인 콘텐츠 이름을 기반으로 저장 및 검색됩니다. 각 구성 요소는 데이터 생성자, 데이터 유형 또는 데이터 버전과 같은 데이터의 특정 속성에 해당합니다. 콘텐츠 이름의 계층 구조는 데이터 액세스의 안전한 인증 및 권한 부여뿐만 아니라 데이터의 효율적인 라우팅 및 캐싱을 허용합니다.


NDN은 확장성, 보안 및 개인 정보 보호와 같은 현재 인터넷의 일부 문제를 해결할 수 있는 잠재력을 가지고 있습니다. 그것은 미래 인터넷을 위한 후보 아키텍처로 제안되었으며, 그 설계 및 구현을 탐색하기 위한 지속적인 연구 노력이 있습니다.