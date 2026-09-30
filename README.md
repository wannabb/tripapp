 # PBL1 - 실시간 환율 기반 해외 여행 장부앱

## 1. 프로젝트 개요
 - 주제: 실시간 환율 기반 해외 여행 장부앱 - 앱 이름 미정.
 - 기획 의도 및 해결하려는 문제: 해외 여행시 스마트한 예산 관리 가능
 - 타겟 사용자: 해외 여행을 가는 모든 사람들이 잠재적 유저층

## 2. 기술 스택 (Tech Stack)
 - `Flutter + FireBase`로 진행할 예정. 
 - 각자 Flutter와 FireBase 활용한 실습을 통한 개인 공부 필요.

## 2. 역할 분담 (Role Assignment)
 

## 4. 협업 방식 및 일정 관리
 - 코드 협업: `GitHub`
 - 소통 채널: `KakaoTalk / Discord` (정기 미팅: 주 1회 정도 빈도로 디스코드로 진행할 예정)

## 5. 개발 요구사항 (Core Features)
 - [필수] MVP (최소 기능 제품) 요구사항:
   1) **로그인 기능이 필요할지 결정해야함.** 확실한건 신용카드 결제 기록 API 연동할려면 로그인 기능 반드시 필요함. 
   2) 메인 페이지에서 새로운 여행 계획을 추가하고 삭제하고 수정하고 관리 가능. 리스트를 클릭하여 여행 장부 페이지로 이동 가능(입력값: 예산-원화로 입력, 기간, 여행 이름)
   3) 환율 API와 연동하여 (USD, JPY, EUR, CNY, VND, THB, PHP, TWD등 주로 가는 여행지의 화폐 단위 기준) 원화로 환산하여 남은 예산 표기. - 환율 API 트래픽량의 절감을 위해 환율 API 최근 호출 시간을 기록해두어 앱을 실행한 날짜와 다르다면 환율 API를 호출하는 방식으로 하면 비용 절감이 가능함
   4) 여행 장부 페이지로 이동하면 새로운 소비기록을 추가할 수 있음. 기록을 할 때 유저로부터 입력 받을 값은 (카테고리, 사용처, 사용금액)이고 날짜는 시스템의 날짜를 그대로 가져         와서 기록할 것. 
   5) 여행 장부 페이지에 기록되는 항목은 소비한 기록이며, 한 위젯 내에서 왼쪽 편에는 (카테고리별 대표 아이콘 이미지, 사용처, 현지 화폐기준 사용금액, 날짜)가 오른쪽 편에는           (원화로 환산한 금액)이 표시됨.
   6) 장부 기록들은 기본적으로 최근 결제한 것이 위로 가도록 정렬함.
  
  
 - [선택] 추가 구현 요구사항 (시간 남을 시):
   1) 현재 계획에서는 장부내 기록은 모두 수동임. 그러나 교수님이 조언하신대로 카드 결제 기록 API를 활용하여, 카드 결제건에 대한 것은 자동으로 기록되도록 하는 것도 괜찮을 거 같    음.
   2) ...














# tripapp

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
