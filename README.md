![header](https://capsule-render.vercel.app/api?type=venom&height=200&color=gradient&text=JiksGit&section=header&fontColor=000000&animation=fadeIn)

# 👋 안녕하세요~! 새로운 문제를 배우고 해결하며 성장하는 개발자 **양현직**입니다.

가천대학교 컴퓨터공학과를 졸업하고 Java 기반 웹 기술을 중심으로  
실무형 프로젝트와 교육을 통해 백엔드 개발 역량을 쌓았습니다.  

Spring Boot와 Spring Framework를 중심으로  
**트랜잭션 처리로 데이터 무결성을 보장하고**
**Redis 기반 채팅 서비스와 MSA 아키텍처**를 경험했습니다.  

> “기술로 사람을 연결하고 안정적인 시스템으로 신뢰를 만든다.”  
> 이것이 제가 지향하는 개발자의 방향입니다.

---

## About Me

최근에는 **K-pop 실시간 라이브 커머스 플랫폼 ‘Universe’** 프로젝트를 진행하며  
Spring Boot 기반 **Gateway, Eureka, Chat, Core 서비스**를 분리하여 **MSA 아키텍처**를 도입했습니다.  
또한 **Redis 기반 실시간 채팅 시스템**과 **JWT 인증 구조**를 구현해 보안성과 확장성을 동시에 확보했습니다.

---

## Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-FF6C37?style=flat-square)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)

> Java 기반 백엔드 서버 및 인증 구조(Spring Security + JWT) 설계  
> ORM(JPA)과 Mapper(MyBatis) 병행 사용 경험

---

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

> React·Vue 기반 SPA 및 JSP 기반 SSR 프로젝트 경험  
> UI 프레임워크 활용 및 데이터 바인딩 구조 설계

---

### Database & Cache
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

> 관계형 DB 설계 및 Redis 기반 캐싱·실시간 데이터 처리 구현

---

### Infra & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Naver Cloud](https://img.shields.io/badge/Naver_Cloud-03C75A?style=flat-square&logo=naver&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

> 클라우드 환경에서 CI/CD 파이프라인 구성 및 무중단 배포 경험  
> Nginx 리버스 프록시 및 로드밸런싱 설정 실습

---

### Tools & Collaboration
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![SourceTree](https://img.shields.io/badge/SourceTree-0052CC?style=flat-square&logo=sourcetree&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

> Git 브랜치 전략 기반 협업 및 Pull Request 리뷰 프로세스 운영  
> Swagger, Notion, Figma를 통한 설계 문서화 및 협업 관리

---

## Projects

### 🎬 Universe – K-POP 라이브 커머스 플랫폼
> 실시간 채팅으로 소통하며 상품을 구매할 수 있는 K-pop 라이브 커머스 플랫폼

- **Spring Cloud Gateway + Eureka** 기반 MSA 유사 구조 설계  
- 상품 등록·수정 시 `@Transactional`로 데이터 일관성 보장  
- WebSocket + STOMP 기반 실시간 채팅 / Redis 캐싱 및 욕설 필터링  
- JWT 기반 사용자 인증 및 블랙리스트 관리  
- 팀장으로서 **WBS 기반 일정 관리**, **GitHub 코드 리뷰** 주도  

**성과:** 서비스 안정성 확보, 코드 품질 개선, 협업 프로세스 효율화

---

### 🎨 HotSource – 디지털 콘텐츠 공유 플랫폼
> 개발자와 디자이너를 위한 이미지·BGM 자산 공유 플랫폼

- Spring Security + OAuth2.0(Google, Naver, Kakao) 로그인 연동  
- BCrypt + Salt 기반 비밀번호 암호화로 보안 강화  
- MyBatis association/collection 매핑으로 N+1 쿼리 개선  
- FileManager 유틸 클래스 생성으로 파일 업로드 구조 표준화  
- `@Transactional` 기반 데이터 무결성 확보  

**성과:** 보안 강화, 쿼리 최적화, 유지보수성 향상

---

### 🍅 Tomato Disease Classification – AI 기반 이미지 질병 판별 서비스
> AI 모델(DenseNet)을 활용해 토마토 잎의 질병을 자동 분류하는 웹 서비스

- DenseNet 전이학습 모델 학습 및 Spring Boot 연동  
- JWT 인증 구조로 세션 부하 문제 해결  
- Docker 컨테이너 기반 AWS EC2·RDS 배포  
- AI 예측 결과를 REST API로 서비스화  

**성과:** AI 모델 실서비스 연동 및 클라우드 자동 배포 경험

---

## Certificates
- 정보처리기사  
- SQLD (SQL 개발자)  
- 네트워크 관리사 2급  

---

## Stats

<p align="center">
  <a href="https://solved.ac/didguswlr">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=didguswlr" height="150">
  </a>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=JiksGit&theme=github_dark" height="150">
</p>

---

## Contact
- **Email:** yanghyunjik99@gmail.com  
- **Portfolio:** [Notion Portfolio](https://chatter-glider-3f4.notion.site/292b5b4ec16181578fc5dc7a69780ad3)
- **GitHub:** [github.com/JiksGit](https://github.com/JiksGit)
