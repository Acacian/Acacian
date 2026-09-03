# Acacian

Backend engineer. Reliability, data consistency, and runtime security for LLM / agent platforms.
Based in South Korea — open to remote or relocation.

**Now** — backend for an enterprise LLM gateway / AI-security platform at **Soosan**: proxy request lifecycle, DLP and guardrail enforcement, cross-provider correctness, policy and audit paths.

**Upstream** — [litellm #36281](https://github.com/BerriAI/litellm/pull/36281) → merged as [#39441](https://github.com/BerriAI/litellm/pull/39441). xAI calls were billed from an internal rate table nobody could keep current, so I made the cost the provider itself reports the source of truth, and fenced the boundary that now trusts a response body: documented shape only, else fall back. Rejecting `NaN` there was the part that mattered — it passes every budget threshold comparison, so one bad field disables budget enforcement for a key entirely. Also Spring AI [#3817](https://github.com/spring-projects/spring-ai/pull/3817), [#3809](https://github.com/spring-projects/spring-ai/pull/3809).

**Aegis** — [PyPI](https://pypi.org/project/agent-aegis/) · [source](https://github.com/Acacian/aegis). Python library that puts guardrails, a policy engine, and audit logging on every LLM call and tool execution. Auto-instruments 12 frameworks; a third-party guardrail provider for Pydantic AI and LiteLLM.

**Before** — Koosstech (backend & DevOps, E2E ownership) · MementoAI (backend, intern) · ROK Air Force (mission-critical systems operations) · PassionPay (MSA fintech payments, lead). CandyPod — backend on a mobile matching app, live on the App Store and Google Play.

Python · Java / Spring · Kafka · Redis · Docker

[Blog](https://victorica.tistory.com/) · koo9811@naver.com · [LinkedIn](https://linkedin.com/in/otkling)
