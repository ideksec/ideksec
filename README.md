# Greg

Security leader focused on secure AI adoption — the governance, identity, and runtime controls that let an enterprise say yes to agents. I lead global Security Operations and IAM at a cloud-native fintech, where I assess the security risks of LLM and agentic adoption across the business — identity and access, tool permissions, data exposure, prompt injection.

**Interested in what happens when both sides have agents.**

The projects below are where I work through the harder versions of these problems in the open.

---

## Current work

### [Bellwether](https://github.com/ideksec/bellwether)

A CI/CD gate for AI agent skills: run a candidate skill repeatedly in an instrumented sandbox, record what the agent actually does, measure how its behavior drifts between runs, and gate the release on evidence rather than prose review. An experiment — it warns, it does not vouch.

### [Agent Identity Broker](https://github.com/ideksec/agent-identity-broker)

An experiment in workload identity and authorization for agents: SPIFFE/SPIRE identity in, short-lived policy-checked credentials out, with on-behalf-of user delegation and an audit trail — instead of a long-lived API key in an environment variable. Proof of concept, not production software.

### [NoScope](https://github.com/ideksec/NoScope)

Time-boxed autonomous agent orchestration: spec in, runnable MVP out, guaranteed to stop. Built in part to understand the systems I want to secure from the inside — capability gating, sandboxing, observability, and verification that runs real commands instead of trusting the model.

## Exploring

- Secure enterprise adoption of AI agents — governance that enables rather than blocks
- Agent identity and delegated authorization
- Runtime observability and control for autonomous systems
- Supply-chain security for agent skills and plugins
- How offense and defense change when both sides field agents

## Also

Data analysis and sabermetrics.

## Contact

[Say hi](https://github.com/ideksec/ideksec/issues)
