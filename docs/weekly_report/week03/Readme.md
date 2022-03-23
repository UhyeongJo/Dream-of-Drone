<h2>3주차 회의록</h2>
<h4>회의 일시 : 2022.03.17</h4>
<h4>참석자 : 조우형, 김준영, 박중후, 유예린</h4>
<h4>회의 주제 :  진행상황 및 물품구입 계획 </h4>

----------------------------------------------------------
<h3>회의 내용</h3>

- 팀원 코로나 확진으로 인해 지도교수님과의 면담시간 변경

- 임베디드 팀 물품구입 계획
  1. 쓰레기통 외부에 적외선 센서 부착 및 서브모터 : 사람이 다가오거나 손을 대면 자동으로 뚜껑이 열리게 한다.
  2. 무게 센서 및 초음파 센서 활용 : 무게 센서와 초음파센서를 활용해 쓰레기 무게와 쓰레기통이 채워진 정도를 파악한다.
  3. 디스플레이 활용 : 무게 센서와 초음파센서의 데이터를 조율해 디스플레이로 쓰레기통이 채워진 정도를 % 단위로 시현한다.
  - 라즈베리파이, 적외선거리센서:GP2Y, 초음파센서:HC-SR04, 5KG 무게센서:DM395, 쓰레기통 구입 계획.

- 통신팀 계획<br>
 드론에서 뿜어져 나오는 와이파이를 사용하여 쓰레기통에서 와이파이에 연결하여 데이터를 주고 받는 형식으로 결정.
-계획-
 1. 유심 통신 모듈 찾기
 2. 드론 자체 테더링 한 후 통신에 성공하며 드론과 쓰레기통 간의 데이터 주고받기(모듈은 향후에 배송이 되므로 드론과 지상 컴퓨터간 통신 교환 먼저 구현)
 3. 쓰레기통이 드론의 wifi에 자동으로 신호를 잡아서 연결.
  