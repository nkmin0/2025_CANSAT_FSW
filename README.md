# 2025_cansat
2025년 캔위성 경연대회 FSW

## 글라이더 캔위성 프로토타입 제작
### 하드웨어
- 상승타 제어를 통한 활강 제어
- IMU 센서 이용
- 캔위성 각도 양 -> 상승타 각도 음
- 캔위성 각도 양 -> 상승타 각도 양 -> 활강
- 좌우제어 X
### 소프트웨어
- 라즈베리파이 사용
- IMU, GPS 데이터 수집 (CSV 파일 제작 코드 필요)
- IMU 값에 따른 상승타 모터 제어 코드 필요