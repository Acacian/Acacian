# :octocat:  **Welcome to Acacian's Github!**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>


---

<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"/> <img src="https://img.shields.io/badge/JPA-6DB33F?style=flat-square&logo=hibernate&logoColor=white"/>

---

<img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white"/> <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white"/>

## 💁🏻‍♂️ Brief
- 안녕하세요, 구동하입니다. Hello, I am Dongha Koo.
- Served in the Air Force for several years. Now Working as a Backend Developer,
- continuously improving through real-world projects and hands-on experience.
- Mainly using Python, with Kotlin and Java as sub languages.
- Comfortable with configuring and managing CI/CD pipelines in both GitHub and GitLab environments.

## 💼 Experience
- 🛠️ **Koosstech** – Backend & DevOps Engineer (End-to-End Ownership)
- 🧠 **MementoAI** – Backend Engineer Intern with project manager
- 🎖️ **Republic of Korea Air Force** – Air defense weapons control/T

## 🌱 Open Source Contributions
- 🧩 Spring AI : 기여 내용: VectorStoreBuilderCustomizer, @ToolParam 바인딩 개선, DeepSeek 응답 처리 보정 등 주요 PR 작성

## 📫 Contact
- 📧 Email: [koo9811@naver.com](mailto:koo9811@naver.com)
- 💼 LinkedIn: [linkedin.com/in/otkling](https://www.linkedin.com/in/otkling/)

<br>

## My Projects
### 📝 열정페이 - 마이크로서비스 아키텍처 기반의 종합 핀테크 플랫폼(Java - Spring Boot)
https://github.com/InnerCircle-ICD3/fintech-BE
- 초기 설계 및 리더 역할을 담당하였으며, 각 모듈뿐만 아니라 필요 시 인프라까지 같이 신경쓰고 책임졌습니다.
- 결제 처리, 가맹점 관리, 사용자 관리 등 핀테크 생태계의 핵심 기능들을 독립적이고 확장 가능한 서비스로 구성했습니다.
- 테스트 주도 개발을 지향하여, 팀원들과 함께 Gitlab-CI/CD를 사용한 환경 설정을 통해 Side Effect를 줄이는 데 신경썼습니다.
- 멱등성 : Redis를 사용해 사용자의 요청에 빠르게 응답할 수 있으며 저장된 Token을 통해 중복 요청을 방지해 멱등성을 챙겼습니다.
- 보안 : 실제 결제에 중요한 정보들이 오고가는 만큼 단순한 Login이 아닌 Spring Security를 이용한 보안 처리가 되어 있습니다.
- 안정성/무결성 : 통합 예외 처리 및 예외 상황을 통일시키고, Transactional 어노테이션과 Redis 캐시를 통해 API반영 시점 보장과 DB 작업을 분리하였습니다.

### 🚆 한국철도기술연구원, 한국철도공사 산하 공공기관 프로젝트(Python - FastAPI / Gitlab)
- 전체 기간 : 24.02.15 ~ 25.12.31 / 24.12.02부터 입사 후 합류 - 국가연구자번호 1330-1778
- Language(Framework) : Python(FastAPI) / Backend Infra : Redis, Gitlab / DB : PostgreSQL, SQLAlchemy(ORM) / API Design Tool : Swagger(직접 일부를 Custom해서 사용)
- 보안 때문에 AWS 등 클라우드 서비스를 사용하지 않고, 사내 전용 서버에 인프라를 구축하였습니다.
- Redis 도입을 건의하여 Token Blacklist를 구현하고, 작업 탐색 속도를 단축시켰습니다. 또한 TTL을 상황에 맞게 커스텀하고, AOF를 활용해 데이터 복구가 가능하게 개발했습니다.
- 기존의 코드에서 라우터와 함수를 따로 분리하고, 대부분의 기능들을 모듈화하여 코드의 재사용성을 극대화시켰습니다.
- 테스트 주도 개발을 지향하며, 이를 위해 Gitlab-CI/CD, Docker-compose와 Pytest를 사용한 CI/CD 환경을 구축하여 하루에도 수백 개의 테스트코드가 사용됩니다.
- 공공기관의 데이터는 절대 노출되면 안 되는만큼 보안에도 신경썼고, 봉투 암호화 기법을 적용시켜 중요한 데이터가 노출되지 않게 하였습니다.
- 개인 블로그에 프로젝트를 진행하며 스스로 공부하고 배웠던 내용들을 정리하고 있습니다. 또한 프로젝트 진행과 동시에 기량향상을 위해 공부 및 개인 프로젝트를 진행하고 있습니다.

### 📝 주식 토론 게시판 백엔드 프로젝트(Java - Spring Boot)
[Repository Link](https://github.com/Acacian/Stock)

이 프로젝트는 한 달간 Java를 익히기 위해 진행된 개인 백엔드 프로젝트로, 주식 토론 게시판을 구현한 것입니다. 간단하지만 React를 사용해 프론트엔드 역시 혼자서 구현했습니다. Java 및 Spring Boot를 메인으로 사용하였고 Kafka, Redis, Eureka, WebSocket 등의 최신 백엔드 기술을 활용하여 개발되었습니다.

### 🎮 ONCORE 프로젝트(Javascript - Nest.js / Typescript - React.js)
[Repository Link](https://github.com/Acacian/ONCORE)

ONCORE는 동료들과 함께 실시간으로 소통하며 알고리즘을 학습할 수 있는 웹 서비스입니다. 알고리즘 학습을 더욱 효율적이고 재미있게 만들기 위해 다양한 실시간 협업 기능을 제공합니다. 실시간 협동 코드 에디터, 화상 채팅, 화이트보드 기능 등을 활용해 알고리즘 문제를 효과적으로 학습할 수 있습니다.

### 📚 DHPintos 프로젝트(C)
[Repository Link](https://github.com/Acacian/DHPintos)

PintOS 운영체제 프로젝트로, OS의 다양한 기능을 직접 구현하고, 시스템 콜, 스케줄링, 멀티스레딩 등의 기능을 테스트했습니다. C 언어를 사용하여 저수준 시스템 프로그래밍을 경험할 수 있는 프로젝트입니다.
