# 👋 Hi there, I'm **Yang Hyunjik (양현직)**  

🎯 **Back-end Developer | Java & Spring Boot 중심의 서비스 아키텍처 설계자**  
가천대학교 컴퓨터공학과 졸업  
확장성과 안정성을 갖춘 서버 개발을 목표로, 단순한 기능 구현을 넘어  
**서비스 구조와 운영 효율성까지 고려한 백엔드 설계**에 집중하고 있습니다.

---

## 🧠 About Me

최근에는 **K-pop 실시간 라이브 커머스 플랫폼 ‘Universe’** 프로젝트에서  
Spring Boot 기반의 **Gateway, Eureka, Chat, Core 서비스**를 분리해 **MSA 아키텍처**를 도입했습니다.  
또한 **Redis 기반 실시간 채팅 시스템**과 **JWT 인증 구조**를 설계하여  
서비스의 실시간성·보안성을 강화했습니다.  

> 변화하는 환경 속에서도 “**더 효율적인 시스템은 어떻게 만들어질까**”를 고민하며  
> 안정적이고 성능 좋은 서비스를 만들어가는 개발자가 되고자 합니다.

---

## 🛠 Tech Stack

**Languages**  
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frameworks & Libraries**  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Databases & Infra**  
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)

---

## 💼 Projects

### 🎤 **Project 1: K-pop 실시간 라이브 커머스 플랫폼 (Universe)**  
K-pop 관련 굿즈와 앨범을 실시간으로 판매할 수 있는 **라이브 커머스 플랫폼**을 개발했습니다.  
팀장으로서 **아키텍처 설계 및 팀원 역할 분담**을 담당하였으며,  
다수의 사용자가 동시에 접속하는 환경을 고려해 **Spring Boot 기반 Gateway·Eureka 구조로 MSA 구현**을 진행했습니다.  

- 상품 관리 기능에 **페이지네이션** 적용  
- JPA **Fetch Join**으로 **N+1 문제 해결 및 조회 성능 향상**  
- **WebSocket + STOMP 프로토콜**로 실시간 채팅 구축  
- **Redis 기반 욕설·도배 필터링 (Aho-Corasick + Rate Limiting)** 적용  
- **스트리밍 파일 저장 오류 수정**을 통해 안정성 확보  

**→** JPA 최적화, Redis 활용, MSA 설계, 코드 리뷰 기반 협업의 중요성을 배움  

---

### 🖼 **Project 2: 디지털 콘텐츠(이미지, BGM) 공유 플랫폼**  
개발자와 디자이너가 프로젝트 제작에 필요한 **이미지나 BGM을 공유**할 수 있는 플랫폼을 개발했습니다.  
팀장으로서 프로젝트 전반을 관리하며, **Spring Framework + MyBatis 환경**에서  
상품 등록·수정·삭제 시 **트랜잭션 처리**를 적용하여 데이터 무결성을 확보했습니다.  

- **Spring Security + OAuth2.0**으로 Google, Naver, Kakao 로그인 연동  
- 페이지별 접근 권한 부여로 **보안 강화**  
- **쿼리 최적화** 및 **다중 테이블 매핑**으로 조회 성능 개선  
- **JSP + Tomcat 기반 SSR 구조 구현**, **Servlet 요청 처리 흐름** 심층 이해  

**→** 트랜잭션 처리, 보안 설계, 데이터 조회 최적화, SSR 및 서버 실행 환경 이해 능력 향상  

---

### 🍅 **Project 3: 토마토 잎 질병 판별 웹서비스**  
AI 모델을 활용해 **토마토 잎의 질병을 자동 분류**하고 정보를 제공하는 웹서비스를 개발했습니다.  
Kaggle 데이터를 활용하여 **DenseNet 모델을 전이학습**, AI 모델을 실서비스와 연동했습니다.  

- 회원 관리, 게시판, 댓글 기능 구현  
- **JWT 인증 구조**로 세션 부하 문제 해결  
- **Docker 기반 서버 격리 및 AWS EC2·RDS 배포 자동화**  
- AI 모델과 웹서비스의 통합 구조 설계  

**→** AI 모델 실서비스 연동, 인증 구조 설계, 클라우드 배포 자동화 역량 강화  

---

## 📚 학습 및 스터디

- **인프런 김영한 – “스프링 완전 정복” 시리즈 스터디 중**  
  → 스프링 핵심 개념 및 고급 기술 실무 적용 학습  
- **알고리즘 학습 (백준 / 프로그래머스)**  
  → 문제 해결력 및 코드 효율성 향상

---

## 🪪 Certificates
- 정보처리기사  
- 네트워크 관리사 2급  
- SQLD (SQL 개발자)

---

## 📈 GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=JiksGit&layout=compact&theme=tokyonight)
![JiksGit's GitHub stats](https://github-readme-stats.vercel.app/api?username=JiksGit&show_icons=true&theme=tokyonight)
![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=JiksGit&theme=react-dark)

---

## 🌐 Contact
📧 **Email:** yanghyunjik99@gmail.com  
🗂 **Portfolio (Notion):** [[https://yanghyunjik.notion.site](#)](https://chatter-glider-3f4.notion.site/292b5b4ec16181578fc5dc7a69780ad3)
