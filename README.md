# Acacian

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

> **Backend engineer — reliable, secure infrastructure for AI systems**  
> distributed reliability · data consistency · runtime correctness, security & cost accuracy for LLM / agent platforms

🌍 **Based in South Korea — open to global roles (remote or relocation)**

<details>
<summary>🇰🇷 한국어 소개</summary>

대규모 서비스 환경에서 **신뢰성과 데이터 정합성**을 고려한 백엔드를 설계하고,  
**LLM/에이전트 플랫폼의 런타임 정확성·보안·비용**을 다룹니다. 리모트·이주 모두 가능하며 글로벌 포지션을 찾고 있습니다.

</details>

---

## 🔧 Merged upstream — billing correctness in LiteLLM

[PR #36281](https://github.com/BerriAI/litellm/pull/36281) → merged as [**#39441**](https://github.com/BerriAI/litellm/pull/39441) · 26 days · commit authorship preserved

Our production gateway runs on a LiteLLM fork, where xAI calls were billed from an internal rate table nobody could keep current — 7 server-side tool counters with 1 priced, and one model billed at multiples of real cost for 6+ weeks. I made the cost the provider itself reports the source of truth, and fenced the boundary that now trusts a response body: documented shape only, else fall back. `NaN` mattered most — it passes *every* budget threshold comparison, so one bad field disables budget enforcement for that key entirely.

```mermaid
flowchart LR
  R["xAI response"] --> V{"reported cost:<br/>documented shape?"}
  V -- yes --> P["bill the reported cost"]
  V -- "missing / NaN / out of range" --> F["fall back to<br/>tokens × internal rate table"]
```

<sub>Merged into a repo with 3,000+ open PRs where outside contributors account for under 2% of merges. Also filed upstream — **Spring AI**: DeepSeek tool-call `content=null` fallback ([#3817](https://github.com/spring-projects/spring-ai/pull/3817)) · RedisVectorStore `BuilderCustomizer` ([#3809](https://github.com/spring-projects/spring-ai/pull/3809), in review).</sub>

## 🏗 Current work — enterprise LLM gateway / AI-security platform

In production today at **Soosan**: proxy request lifecycle, DLP and guardrail enforcement, cross-provider correctness, policy & audit paths, load and reliability testing.

## 🛡 Built — Aegis, runtime security for AI agents

[![PyPI](https://img.shields.io/pypi/v/agent-aegis?color=blue)](https://pypi.org/project/agent-aegis/) · [github.com/Acacian/aegis](https://github.com/Acacian/aegis)

Solo-designed Python library that enforces guardrails, a policy engine, and audit logging on every LLM call and tool execution — at the CI/CD layer. Auto-instruments 12 AI frameworks (LangChain, CrewAI, OpenAI, Anthropic, LiteLLM, Google ADK …).

<sub>Integrates as a third-party guardrail provider for Pydantic AI and LiteLLM · listed in [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) and [Awesome-LM-SSP](https://github.com/CryptoAILab/Awesome-LM-SSP).</sub>

## 📦 Also shipped

**CandyPod** — backend engineer on a mobile matching app, live on the App Store and Google Play.

## 🎯 Focus

`distributed reliability` · `fault isolation & recovery` · `data consistency` · `LLM / agent runtime security` · `cross-provider correctness & cost accuracy` · `AI-native system design`

## 💼 Experience

- **Soosan** (current)
- **Koosstech** — Backend & DevOps (E2E ownership)
- **MementoAI** — Backend (intern)
- **ROK Air Force** — mission-critical systems operations

<sub>Earlier: **PassionPay** — MSA fintech payments platform (lead), payment-service architecture & consistency design.</sub>

## ✍️ Writing · 📫 Contact

Tech blog → https://victorica.tistory.com/ &nbsp;·&nbsp; 📧 koo9811@naver.com &nbsp;·&nbsp; 💼 [linkedin.com/in/otkling](https://linkedin.com/in/otkling)
