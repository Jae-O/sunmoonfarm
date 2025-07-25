# 📦 SM AUCTION – 모바일 중고 경매 플랫폼

> **“교내 중고 거래부터 경매까지 접근성이 다르다”**

---

## 📘 프로젝트 개요

- **팀명**: 5팀
- **개발 플랫폼**: React Native (모바일 앱)
- **서버 및 DB**: Firebase (Authentication, Firestore, Realtime DB)
- **주요 도구**: Discord(협업), Expo Snack, GitHub

### 🧩 개발 배경

- **코로나19 이후 중고거래 수요 증가**
- **단순 직거래 → 경매 시스템으로 확장**
- **거래 신뢰성 보장과 사용자 편의성 확보**

---

## 🛠 맡은 역할 (주재오)

| 담당 영역 | 세부 내용 |
|-----------|-----------|
| **중고거래 기능 구현** | 게시글 조회, 등록, 수정, 삭제, 거래 상태 변경 |
| **Firebase 연동** | 실시간 데이터베이스 설계 및 연동 |
| **데이터 구조 설계** | 사용자, 상품, 채팅, 거래 이력 등 데이터 모델링 |
| **카테고리 / 검색 기능 구현** | 키워드 및 카테고리별 필터링 로직 작성 |


---

## ✨ 핵심 기능 소개

### 홈 & 내비게이션 구성

- 탭 내비게이션 / 스택 내비게이션 혼합 사용
- 인트로, 로그인, 회원가입, 홈 등 기본 구성 완료

🔁 중고거래 기능 (담당)
<div align="center"> <img src="https://github.com/user-attachments/assets/3fffe613-c418-451c-ab21-423e5dd501bd" width="200" /> <img src="https://github.com/user-attachments/assets/3c27086e-f30f-4b5d-9276-873e3bac5f8e" width="200" /> </div> <p align="center"><i>상품 목록 및 상세 페이지 / 거래 상태 및 채팅 연동</i></p>
글 등록, 수정, 삭제, 판매완료 처리

Firebase Firestore 기반 상품 데이터 저장

실시간 거래 상태 변경 반영

📂 카테고리 & 검색 (담당)
<div align="center"> <img src="https://github.com/user-attachments/assets/52fff6d0-467b-4ec7-bf2c-0cfa9004ee51" width="200" /> <img src="https://github.com/user-attachments/assets/cfdf05d9-fd59-4acd-9246-5ba35031b3ca" width="200" /> <img src="https://github.com/user-attachments/assets/8c3d6541-3cdc-4e05-8fd2-c68f25465316" width="200" /> </div> <p align="center"><i>카테고리별 필터 / 키워드 검색 / 정렬 기능</i></p>
키워드 기반 검색 구현

카테고리 선택 필터로 사용자 편의성 확보

데이터 정렬 / 필터링 UI 구현

🔨 경매 기능
<div align="center"> <img src="https://github.com/user-attachments/assets/4231386a-f8e2-4718-b0d6-19ba9145e36c" width="200" /> </div> <p align="center"><i>경매 등록 / 참여 / 낙찰 처리</i></p>
자동 송금 연동 구조 설계 (향후 Toss API 연동 고려)

경매 종료 시 최종 입찰자에게 자동 낙찰

💬 실시간 채팅 & 송금
<div align="center"> <img src="https://github.com/user-attachments/assets/58cb4300-9e28-433b-8277-7a09cadd27bb" width="200" /> <img src="https://github.com/user-attachments/assets/0507a890-3894-4ff4-911c-558568bc447b" width="300" /> </div> <p align="center"><i>실시간 채팅 / 자동 송금 처리 UI</i></p>
1:1 채팅방 구성 (김준태 담당)

거래 중 채팅으로 협의 가능

👤 사용자 정보
<div align="center"> <img src="https://github.com/user-attachments/assets/2be007fc-ef65-4d24-9033-557956c57b34" width="200" /> <img src="https://github.com/user-attachments/assets/3a09a31b-ca7d-4a20-bcaf-c4ed5a130809" width="200" /> </div> <p align="center"><i>내 정보 및 상대방 프로필 확인 / 신고 기능</i></p>

---

## 🔍 기술 스택

| 기술 | 사용 용도 |
|------|-----------|
| **React Native** | 모바일 앱 UI/UX 구현 |
| **Firebase Auth** | 사용자 로그인/가입 처리 |
| **Firebase Firestore** | 상품, 사용자, 채팅 데이터 저장 |
| **Firebase Realtime DB** | 실시간 채팅 및 경매 상태 변경 |
| **Expo** | 앱 실행 및 테스트 |
| **Discord** | 협업 커뮤니케이션 도구 |

---

## 🚀 향후 개선 방향

- **서버/클라이언트 완전 분리**
  - Firebase 외 자체 Node.js 백엔드로 전환 고려
- **Toss Payments API 연동**
  - 거래 신뢰도 향상 위한 자동 결제 시스템 도입
- **앱 외부 알림 기능**
  - 푸시 알림으로 사용자 응답성 향상

---

## 📮 팀 정보

- **주재오** – 중고거래 기능, DB 설계 및 구현  
- **김준태** – UI/UX, 채팅  
- **최성혁** – 경매 로직, UI 병합  

---

## 🙏 감사합니다

> **“중고거래의 새로운 패러다임, 실시간 경매와 안정된 데이터 연동으로 구현했습니다.”**
