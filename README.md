<p align="start">
<img width="166" height="175" alt="Image" src="https://github.com/user-attachments/assets/ef3281b3-306a-47e4-9df2-58b9207efe7e" />
</p>

# 필가이
AI 기반 개인 약 복용 관리 및 증상별 맞춤형 추천 케어 애플리케이션 

## 프로젝트 소개 
복약 관리에 어려움을 겪는 사람들에게 OCR 기반 처방전 자동 등록, AI 증상 분석 및 약 추천, 복약 알림, 캘린더 기반 일정 관리, 공공데이터 연동 약품 정보 제공 등 체계적인 복약 관리 기능을 제공하는 AI 기반 맞춤형 건강관리 앱입니다.

## 프로젝트 상세 정보 
- 2025년 한성대학교 컴퓨터공학부 졸업 작품
- 프로젝트 기간: 2025.02.05 ~ 2025.06.08
- 팀: 전지원[앱 프런트 담당],김동휘,노경민,박진영

## 기술스택
| **Category** | **TechStack** |
-- | --
| Mobile Language   | Dart                                             |
| Mobile Framework  | Flutter                                          |
| UI Styling        | Flutter Widget                                   |
| State Management  | Flutter State Management (setState / Provider 등) |
| API Communication | REST API                                         |
| Backend           | Spring Boot                                      |
| Database          | MySQL                                            |
| OCR Service       | Naver Cloud OCR                                  |
| Public Data API   | 공공데이터포털 – e약은요                               |
| AI Service        | Gemini API                                       | 

## 역할 및 구현 내용

<details>
<summary><strong>UI 및 화면 설계/구현</strong></summary>

- 앱 전반적인 화면 디자인 및 Flutter UI 위젯 활용
- 사용자 경험 중심의 화면 배치 및 인터랙션 구성

</details>

<details>
<summary><strong>Backend 요청 설계 (CRUD)</strong></summary>

- DB 요청 정의에 따라 Spring Boot 기반 REST API 연동
- 데이터 생성(Create), 조회(Read), 수정(Update), 삭제(Delete) 기능 구현

</details>

<details>
<summary><strong>Provider 기반 캐싱 및 데이터 관리</strong></summary>

- 사용자가 설정한 데이터들을 캐싱하여, 등록된 약 정보는 매번 로딩 없이 즉시 화면에 표시
- 달력 기능, 알약 상세 조회, 메인 화면 오늘 복용 약 정보 등에서 캐싱을 활용해 기존 로딩 시간을 최소화
- 새로운 데이터가 들어올 때는 Provider를 통해 실시간 업데이트 가능하도록 구현

</details>

<details>
<summary><strong>공공데이터 API 연동</strong></summary>

- e-약은요 API 연동으로 의약품 상세 정보 제공
- 사용자 입력 기반 약품 검색 및 정보 조회 기능 구현

</details>


## 프로젝트 시연 
<div align="center">
    <video src="https://github.com/user-attachments/assets/863d6156-2196-469e-8b0e-fdaa1d33a6c8" width="200" height="200" controls>
  </video>
</div>

## 프로젝트 화면 구성 

| **로그인 화면** | **회원가입 화면** | **메인 화면** |
| :---: | :---: | :---: |
| <img width="1419" height="2796" alt="Image" src="https://github.com/user-attachments/assets/4fbbf61c-c1b1-4816-aa4e-524ac40e912f" /> |<img width="1419" height="2796" alt="Image" src="https://github.com/user-attachments/assets/c397f4e9-edf6-4c75-9a54-364476e2bb76" />  | <img width="1419" height="2796" alt="Image" src="https://github.com/user-attachments/assets/bda4463d-34ee-49a9-9c60-43c6c67ad1d4" /> |

| **달력 화면** | **추가 화면** | **추천 화면** |
| :---: | :---: | :---: |
| <img width="1419" height="2796" alt="Image" src="https://github.com/user-attachments/assets/8678f657-04f1-438b-a58f-eb35072bbe21" /> |<img width="1419" height="2796" alt="Image" src="https://github.com/user-attachments/assets/be1e45a1-598b-423f-a087-b79004e6014d" /> | <img width="1419" height="2796" alt="Image" src="https://github.com/user-attachments/assets/90ee488f-7a39-4146-9434-7afbbf2c6ab2" /> |

## 느낀점
이번 프로젝트를 통해 팀워크의 중요성을 깊이 체감했습니다.주차별 역할 분담과 문제 공유를 통해 협업의 효율성을 경험할 수 있었습니다.
아이디어부터 결과까지 앱이 완성되는 과정을 직접 경험하며 개발에 대한 책임감과 실무 감각을 얻었습니다.







