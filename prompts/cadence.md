# Cadence Orchestration

Choose the next approved outreach step for a lead.

Inputs:
- lead status
- campaign cadence state
- last outreach event
- waiting period / send window
- approval policy

Rules:
- Only propose actions allowed by campaign policy.
- If approval is required, stop and draft a Slack approval request.
- If send is allowed, produce an email action summary and idempotency key.
