# 세션 109 : Display Systems & Interactive Technology

## 109-1. Multi-device Linkage Technology for Eye-controlled Content Continuation Display
1. **제목**: Multi-device Linkage Technology for Eye-controlled Content Continuation Display
2. **논문 발표자**: Xiufeng Wang
3. **소속 회사**: BOE Technology Group Co., Ltd
4. **주요 논문 내용**: 
   - 여러 기기의 카메라를 활용하여 사용자의 시선을 인식하고 추적하는 기술을 제안함.
   - 사용자의 얼굴 방향과 시선 방향을 기반으로 현재 응시하고 있는 기기를 식별하여, 별도의 수동 조작 없이 해당 화면으로 콘텐츠를 직접 전송(연속 표시)함.
   - 거리에 따라 3가지 기술(YOLOv8, dlib, MediaPipe)을 단계적으로 결합하여 최적의 성능(60+ FPS)을 확보함.
5. **삼성디스플레이 시사점**: 
   - **위협도: 중간**. BOE가 디스플레이 하드웨어를 넘어 다중 기기 환경에서의 사용자 경험(UX) 및 인터랙션 기술력을 과시함. 스마트홈, 회의 시스템 등 다양한 응용 분야에서 경쟁력을 확보하려는 시도로 보임.

## 109-2. Thinking Differently About Video Processing at the Edge with AI in Systems Including Professional Displays
1. **제목**: Thinking Differently About Video Processing at the Edge with AI in Systems Including Professional Displays
2. **논문 발표자**: Ben Cope
3. **소속 회사**: Intel Corporation
4. **주요 논문 내용**: 
   - 비디오 압축 및 스케일링(Super Resolution) 등 전통적인 비디오 처리 작업에 AI를 적용하는 방안을 탐구함.
   - GPU용으로 설계된 초해상도(SR) 구현이 모바일 프로세서의 NPU나 통합 GPU에서도 효율적으로 실행될 수 있음을 보여줌.
   - 540p 영상을 700 kbps로 전송한 후 AI SR을 적용하면, 1000 kbps로 전송한 1080p 영상과 유사한 객체 검출 정확도(mAP)를 회복하여 대역폭을 30% 절감할 수 있음을 입증함.
5. **삼성디스플레이 시사점**: 
   - **위협도: 중간**. Intel 등 칩셋 업체들이 NPU 기반의 화질 개선 및 대역폭 절감 기술을 적극적으로 개발하고 있음. 이는 고해상도(8K 등) 디스플레이에서 저해상도 콘텐츠를 효과적으로 표시할 수 있게 하여, 디스플레이 자체의 스펙 경쟁 외에 시스템 레벨의 최적화가 중요해짐을 시사함.

## 109-3. Ultra-Low Interactive Latency with Frameless Render-Display Integration
1. **제목**: Ultra-Low Interactive Latency with Frameless Render-Display Integration
2. **논문 발표자**: Evan Jonson
3. **소속 회사**: North Carolina State Univ. (경희대, 세종대 공동 연구)
4. **주요 논문 내용**: 
   - 프레임 버퍼, 동기화(VSYNC 등) 및 순차적 디스플레이 업데이트를 제거하여 "클릭 투 포톤(click-to-photon)" 지연을 최소화하는 프레임리스(Frameless) 통합 렌더링-디스플레이 아키텍처를 제안함.
   - 레이 트레이싱(이미지 순서 렌더링)을 활용하여 픽셀이 렌더링되는 즉시 디스플레이로 전송함.
   - 프로토타입(Raspberry Pi Pico 2 및 LED 매트릭스 활용)을 통해 상호작용 지연을 2ms 미만으로 줄임(기존 시스템은 32.7ms).
5. **삼성디스플레이 시사점**: 
   - **위협도: 중간**. 게이밍 및 VR/AR 등 지연 시간에 극도로 민감한 디스플레이 시장에서 매우 중요한 연구임. 기존의 프레임 기반 구동 방식에서 벗어난 새로운 디스플레이 구동 패러다임을 제시하고 있어, 향후 고성능 디스플레이 드라이버 IC(DDI) 및 패널 설계에 영향을 줄 수 있음.
