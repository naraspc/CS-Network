# CS-Network

<details>
  <summary>OSI 7 Layer</summary>
    <div markdown="1">
    <ul>
<details>
  <summary>물리 계층</summary>
  <div markdown="1">
    <ul>
      <li>0과 1로 이루어짐</li>
      <li>Hub를 통해 BroadCasting 방식으로 소통함(단뱡향)</li>
      <li>물리적 주소가 존재하지않음</li>
    </ul>
  </div>
</details>

<details>
  <summary>데이터링크 계층</summary>
  <div markdown="1">
    <ul>
      <li>MAC주소를 통해 원하는 대상에 직접 연결</li>
      <li>Switch를 통해 MAC주소로 양뱡향 소통함</li>
    </ul>
  </div>
</details>

<details>
  <summary>네트워크 계층</summary>
  <div markdown="1">
    <ul>
      <li>목적지까지의 최단거리를 계산함</li>
      <li>ARP를 사용하여 MAC주소에 IP주소를 매핑함</li>
      <li>Route를 사용하여 네트워크와 연결됨</li>
    </ul>
  </div>
</details>

<details>
  <summary>전송 계층</summary>
  <div markdown="1">
    <ul>
      <li>통신의 규약을 정의함 (TCP,UDP등이 있음)</li>
      <li>흐름제어를 수행</li>
      <li>데이터 전송을 담당함</li>
    </ul>
  </div>
</details>

<details>
  <summary>세션 계층</summary>
  <div markdown="1">
    <ul>
      <li>장치 간 상호작용 및 동기화</li>
      <li>데이터 전달과정에서 에러 발생 시 복구담당</li>
    </ul>
  </div>
</details>

<details>
  <summary>표현 계층</summary>
  <div markdown="1">
    <ul>
      <li>데이터의 타입을 정의(MPEG, JPG등)</li>
      <li>데이터의 암&복호화 담당</li>
    </ul>
  </div>
</details>

<details>
  <summary>응용 계층</summary>
  <div markdown="1">
    <ul>
      <li>사용자와의 상호작용 담당</li>
      <li>DNS, HTTP(S), SSH 등의 프로토콜이 대표적</li>
    </ul>
  </div>
</details>

### 응용계층이 최상위, 물리계층이 최 하위계층으로 상위 계층에서 하위계층으로 정보 전달 시 데이터 앞에 각각 레이어의 헤더를 달아 캡슐화함

 </ul>
  </div>
</details>
