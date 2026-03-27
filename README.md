# 🥤 싱싱한 녀석들
> **프랜차이즈·편의점 신메뉴를 한곳에서 탐색하고, 리뷰·위치·알림까지 확인할 수 있는 통합 플랫폼**

[![React Native](https://img.shields.io/badge/React%20Native-20232A?logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://react.dev/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white)](https://www.oracle.com/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white)](https://expo.dev/)

---

## 📅 프로젝트 개요
- **프로젝트명**: 싱싱한 녀석들
- **한 줄 소개**: 프랜차이즈와 편의점의 신메뉴 정보를 모아, 검색·비교·리뷰·위치 확인까지 지원하는 서비스
- **주요 타겟**
  - 편의점 및 프랜차이즈 신제품에 관심이 많은 사용자
  - 트렌드에 민감한 MZ세대 소비층
- **개발 배경**
  - 신제품 정보가 브랜드별로 흩어져 있어 사용자가 직접 여러 앱과 사이트를 오가며 찾아야 하는 불편함이 존재
  - 출시 소식, 가격, 영양 정보, 판매 지점, 리뷰를 한 번에 볼 수 있는 통합 서비스가 부족
- **핵심 목표**
  - 프랜차이즈·편의점 신제품 정보를 한 곳에 통합
  - 출시 정보, 가격, 영양 정보, 리뷰, 판매 위치까지 원스톱 제공
  - 사용자가 원하는 신메뉴를 빠르고 편하게 탐색할 수 있도록 지원

---

## 👥 팀 구성 및 역할

### 조하람
- 제품 상세 정보 제공 및 정보 통합
- 신제품 알림 서비스
- 사용자 맞춤 필터링 시스템
- 위치 기반 서비스

### 강구용
- POS 관련 기능
- 마이페이지
- 리뷰 및 평가 기능
- 영수증 인증 OCR

### 조혜령
- 신메뉴 출시 캘린더
- 위치 기반 서비스
- 메인 페이지

---

## 🛠 기술 스택

### Frontend
- **React Native**: 모바일 앱 UI 및 기능 구현
- **React**: POS 웹 구현

### Backend
- **Spring Boot**: API 처리 및 서버 구성
- **JPA**: CRUD 처리 및 Entity 매핑
- **MyBatis**: 복잡한 SQL 분리 및 관리

### Database & Infrastructure
- **Oracle**: 데이터 저장소
- **AWS EC2**: 서버 및 DB 운영 환경

### External API / Service
- **Firebase Authentication**: 로그인/회원가입 인증 처리
- **Naver Clova OCR**: 영수증 인증 OCR 처리
- **Naver Blog / YouTube API**: 외부 리뷰 정보 제공
- **Expo Push Notification**: 브랜드 신메뉴 푸시 알림 발송

---

## 🏗 시스템 아키텍처

- **Client**
  - React Native 기반 모바일 앱
  - React 기반 POS 웹

- **Server**
  - Spring Boot 서버에서 비즈니스 로직 처리
  - Oracle DB와 연동하여 메뉴, 리뷰, 구독, 위치 정보 저장 및 조회

- **Authentication**
  - Firebase를 통한 사용자 인증 처리

- **External Integration**
  - Clova OCR: 영수증 인증
  - Naver / YouTube: 리뷰 및 콘텐츠 정보 수집
  - Expo Push Notification: 브랜드 구독 알림 발송

### 기능 흐름도
![기능흐름도](https://github.com/user-attachments/assets/ae47a41f-a18a-4d37-a495-8d8940e4156e)

### 시스템 아키텍처
![시스템아키텍처](https://github.com/user-attachments/assets/e8f3bc9a-3a34-4340-92e4-7648b37d72e3)

### 포스기 웹
![포스기웹](https://github.com/user-attachments/assets/36d688c3-91c5-42ba-a756-863de265063c)

### 소통 방식
![소통방식](https://github.com/user-attachments/assets/92bf4ab5-16aa-4eee-942a-e88c2644a651)

### 서비스 로고
![싱싱한녀석들](https://github.com/user-attachments/assets/677789e3-09ce-4fe0-9ed4-df1c29b19bac)

---

## ✨ 주요 기능

### 1. 신메뉴 통합 탐색
- 프랜차이즈와 편의점의 신제품 정보를 한곳에서 확인 가능
- 브랜드별로 흩어진 정보를 메뉴 중심으로 통합 제공
- 검색과 카테고리 기반 탐색 지원

### 2. 사용자 맞춤 필터링
- 브랜드, 가격, 인기순, 최신순 등 다양한 조건으로 필터링 가능
- 사용자가 원하는 조건에 맞춰 빠르게 메뉴 탐색 가능

### 3. 제품 상세 정보 제공
- 메뉴명, 가격, 설명, 이미지 등 기본 정보 제공
- 상세 화면에서 제품에 대한 핵심 정보를 직관적으로 확인 가능

### 4. 외부 리뷰 콘텐츠 제공
- 네이버 블로그, 유튜브 리뷰 정보를 함께 제공
- 실제 사용자 후기와 영상 콘텐츠를 통해 제품 이해도 향상

### 5. 위치 기반 서비스
- 현재 위치를 기준으로 판매 매장 위치를 지도에 표시
- 사용자가 가까운 매장을 쉽게 찾을 수 있도록 지원

### 6. 브랜드 구독 및 알림
- 관심 브랜드를 구독하면 신메뉴 출시 시 푸시 알림 제공
- 사용자의 재방문을 유도하고, 브랜드 소식을 빠르게 전달

### 7. 리뷰 및 평가 기능
- 사용자가 직접 리뷰 작성 가능
- 리뷰와 평점을 기반으로 메뉴에 대한 반응 확인 가능

### 8. 영수증 인증 OCR
- Naver Clova OCR을 활용해 영수증 인증 기능 제공
- 실제 구매 여부를 기반으로 신뢰도 높은 리뷰 환경 조성

### 9. 신메뉴 출시 캘린더
- 출시 예정 및 출시된 신메뉴를 캘린더 형식으로 제공
- 일정 기반 탐색이 가능해 사용자 편의성 향상
  
---

## 🔄 서비스 흐름

1. 사용자는 메인 화면에서 신메뉴 목록, 캘린더, 검색 기능을 통해 원하는 메뉴를 탐색한다.
2. 검색 결과 화면에서 브랜드, 가격, 인기순 등 다양한 조건으로 필터링한다.
3. 특정 메뉴를 선택하면 상세 페이지로 이동한다.
4. 상세 페이지에서는 메뉴 정보, 리뷰, 외부 콘텐츠, 가까운 판매 매장 위치를 함께 확인할 수 있다.
5. 사용자는 브랜드를 구독하거나 찜 기능을 활용해 관심 있는 메뉴를 저장할 수 있다.
6. 이후 브랜드에서 신메뉴가 등록되면 푸시 알림을 받을 수 있다.

---

## 🤝 협업 방식

- 기능별 역할을 분담하여 각자 담당 영역을 책임감 있게 구현
- 프론트엔드, 백엔드, 외부 API 연동 기능을 구분하여 개발
- 팀원 간 회의를 통해 기능 연결 흐름과 데이터 구조를 지속적으로 조율
- 사용자 경험 중심으로 화면 흐름과 기능 우선순위를 함께 정리하며 개발 진행

---

## 📌 기대 효과

### 사용자 측면
- 흩어져 있는 신메뉴 정보를 한곳에서 빠르게 확인 가능
- 리뷰, 위치, 상세 정보를 함께 확인해 구매 결정에 도움
- 브랜드 구독을 통해 관심 있는 신제품 소식을 놓치지 않음

### 서비스 측면
- 브랜드 신제품 노출 강화
- 사용자 관심도 및 리뷰 데이터 축적 가능
- 향후 추천 시스템 및 마케팅 데이터로 확장 가능

---

## 🚀 향후 확장 방향
- 더 많은 프랜차이즈 및 편의점 브랜드 추가
- 개인 맞춤 추천 기능 고도화
- 위치 기반 추천 정확도 향상
- 리뷰 신뢰도 검증 기능 강화
- POS 연동 기능 확장

---

## 🙌 프로젝트를 통해 얻은 점
이 프로젝트를 통해 단순한 정보 조회 서비스를 넘어,  
**검색 → 필터링 → 상세 조회 → 리뷰 확인 → 위치 탐색 → 구독 알림**까지 이어지는  
사용자 중심 서비스 흐름을 설계하고 구현하는 경험을 쌓음

또한 React Native, Spring Boot, Oracle, Firebase, 외부 API, OCR, 푸시 알림을 연동하며  
실제 서비스에 가까운 구조를 직접 설계하고 구현해볼 수 있었음
