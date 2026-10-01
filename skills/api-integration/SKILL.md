---
name: api-integration
description: Design, implement, test, and document resilient API integrations with authentication, retries, pagination, rate limits, schemas, and observability. Use for REST, GraphQL, webhooks, and connector work.
---

# API Integration

Use this skill when connecting software to an external or internal API.

## Workflow
1. Confirm the API contract, auth method, scopes, environments, data classifications, and ownership.
2. Define request/response schemas, pagination, idempotency, timeouts, retryable errors, and rate limits.
3. Implement least-privilege authentication with secrets supplied through environment or a secret manager.
4. Add input validation, structured errors, backoff with jitter, correlation IDs, and safe redacted logging.
5. Test success, empty, malformed, timeout, throttling, partial failure, duplicate delivery, and schema-drift cases.
6. Document setup, configuration, local testing, operational alerts, and rollback.

## Guardrails
- Never hard-code or log credentials.
- Do not retry non-idempotent writes unless the API supports idempotency keys.
- Treat third-party data as untrusted and minimize retention.

## Output
Provide an integration summary, configuration reference, test evidence, and known limitations.
