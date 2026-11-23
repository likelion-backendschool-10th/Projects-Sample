# 프로젝트 SR (Software Requirement) 
> SR(Software Requirement) 이란 프로젝트에서의 요구되는 것들이 무엇인지를 구체화 및 문서화하는 것을 의미한다.
>프로젝트에서 구현해야 할 기능에 대해 구성원 전체가 논의하고 기획한 내용을 SR에 작성하도록 한다.
> 제공한 문서 양식과 및 아래의 READ.MD를 꼭 참고하여 SR을 작성한다.
---
<br>

##  README.md 작성 항목 안내

아래 목차를 참고하여 프로젝트의 전반적인 내용을 작성한다.
각 항목은 프로젝트의 목적과 진행 과정, 개발 결과를 명확하게 전달할 수 있도록 구체적으로 작성한다.

| 번호 | 목차 | 작성 내용 |
|---|---|---|
| 1 | 프로젝트 개요 | 프로젝트명, 개발 기간, 프로젝트 목적 및 추진 배경 |
| 2 | 팀 소개 | 팀명, 팀원 정보, GitHub 계정, 담당 역할 및 주요 담당 기능 |
| 3 | 배포 링크 | 실제 배포된 서비스에 접속할 수 있는 URL |
| 4 | 프로젝트 발표 영상 & 발표 문서 | 프로젝트 발표 영상 및 발표 자료 링크 |
| 5 | 서비스 소개 | 서비스의 주요 기능, 핵심 사용자, 서비스 특징 및 기대 효과 |
| 6 | WBS | 프로젝트 일정, 단계별 작업 계획 및 담당자 |
| 7 | ERD | 데이터베이스 구조 및 테이블 간 관계 |
| 8 | 시스템 아키텍처 | 시스템 구성도, 서비스 간 통신 구조 및 인프라 구성 |
| 9 | Skills | 프로젝트 개발에 사용한 언어, 프레임워크, 라이브러리 및 개발 도구 |
| 10 | 오류 해결 및 기술 이슈 관리 | 개발 과정에서 발생한 오류, 원인 분석, 해결 방법 및 기술적 논의 기록 |
| 11 | 프로젝트 규칙 | Git 브랜치 전략, Commit Convention, 코드 작성 규칙 및 협업 규칙 |
| 12 | **중요!!** 데일리 업무 문서 | 일자별 진행 상황, 개인별 작업 내역 및 회의 기록 |
| 13 | **중요!!** 프로젝트 기획 및 개발 설계 문서 | 요구사항 정의서(SR), 기능 명세서, 화면 설계서, API 명세서 등 |

###  작성 시 유의사항

- 모든 항목은 프로젝트 진행 상황에 맞게 구체적으로 작성한다.
- 이미지, 다이어그램, 표 등을 활용하여 내용을 직관적으로 전달한다.
- WBS, ERD, 시스템 아키텍처 등은 이미지 또는 외부 문서 링크를 활용할 수 있다.
- 오류 및 기술적 이슈는 README에 상세하게 작성하기보다 GitHub Issues를 활용하여 기록하고, README에는 해당 이슈의 링크를 정리한다.
- 발표 자료, 기획 문서 등 외부 자료를 활용하는 경우 팀원 및 강사가 접근할 수 있는 링크를 제공한다.
- 프로젝트 종료 시 모든 항목을 최종 결과물 기준으로 업데이트한다.

> **README.md는 프로젝트를 처음 접하는 사람이 서비스의 목적, 팀 구성, 기술 스택, 시스템 구조 및 개발 과정을 한눈에 파악할 수 있도록 작성하는 프로젝트 소개 및 기술 문서이다.**


---
<br>
<br>
<br>
<br>


# Project-Sample 


## 1. 프로젝트 개요
> ### 개발 기간 
> **YYYY-MM-DD - YYYY-MM-DD**
<br>

> ### 프로젝트 명 
> **네이버 Naver**

<br>

