---
title: "안심길: 안심 귀가 서비스"
date: 2024-06-10
categories: [Project, Capstone]
tags: [App, Safe-Way-Home-Service, Software-Development, Development]
permalink: /projects/capstone-design/
summary: "안심길은 사용자에게 안전한 귀가를 지원하는 모바일 앱으로, 2024년 캡스톤 디자인 대회에서 우수작품상 1등을 수상한 프로젝트입니다."
---

<!-- # 안심귀가 서비스: 당신의 안전한 귀가 동반자 -->

> ### 수상 내역  
- **2024 캡스톤 디자인 대회 우수작품상 1등**

---

## 프로젝트 소개
안심귀가 서비스는 밤늦게 귀가하는 사용자를 위한 애플리케이션으로, **실시간 위치 추적, 안전 경로 안내, 비상 알림 기능**을 통합하여 범죄 예방 및 안전한 귀가 경로 제공합니다. 이 서비스는 사용자가 안심하고 귀가할 수 있도록 지원합니다.

<img src="/images/capstone/main.png" alt="안심길 메인 화면면" style="width: 400px;">


---

## 주요 기능

### 1. 실시간 위치 추적으로 안전 확보
1. **위치 공유 시작**: 사용자는 귀가를 시작할 때 앱을 실행하고 GPS 기반 위치 공유를 활성화합니다.
2. **실시간 모니터링**: 가족이나 친구가 사용자의 이동 경로를 실시간으로 확인할 수 있습니다.
3. **안전한 귀가 확인**: 지오펜싱(Geofencing) 기술로 경로 이탈 여부를 감지하고, 목적지 도착 시 위치 공유가 종료됩니다.

<!-- ![GPS 실시간 추적 예시](/images/capstone/gps_tracking.png) -->
<img src="/images/capstone/gps_tracking.png" alt="GPS 실시간 추적 예시" style="width: 200px;">


---

### 2. 스마트한 안전 경로 안내
- **경로 최적화**: 최단 거리 경로를 제공합니다.
- **안전 경로 제안**: 위험 지역을 회피하고 CCTV 및 비상벨이 많은 안전한 경로를 안내합니다.

<img src="/images/capstone/safe_route.png" alt="안전 경로 안내" style="width: 200px;">

<!-- ![안전 경로 안내](images/safe_route.png) -->

---

### 3. 신속한 비상 알림 및 SOS
- **위험 감지**: 사용자의 흔들림을 분석하여 잠재적 위험을 감지합니다.
- **SOS 활성화**: 한 번의 터치로 비상 신호를 전송하고, GPS 정보를 기반으로 긴급 연락처 및 경찰에 알림을 보냅니다.

<img src="/images/capstone/sos_alert.png" alt="비상 상황 SOS 화면" style="width: 200px;">
<!-- ![비상 상황 SOS 화면](images/sos_alert.png) -->

---

## 개발 환경
- **개발 도구**: Android Studio, Spring Boot  
- **개발 언어**: Kotlin, Java, Python  
- **사용한 API 및 데이터**: Google Maps API, 위치 기반 서비스 API, 공공 안전 데이터  

---

## 범죄율 감소 효과 분석
- **범죄율 변화 분석**:  
  - CCTV와 비상벨 설치 후 전체 범죄율 평균 18% 감소  
  - 재산범죄(강도, 절도)는 평균 25% 감소  
  - 대인범죄(폭행 등)는 비상벨 설치 후 평균 20% 감소  

<img src="/images/capstone/crime_rate_analysis.png" alt="범죄율 감소 분석 그래프" style="width: 500px;">
<!-- ![범죄율 감소 분석 그래프](images/crime_rate_analysis.png) -->

  
---

## UI 및 사용자 경험 (UX) 설계

### 1. 로그인 화면
- 중앙에 배치된 직관적인 로그인 버튼으로 사용자 접근성을 극대화했습니다.

### 2. 친구 목록 관리
- 사용자가 친구를 추가하거나 삭제할 수 있으며, 긴급 시 친구와 위치를 공유할 수 있습니다.

<img src="/images/capstone/friends_list.png" alt="친구 목록 UI" style="width: 500px;">
<!-- ![친구 목록 UI](images/friends_list.png) -->

### 3. 안심벨 및 CCTV 위치 제공
- 주변의 **안심벨**과 **CCTV 위치**를 실시간으로 확인하여 안전한 경로 선택이 가능합니다.

<img src="/images/capstone/safety_points.png" alt="안심벨 및 CCTV 위치" style="width: 100px;">
<!-- ![안심벨 및 CCTV 위치](images/safety_points.png) -->

---

## 향후 업데이트 계획
1. **이상 움직임 감지 및 자동 알림 기능**: 사용자의 흔들림 데이터를 분석해 낙상이나 비정상적인 움직임이 감지될 경우, 등록된 지인에게 실시간 위치 정보와 함께 즉시 영상 통화를 연결해 상황을 신속하게 파악할 수 있도록 지원하는 기능

---

## 결론
안심귀가 서비스는 사용자의 귀가 안전을 보장하는 스마트 보안 솔루션으로, 실시간 경로 추적과 안전 정보 제공을 통해 범죄를 예방하고 안전한 커뮤니티 형성에 기여합니다.

---
