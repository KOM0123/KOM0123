## 권오민 (KOM)

ROS 2로 로봇을 움직이는 코드를 짜고 있습니다.
교육과정에서 TurtleBot3와 LIMO PRO 실물 로봇, Unity 디지털 트윈을 팀으로 만들었고, 다음은 매니퓰레이터 프로젝트를 준비하고 있습니다.

### 프로젝트

| 프로젝트 | 무엇을 만들었나 | 내가 맡은 일 |
|---|---|---|
| [TurtleBot3_com_ws](https://github.com/KOM0123/TurtleBot3_com_ws)<br>2인 · 2026.08 | 실내 방문자 안내 로봇. 목적지까지 Nav2로 안내하고, 끝나면 ArUco 마커를 보고 충전 스테이션에 도킹 | SLAM 매핑, ArUco 인식·도킹 오차 계산, 사람 감지, 센서 브리지(Arduino, 후방 초음파) |
| [LIMO_Patrol](https://github.com/KOM0123/LIMO_Patrol)<br>4인 · 2026.09 | 웨이포인트를 순찰하며 바닥의 위험 물체를 찾는 LIMO PRO 순찰 로봇 | YOLO 탐지 노드. 모델 학습·비교, Jetson TensorRT 배포, 순간 오탐을 막는 3프레임 확인 필터 |
| [DT_Index](https://github.com/KOM0123/DT_Index)<br>4인 · 2026.10–11 | 로봇팔 3대·컨베이어·AGV가 있는 분류 라인의 Unity–ROS 2 디지털 트윈 | 로봇팔1 투입, 컨베이어·레인, 무게 센서·분기 게이트, 상태 패널 (Unity) |

### 써본 것

- **로봇**: ROS 2 Humble, Nav2, SLAM, OpenCV(ArUco)
- **비전**: YOLOv8, TensorRT, NCNN
- **시뮬레이션**: Unity, Gazebo
- **하드웨어**: TurtleBot3 Burger, LIMO PRO(Jetson), Raspberry Pi 4, Arduino
- **언어**: Python, C#