> ### 프로젝트  소개 
>
>더 이상 정보 검색은 단순히 검색어를 입력하는 것에서 끝나지 않습니다❌
>
>궁금한 정보를 찾고 싶은 사람, 최신 소식을 빠르게 확인하고 싶은 사람, 다양한 분야의 지식과 콘텐츠를 탐색하고 싶은 사람까지.
>
>`네이버 포털 프로젝트`는 검색을 중심으로 뉴스, 블로그, 카페, 지식iN 등 다양한 서비스를 하나로 연결하여 사용자에게 필요한 정보를 제공합니다.
>
> 누구나 쉽고 편리하게 정보를 검색하고, 다양한 콘텐츠를 발견하며, 세상과 소통할 수 있는 공간. 
>
> 일상의 모든 궁금증을 연결하는 서비스, `네이버 포털 프로젝트`에 오신 걸 환영합니다!
<br>

> ### 프로젝트 배경
>
> 포털 서비스는 단순한 정보 검색을 넘어 콘텐츠 공유, 사용자 간 소통, 구독 및 결제 등 다양한 서비스를 제공하는 플랫폼으로 발전하고 있습니다.
>
> 본 프로젝트는 회원 관리, 게시글 및 댓글, 구독, 결제, 알림 기능을 갖춘 통합 웹 포털 서비스를 구현하고자 합니다.
>
> 이를 통해 실제 웹 서비스의 개발부터 클라우드 배포 및 운영까지 전체 개발 과정을 경험하고자 합니다.
<br>

> ### 프로젝트 목표
> 
> 사용자에게 편리한 서비스를 제공하고, 안정적인 웹 서비스 운영 환경을 구축하는 것이 목표입니다.
>
> 1. **화면 및 워크플로우 설계**
>   - 메인 피드, 게시글, 회원, 구독 및 결제, 알림 화면 설계
>
> 2. **데이터베이스 설계**
>   - JPA 기반 회원, 게시글, 댓글, 구독, 결제 Entity 설계
>
> 3. **백엔드 개발**
>  - Spring Boot 기반 회원 관리 및 게시글, 댓글, 구독, 결제 REST API 구현
>
> 4. **프론트엔드 개발**
>   - React, Svelte, Thymeleaf 중 하나를 활용한 UI 구현 및 API 연동
>
> 5. **클라우드 배포 및 운영**
>   - AWS EC2, Docker, GitHub Actions를 활용한 CI/CD 구축
>   - 포트 스위칭 방식의 무중단 배포 및 CloudWatch 모니터링 구현

<br>

> 기획부터 개발, 배포, 운영까지 웹 서비스의 전체 생명주기를 경험하는 것을 최종 목표로 합니다.

---
<br>


##  2. 팀 소개

### TEAM Naver

| DAVID | SOPHIE | ZOE | IVAR | JADEN | AMINA |
|:---:|:---:|:---:|:---:|:---:|:---:|
| <a href="https://github.com/"><img src="https://avatars.githubusercontent.com/u/93540726?v=4" width="100px"/><br/>@GithubID</a> | <a href="https://github.com/"><img src="https://avatars.githubusercontent.com/u/93540726?v=4" width="100px"/><br/>@GithubID</a> | <a href="https://github.com/"><img src="https://avatars.githubusercontent.com/u/93540726?v=4" width="100px"/><br/>@GithubID</a> | <a href="https://github.com/"><img src="https://avatars.githubusercontent.com/u/111436967?v=4" width="100px"/><br/>@GithubID</a> | <a href="https://github.com/"><img src="https://avatars.githubusercontent.com/u/85716720?v=4" width="100px"/><br/>@GithubID</a> | <a href="https://github.com/"><img src="https://avatars.githubusercontent.com/u/90237119?v=4" width="100px"/><br/>@GithubID</a> |
| **담당 역할** | **담당 역할** | **담당 역할** | **담당 역할** | **담당 역할** | **담당 역할** |
| Frontend | Backend | Backend | AI | Frontend | DevOps |
| **주요 담당 기능** | **주요 담당 기능** | **주요 담당 기능** | **주요 담당 기능** | **주요 담당 기능** | **주요 담당 기능** |
| 로그인 UI<br/>회원가입 화면 | 회원가입 API<br/>사용자 인증 | 게시글 CRUD<br/>댓글 기능 | AI 모델 연동<br/>추천 시스템 | 메인 페이지<br/>검색 UI | 배포 환경 구축<br/>CI/CD |

---
<br>



