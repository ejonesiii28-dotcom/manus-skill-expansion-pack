---
name: security-review
description: Defensive application and repository security review covering secrets, dependencies, auth, input handling, privacy, and deployment risks. Use for audits, hardening, and pre-release checks.
---

# Security Review

Use this skill for authorized defensive review only.

## Workflow
1. Establish scope, environment, threat model, data sensitivity, and out-of-scope systems.
2. Inventory entry points, identities, secrets, dependencies, storage, network boundaries, and privileged operations.
3. Review authentication, authorization, validation, injection risks, SSRF, CSRF, file handling, logging, and error disclosure.
4. Check dependency and secret scanning results; distinguish confirmed findings from hypotheses.
5. Reproduce issues safely with non-destructive tests and minimal data.
6. Rank findings by impact, exploitability, exposure, and remediation effort; propose fixes and retest criteria.

## Guardrails
- Do not exploit, persist, exfiltrate, or modify systems beyond written scope.
- Do not print secrets; rotate exposed credentials through the proper owner workflow.
- Avoid destructive proof-of-concept payloads.

## Output
Use: **Scope**, **Executive risk summary**, **Findings** (severity, evidence, impact, remediation), **Positive controls**, and **Retest plan**.
