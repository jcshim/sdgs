# Physical AI(물리적 AI)
* 화면 속 디지털 데이터를 넘어 **현실 세계의 물리 법칙을 이해하고, 센서로 환경을 인식해 직접 움직이며 행동하는 AI**
* 
* **핵심 원리:** 인지(센서) $\rightarrow$ 판단(AI 모델) $\rightarrow$ 행동(로봇·기계 제어)
* **대표 분야:** 휴머노이드 로봇, 자율주행차, 스마트 팩토리 물류 로봇, 드론 등

[마이크로덕](https://youtu.be/reiTh7K4KSc?si=Fq24MGDiavf5Dwbe)

### AI 학습용 외장 GPU가 아닌, 소형 보드용 내장 그래픽 칩셋
* 내장칩(SoC): 록칩(Rockchip) RK3566
* GPU: Arm Mali-G52 (내장)
* AI 가속기: NPU (약 0.8 TOPS)
※ 시뮬레이션 강화학습은 로봇 자체가 아닌 별도 PC의 NVIDIA GPU(RTX 등)에서 수행한 뒤, 
※학습된 제어 정책(Policy)만 로봇으로 전송해 실행하는 구조