> ## 3. 배포 링크
> 
> ### [배포 링크- 네이버](https://www.naver.com/)


---
<br>



> ## 4. 프로젝트 발표 영상 & 발표 문서
>
> ### [ 발표 영상 ](https://m.naver.com/shorts/?seedMediaId=8673FE6E09FC9AEA1D59EA67BC5F286A201F&serviceType=NTV)
> ### [ 발표 문서 ](https://deview-serving.pstatic.net/v1/files?objectPath=data/deview/session/attach/%E1%84%82%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%87%E1%85%A5%E1%84%91%E1%85%A6%E1%84%8B%E1%85%B5%20%E1%84%80%E1%85%A7%E1%86%AF%E1%84%8C%E1%85%A6%20%E1%84%89%E1%85%A5%E1%84%87%E1%85%B5%E1%84%89%E1%85%B3%20%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8C%E1%85%A1%E1%86%BC%E1%84%80%E1%85%AA%20%E1%84%87%E1%85%A7%E1%86%AB%E1%84%92%E1%85%AA_%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%92%E1%85%A1%E1%86%AB.pdf)
---
<br>





## 5. 서비스 소개
|   메인 화면 1  |  메인 화면 2  |   소셜 로그인 1   |
|:--------:|:------:|:--------:|
| <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" /> |   <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" />  | <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" /> |

|   가능 1  |  기능 2  |   기능 3   |
|:--------:|:------:|:--------:|
| <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" /> |   <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" />  | <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" /> |

|   가능 4  |  기능 5  |   기능 6   |
|:--------:|:------:|:--------:|
| <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" /> |   <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" />  | <img width="400" height="187" alt="녹음 2026-11-23 144446" src="https://github.com/user-attachments/assets/9d5a7f66-15f7-442f-bcf4-b8b7e3ec01b2" /> |

---
<br>
<br>
<br>

## 6. WBS 

| 단계 | 작업 항목 | 세부 작업 내용 | 담당자 | 시작일 | 종료일 | 
|---|---|---|---|---|---|
| 1. 기획 | 요구사항 분석 | 포털 서비스 기능 정의 및 요구사항 명세 | - | - | - | 
|  | 화면 설계 | 메인, 검색, 뉴스, 블로그, 카페 화면 설계 | - | - | - | 
|  | 회원 화면 설계 | 회원가입, 로그인, 마이페이지 화면 설계 | - | - | - | 
|  | 워크플로우 | 검색, 콘텐츠 작성, 댓글 및 사용자 활동 흐름 설계 | - | - | - | 
| 2. DB 설계 | 회원 Entity | 회원 정보, 프로필 및 권한 정보 설계 | - | - | - | 
|  | 게시글 Entity | 게시글 제목, 내용, 작성자 및 공개 범위 설계 | - | - | - | 
|  | 댓글 Entity | 댓글 내용, 작성자 및 게시글 관계 설계 | - | - | - | 
|  | 구독 Entity | 사용자 간 구독 관계 및 구독 상태 설계 | - | - | - | 
|  | 결제 Entity | 결제 수단, 금액, 일자 및 결제 상태 설계 | - | - | - | 
| 3. 백엔드 개발 | 회원 관리 | 회원가입, 로그인, 마이페이지 API 구현 | - | - | - | 
|  | 검색 기능 | 키워드 검색 및 카테고리별 검색 API 구현 | - | - | - | 
|  | 뉴스 서비스 | 뉴스 목록 및 상세 조회 API 구현 | - | - | - | 
|  | 블로그 서비스 | 게시글 CRUD API 구현 | - | - | - | 
|  | 카페 서비스 | 카페 게시글 및 댓글 CRUD API 구현 | - | - | - | 
|  | 구독 관리 | 사용자 구독 신청, 취소 및 조회 API 구현 | - | - | - | 
|  | 결제 관리 | 결제 요청, 승인 및 결제 내역 API 구현 | - | - | - | 
| 4. 프론트엔드 개발 | 메인 화면 | 네이버 스타일 메인 페이지 및 검색창 구현 | - | - | - |
|  | 검색 화면 | 검색 결과 및 카테고리별 필터링 화면 구현 | - | - | - | 
|  | 뉴스 화면 | 뉴스 목록 및 상세 페이지 구현 | - | - | - | 
|  | 블로그 화면 | 블로그 목록, 상세 및 게시글 작성 화면 구현 | - | - | - | 
|  | 카페 화면 | 카페 게시글 목록 및 상세 화면 구현 | - | - | - | 
|  | 회원 화면 | 회원가입, 로그인 및 마이페이지 구현 | - | - | - | 
|  | API 연동 | Axios 또는 Fetch를 활용한 서버 API 연동 | - | - | - | 
| 5. 서비스 기능 구현 | 콘텐츠 관리 | 게시글 작성, 수정, 삭제 및 조회 기능 구현 | - | - | - | 
|  | 검색 관리 | 통합 검색 및 검색 결과 필터링 기능 구현 | - | - | - | 
|  | 사용자 소통 | 댓글 작성 및 사용자 간 구독 기능 구현 | - | - | - | 
|  | 결제 기능 | 유료 서비스 결제 및 이용 권한 관리 구현 | - | - | - | 
|  | 알림 기능 | 댓글, 구독 및 서비스 알림 기능 구현 | - | - | - | 예정 |
| 6. 배포 및 운영 | 컨테이너 환경 | Docker 및 Docker Compose 환경 구축 | - | - | - | 
|  | CI/CD | GitHub Actions 기반 빌드 및 배포 자동화 | - | - | - | 예정 |
|  | 무중단 배포 | NGINX 기반 포트 스위칭 방식 구현 | - | - | - | 예정 |
|  | 모니터링 | CloudWatch 또는 Prometheus/Grafana 기반 모니터링 및 로깅 | - | - | - | 
| 7. 테스트 및 완료 | 기능 테스트 | 회원, 검색, 게시글, 댓글, 구독 및 결제 테스트 | - | - | - |
|  | 통합 테스트 | 프론트엔드와 백엔드 API 연동 테스트 | - | - | - | 
|  | 배포 테스트 | AWS 배포 및 무중단 배포 정상 동작 확인 | - | - | - | 
|  | 최종 점검 | 오류 수정 및 프로젝트 결과물 정리 | - | - | - | 

