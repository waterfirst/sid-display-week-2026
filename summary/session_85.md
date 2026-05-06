# 세션 85 : AR/VR Computing & Algorithms

## 85-3. Lens-Based CGEI Algorithm with GPU Acceleration for Integral Imaging Light-Field Displays System
1. **제목**: Lens-Based CGEI Algorithm with GPU Acceleration for Integral Imaging Light-Field Displays System
2. **논문 발표자**: Shao-Yu Hung
3. **소속 회사**: National Taiwan University
4. **주요 논문 내용**: 
   - 차량용 AR 디스플레이를 위한 저지연 요소 이미지(Elemental Image) 생성 알고리즘.
   - GPU 가속(CUDA kernels)과 렌즈 기반 LUT 프레임워크를 사용하여 계산량을 획기적으로 줄임.
   - 0.032초의 생성 시간으로 동적 장면의 실시간 렌더링이 가능함을 입증.
5. **삼성디스플레이 시사점**: 
   - **위협도: 중간**. 고해상도 라이트필드 디스플레이 구동을 위한 소프트웨어 인프라 기술임. SDC가 패널뿐만 아니라 이를 구동하기 위한 저지연 알고리즘 생태계에도 관심을 가져야 함.

## 85-4. Accelerated CGH Generation for AR Head-Up Display Based on DeepCGH and Yolo
1. **제목**: Accelerated CGH Generation for AR Head-Up Display Based on DeepCGH and Yolo
2. **논문 발표자**: Pin-Yin Huang
3. **소속 회사**: National Taiwan University
4. **주요 논문 내용**: 
   - YOLO 기반 차량 감지와 DeepCGH 모델을 결합한 가속 컴퓨터 생성 홀로그램(CGH) 프레임워크.
   - 단안 깊이 추정(Monocular depth estimation)을 사용하여 객체와의 거리에 따른 깊이 인지 홀로그램 생성.
   - 주행 영상의 프레임별 실시간 처리 및 깊이 인식 홀로그래픽 시각화 실현.
5. **삼성디스플레이 시사점**: 
   - **위협도: 낮음**. AI 기술을 활용한 홀로그램 생성 가속화 기술로, 향후 SDC의 홀로그래픽 디스플레이 모듈이 탑재될 때 시각적 품질과 속도를 높이는 데 필요한 핵심 알고리즘임.
