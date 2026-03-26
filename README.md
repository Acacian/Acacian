# :octocat: Welcome to Acacian's Github!

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

---

# 구동하 (Dong-ha Koo)

**Backend Engineer — Distributed Architecture & AI Governance**

대규모 서비스 환경에서 **신뢰성과 데이터 정합성**을 고려한 백엔드 시스템 설계에  
관심이 있으며 신뢰성 있는 서비스 아키텍처와 장애 대응 구조를 설계하는 것을 목표로 합니다.

---

# 🌱 Open Source

### Spring AI

- Redis / Vector 관련 테스트 구조 개선 제안 및 피드백 PR  
  https://github.com/spring-projects/spring-ai/pull/3809

- DeepSeek tool call 응답에서 content=null 발생 시  
  호환성 문제를 방지하기 위한 fallback 처리 제안 PR  
  https://github.com/spring-projects/spring-ai/pull/3817
  
특히 Deepseek PR의 경우 Maintainer가 직접 본인한테 Assigned 해서 할당했으며,  
Backport로 반영될 정도로 의미있는 PR이었습니다.

### Aegis — Runtime Security for AI Agents

[![PyPI](https://img.shields.io/pypi/v/agent-aegis?color=blue)](https://pypi.org/project/agent-aegis/)
[![Tests](https://img.shields.io/badge/tests-3860%2B_passed-brightgreen)](https://github.com/Acacian/aegis)

AI 에이전트의 모든 LLM 호출과 tool 실행에 보안 guardrail + 정책 엔진 + 감사 로그를 적용하는 Python 라이브러리. 단독 설계·구현.

- **`import aegis; aegis.auto_instrument()`** 한 줄로 11개 프레임워크 런타임 보안 적용 (LangChain, CrewAI, OpenAI 등)
- Prompt injection 차단 (100+ 패턴), PII 탐지/마스킹 (12 카테고리), MCP rug-pull 탐지 (SHA-256 핀)
- 정책 평가 < 1ms, 필수 의존성 PyYAML 하나, 3,860+ tests, mypy strict

> https://github.com/Acacian/aegis

### kt-pattern
- Kotlin **Pattern Matching DSL Library**
- Kotlin `when` 분기의 한계를 보완하기 위한 선언형 패턴 매칭 라이브러리

---

# 📦 Projects

### PassionPay
MSA 기반 **핀테크 결제 플랫폼** (Project Lead)
Java / Spring Boot 기반 결제 서비스 아키텍처 설계 및 구현

### Insty
**운영 중인 라이브 서비스** 백엔드에서
대용량 미디어 업로드 처리 안정화 및 트러블슈팅 수행
외부 AI 추론 서비스 연동 기능 개발 참여

---

# 🎯 Engineering Focus

- 분산 환경에서의 서비스 신뢰성
- 장애 격리 및 복구 전략 (Circuit Breaker, Retry)
- 분산 시스템 데이터 정합성
- AI 에이전트 거버넌스 & 안전성
- 운영 환경 트러블슈팅 및 시스템 안정화

---

# 💼 Experience

**Koosstech**
Backend & DevOps Engineer (End-to-End Ownership)

**MementoAI**
Backend Engineer Intern

---

# 🎖 Military Service

**Republic of Korea Air Force**
미션 크리티컬 시스템 운영 환경 경험

---

# ✍️ Writing

기술적인 고민과 트러블슈팅 과정은 블로그에 정리하고 있습니다.

Tech Blog
https://victorica.tistory.com/

Topics

- Redis 없는 화이트박스 모니터링 설계
- 분산 시스템 데이터 정합성
- Circuit Breaker 구현과 장애 격리 전략

---

# 📫 Contact

📧 Email
koo9811@naver.com

💼 LinkedIn
https://linkedin.com/in/otkling