---
<br>
<br>
<br>


## 7. ERD 
<img width="626" height="385" alt="image" src="https://github.com/user-attachments/assets/2a12ba4a-29cd-4f4c-a5f5-3120182eb0da" />

---
<br>


## 8. 시스템 아키텍쳐 

<img src="https://user-images.githubusercontent.com/90237119/215304129-d8006105-cf1c-49c7-a819-4f819dfac523.png"/>

---
<br>



## 9. Skills

### Engineering

| Category | Technology | Version |
|---|---|---|
| Language | <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"> |  |
| Frontend | <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"> |  |
| Frontend | <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"> |  |
| Backend | <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"> |  |
| ORM | <img src="https://img.shields.io/badge/Spring_Data_JPA-59666C?style=flat-square"> |  |
| Database | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"> |  |
| API | <img src="https://img.shields.io/badge/Axios-671DDF?style=flat-square&logo=axios&logoColor=white"> <img src="https://img.shields.io/badge/Fetch_API-333333?style=flat-square"> |  |

<br>

### Third Party

| Category | Technology | Version |
|---|---|---|
| Payment | PG 결제 API |  |
| Monitoring | <img src="https://img.shields.io/badge/AWS_CloudWatch-FF4F8B?style=flat-square&logo=amazonaws&logoColor=white"> |  |
| Monitoring | <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"> |  |

<br>

### Infrastructure & DevOps

| Category | Technology | Version |
|---|---|---|
| Container | <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"> |  |
| Container | <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white"> |  |
| Web Server | <img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white"> |  |
| CI/CD | <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"> |  |
| Cloud | <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"> |  |

<br>

### Cooperation

| Category | Technology | Version |
|---|---|---|
| Version Control | <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"> |  |
| Repository | <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"> |  |
| API Testing | <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white"> |  |
| Design | <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"> |  |
| Documentation | <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"> |  |
| Communication | <img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white"> |  |

---
<br>



## 10. 오류 해결 및 기술 이슈 관리

프로젝트 개발 과정에서 발생하는 오류, 해결이 어려운 문제, 기능 개선 사항 및 기술적 질문을 GitHub Issues를 통해 관리한다. <br>
대표 트러블슈팅 2~3건 요약해서 꼭 넣어준다. 


