---
name: automation-orchestration
description: Design reliable automations, scheduled jobs, event-driven workflows, retries, approvals, observability, and safe recovery. Use for recurring tasks, monitors, bots, and multi-step pipelines.
---

# Automation Orchestration

Use this skill to design unattended work that is safe, observable, and maintainable.

## Workflow
1. Define trigger, inputs, outputs, frequency, owner, permissions, SLA, and failure budget.
2. Map the workflow as idempotent steps with explicit state and checkpoints.
3. Separate reversible actions from consequential actions; require approval before publication, deletion, payments, access changes, or official submissions.
4. Add timeouts, bounded retries with backoff, deduplication, dead-letter handling, alerts, and run correlation IDs.
5. Minimize secrets and permissions; redact sensitive data from logs.
6. Test duplicate events, partial completion, stale inputs, provider outage, schema change, and recovery.
7. Document disablement, replay, rollback, and ownership.

## Output
Use: **Trigger**, **State model**, **Steps**, **Failure handling**, **Permissions**, **Observability**, **Approval gates**, and **Runbook**.
