# Greg

Security leader working on the problems agentic AI creates for the enterprise — and on what it takes to adopt agents without giving up visibility or control. Background in security architecture, identity, and runtime security; currently spending my time building small, honest experiments against the sharpest of those problems.

**Interested in what happens when both sides have agents.**

---

## Current work

### [Bellwether](https://github.com/ideksec/bellwether)

A CI/CD gate for AI agent skills. A skill is distributed like code and reviewed like prose, but what it *does* depends on which model reads it and when. Bellwether runs a candidate skill repeatedly in an instrumented sandbox, records what the agent actually did — tool calls, file access, network egress, planted-canary leaks — measures how much behavior varies between runs, and renders a release verdict against a policy the repo owner controls. It is deliberately modest about what evidence can claim: N runs are a distribution, not a proof. It warns; it does not vouch. Early and moving fast.

### [Agent Identity Broker](https://github.com/ideksec/agent-identity-broker)

An experiment in workload identity and authorization for autonomous and user-delegated agents. The default today is handing an agent a long-lived, over-scoped API key. This explores the alternative: SPIFFE/SPIRE workload identity in, short-lived policy-checked credentials out, with on-behalf-of user context and an audit record for every decision. A hands-on way to work through the primitives — SPIFFE, OIDC federation, OPA — that agentic systems will increasingly depend on. Proof of concept, not production software.

### [NoScope](https://github.com/ideksec/NoScope)

Time-boxed autonomous agent orchestration: spec in, runnable MVP out, guaranteed to stop. Built in part to understand from the inside the systems I want to secure — capability-gated tools instead of raw shell access, optional Docker sandboxing, a full JSONL event log of every action, and verification that executes real commands rather than trusting the model's own claim of success.

## Exploring

- Secure enterprise adoption of AI agents
- Agent identity and delegated authorization
- Runtime observability and control for autonomous systems
- Supply-chain security for agent skills and plugins
- How offense and defense change when both sides field agents

## Also

Data analysis and sabermetrics.

## Contact

[Say hi](https://github.com/ideksec/ideksec/issues)