| Issue Type | Issue | content | Issue Link |
|---|---|---|---|
|  **Bug** | Docker ImagePullBackError | Docker 이미지 Pull 실패 및 이미지 다운로드 오류 | [Issue](https://github.com/likelion-backendschool-10th/Projects-Sample/issues/5) | 
| **Help** | React - Backend API 연동 문제 | CORS 오류 및 API 연동 문제 해결 요청 | [Issue](https://github.com/likelion-backendschool-10th/Projects-Sample/issues/2) |
|  **Enhancement** | 게시글 검색 기능 개선 | 검색 필터 및 정렬 기능 추가 요청 | [Issue](https://github.com/likelion-backendschool-10th/Projects-Sample/issues/3) |
|  **Bug** | 로그인 API 500 Internal Server Error | 로그인 요청 시 서버 오류 발생 및 원인 분석 | [Issue](https://github.com/likelion-backendschool-10th/Projects-Sample/issues/1) |


<br>

### Issue 관리 규칙
- 오류가 발생하면 Bug Report를 작성한다.
- 혼자 해결하기 어려운 문제는 Help를 통해 도움을 요청한다.
- 기존 기능의 개선이 필요한 경우 Enhancement를 등록한다.
- 기술적인 개념이나 구현 방법에 대한 질문은 Question으로 등록한다.
- 문제 해결 과정과 최종 결과는 해당 Issue에 업데이트한다.
- 관련 Pull Request가 있다면 Issue와 연결한다.

<br>

### 회고 및 개선 사항

- 반복적으로 발생한 오류 및 주요 원인
- 오류 해결 과정에서 새롭게 학습한 내용
- 향후 동일한 오류를 방지하기 위한 개선 사항
  
---
<br>
<br>



##  11. 프로젝트 규칙

### Branch Strategy
> - main / dev 브랜치 기본 생성 
> - main과 dev로 직접 push 제한
> - PR 전 최소 1인 이상 승인 필수

### Git Convention
> 1. 적절한 커밋 접두사 작성
> 2. 커밋 메시지 내용 작성
> 3. 내용 뒤에 이슈 (#이슈 번호)와 같이 작성하여 이슈 연결

> | 접두사        | 설명                           |
> | ------------- | ------------------------------ |
> | Feat :     | 새로운 기능 구현               |
> | Add :      | 에셋 파일 추가                 |
> | Fix :      | 버그 수정                      |
> | Docs :     | 문서 추가 및 수정              |
> | Style :    | 스타일링 작업                  |
> | Refactor : | 코드 리팩토링 (동작 변경 없음) |
> | Test :     | 테스트                         |
> | Deploy :   | 배포                           |
> | Conf :     | 빌드, 환경 설정                |
> | Chore :    | 기타 작업                      |


### Pull Request
> ### Title
> * 제목은 '[Feat] 홈 페이지 구현'과 같이 작성한다.

> ### PR Type
  > - [ ] FEAT: 새로운 기능 구현
  > - [ ] ADD : 에셋 파일 추가
  > - [ ] FIX: 버그 수정
  > - [ ] DOCS: 문서 추가 및 수정
  > - [ ] STYLE: 포맷팅 변경
  > - [ ] REFACTOR: 코드 리팩토링
  > - [ ] TEST: 테스트 관련
  > - [ ] DEPLOY: 배포 관련
  > - [ ] CONF: 빌드, 환경 설정
  > - [ ] CHORE: 기타 작업

> ### Description
> * 구체적인 작업 내용을 작성한다.
> * 이미지를 별도로 첨부하면 더 이해하기 좋다.


### Code Convention
>BE
> - 패키지명 전체 소문자
> - 클래스명, 인터페이스명 CamelCase
> - 클래스 이름 명사 사용
> - 상수명 SNAKE_CASE
> - Controller, Service, Dto, Repository, mapper 앞에 접미사로 통일(ex. MemberController)
> - service 계층 메서드명 create, update, find, delete로 CRUD 통일(ex. createMember) 
> - Test 클래스는 접미사로 Test 사용(ex. memberFindTest)


> FE
> - styled-Component 변수명 S + 변수명 (ex. Swrap)
> - styled-Component는 return문 위에 작성
> - 크게는 styled-Component, 그 안에서 className 사용 
> - Event handler 사용 (ex. handle ~)
> - export방식 (ex. export default ~)
> - 화살표 함수 사용

### Communication Rules
> - CampFire 활용 
> - 정기 회의
---
<br>


##  12. 데일리 업무 문서

프로젝트 진행 상황과 팀 내 논의 내용을 데일리로 기록하는 문서이다.

| 문서 | 링크 |
|---|---|
| 일일 보고서 | [ 양식 링크](https://docs.google.com/document/d/1VADG9PE1jOEa0h00hW_9CdQzrC2PMZ7N/edit) |
| 주간 보고서 | [ 양식 링크](https://docs.google.com/document/d/19p8oT2qFZUMvNyZ-Jyqs5UeX2_km47wu/edit) |
| 회의록 | [ 양식 링크](https://docs.google.com/document/d/1fJ-izDT6L1TEm5kn3i4rGu1lMUdJLHX3/edit) |

---
<br>
<br>


##  13. 프로젝트 기획 및 개발 설계 문서

프로젝트 기획부터 설계, 구현 및 테스트까지 필요한 **최종 필수 산출물** 이다.

### 1. 기획 및 요구사항 정의

| 문서 | 링크 |
|---|---|
| 프로젝트 기획서 | [양식 링크](https://docs.google.com/document/d/1CD_qHa5xQszhi_MgjN330SVCA-EEyPDy/edit) |
| 요구사항 정의서 | [ 양식 링크](https://docs.google.com/document/d/1Iv43n-3osKQnb3YoMwAmue-7zBrUhj7s/edit) |
| Use Case 명세서 | [ 양식 링크](https://docs.google.com/document/d/1mVU8aft3CnAgROAMgWKsysT92R6TkZe3/edit) |
| 기능 정의서 | [ 양식 링크](https://docs.google.com/document/d/1sHWWTHl9ep9ThZqNtU9Li5582ynYw-HY/edit) |
| 업무분해도(WBS) | [ 양식 링크](https://docs.google.com/spreadsheets/d/18_BDexTKzuOpBxhwHW-rmOQkJc_7GfZ8/edit?gid=1334287492#gid=1334287492) |

### 2. 서비스 및 시스템 설계

| 문서 | 링크 |
|---|---|
| 화면 설계서 | [ 양식 링크](https://docs.google.com/document/d/1fyY1KNKqNEnF9fo9juQuMgQvobdEkE9J/edit?usp=drive_web&ouid=114449420159385852563&rtpof=true) |
| 서비스 흐름도 | [ 양식 링크](https://docs.google.com/document/d/1Zj_Jf7csMcP4LHGTah7pX5EcVLfU2mkC/edit) |
| 시스템 아키텍처 | [ 양식 링크](https://docs.google.com/document/d/1LY1Jge9iMfI5wRtpww4i37idEHc4cw1b/edit) |
| 코딩 컨벤션 | [ 양식 링크](https://docs.google.com/document/d/16m2MI8gdaUgN9Rasa9IW7UVzxqJwdSIA/edit) |

### 3. 데이터베이스 설계

| 문서 | 링크 |
|---|---|
| 데이터 명세서 | [ 양식 링크](https://docs.google.com/document/d/1mUDy6IHqjiLcEQd6FRR5M7VoQ-AMdCXR/edit) |
| ERD | [ 양식 링크](https://docs.google.com/document/d/1FsBtXXKNfxjT4sIInFWjoBROxlmiXi4f/edit) |
| 테이블 정의서 | [ 양식 링크](https://docs.google.com/document/d/1K_E1hNhgSLj-ReNuVOXT1Fa_0IrK-Lbc/edit) |

### 4. 테스트 및 검증

| 문서 | 링크 |
|---|---|
| 단위 테스트 | [ 양식 링크](https://docs.google.com/document/d/10PRDe8hVF9TYDZHCC_9wUgVaSRMR2j6R/edit) |
| 시나리오 테스트 | [ 양식 링크](https://docs.google.com/document/d/1QebMizjnnXhN2LBkyC-TZRP0at6MophH/edit) |

