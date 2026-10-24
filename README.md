<h2>구동하 (Dongha Koo)</h2>

Backend engineer on an enterprise LLM gateway — keeping security checks, billing, and audit logs consistent with what requests actually do.

정합성이 걸린 자리에서 트레이드오프를 정하고 그 결정을 책임지는 일을 합니다.  
터지면서 알려주는 실패보다, 조용히 틀리는 실패를 찾는 데 시간을 씁니다.

[Blog](https://victorica.tistory.com/) · [LinkedIn](https://linkedin.com/in/otkling) · [Email](mailto:koo9811@naver.com)

## Work

| Organization | Position | Period |
|:---|:---|:---|
| [Soosan INT](https://www.soosanint.com/) | Backend Engineer — eSafeAI, an enterprise LLM gateway | 26.05 ~ now |
| Koosstech | Backend & DevOps — R&D, closed-network ERP with KRRI | 24.12 ~ 26.05 |
| Memento AI | Backend Developer (intern) | 24.10 ~ 24.11 |

At eSafeAI:

- Designed MCP connectors so tool calls go through the existing inspection and billing path, failing closed
- Find and fix places where inspection, billing, or audit records drift from what a request actually did
- Load-limit testing and on-site deployment for financial-sector customers

## Open Source (Merged PRs Only)

| Project | Contribution | Merged |
|:---|:---|:---|
| [**litellm**](https://github.com/BerriAI/litellm) | Billing xAI from the cost it reports instead of recomputing it ([#36281](https://github.com/BerriAI/litellm/pull/36281) → merged as [#39441](https://github.com/BerriAI/litellm/pull/39441)) | 26.09 |
| [**litellm**](https://github.com/BerriAI/litellm) | Keeping provider response headers on SDK streaming errors ([#41528](https://github.com/BerriAI/litellm/pull/41528)) | 26.10 |

## Side Projects

| Project | What it does |
|:---|:---|
| [**CandyPod**](https://apps.apple.com/kr/app/candypod/id6752270848) | Backend for a K-POP fan matching app, live on the App Store and Google Play. |
| [**Aegis**](https://github.com/Acacian/aegis) | Guardrails and audit logging on LLM calls and tool execution. [PyPI](https://pypi.org/project/agent-aegis/) |

## Writing

- [GPT가 같은 점검을 반복할 때, 범위를 다시 잡아 찾은 Docker ip_forward 문제](https://victorica.tistory.com/47)
- [[LiteLLM PR 기여] xAI 비용 산정이 실제 청구액과 어긋나는 버그 고치기](https://victorica.tistory.com/46)
- [RDB 동시성 제어와 상태 기반 설계로 구현한 실시간 매칭 시스템](https://victorica.tistory.com/32)
- [관제 인력을 아키텍처로 대체하다 — Redis 없는 폐쇄망 모니터링 시스템 설계](https://victorica.tistory.com/29)
- [인증 경로 재설계로 로그인 API 지연 개선](https://victorica.tistory.com/14)

<sub>Java · Python · Spring Boot · FastAPI · PostgreSQL · Redis · Kafka · Docker</sub>

<sub>Seoul, South Korea · open to remote or relocation</sub>
