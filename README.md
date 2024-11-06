➨ Jetson Nano에서 카메라 영상 실시간 전송 및 변환
- Jetson Nano를 이용하여 카메라 영상을 실시간으로 수신하고, 해당 영상을 세 가지 형태(원본, 그레이스케일, 이진화)로 전송하는 시스템 구현
- 각각의 영상은 특정 포트를 통해 네트워크로 전송되며, OpenCV와 GStreamer를 사용하여 Jetson Nano의 영상을 처리

  • 개발 환경 : Jetson Nano
  • 라이브러리 OpenCV (GStreamer 지원 포함)
  • 네트워크 송출 포드:
          원본 영상: 포트 8001
          그레이스케일 영상: 포트 8002
          이진화 영상: 포트 8003

  ➨ https://github.com/smHan22/jetson-camera/blob/main/Makefile
