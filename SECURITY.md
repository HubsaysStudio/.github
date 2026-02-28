# Security Policy

## Supported Surfaces

This organization is intentionally small and static-first. The primary supported public surfaces are:

- `hubsays.com`
- Public organization profile content
- Public repositories explicitly marked as active

Private repos, local-only tooling, and experimental branches may change quickly and should not be treated as stable public interfaces.

## Reporting a Vulnerability

Please do not open public issues for suspected security problems.

Report concerns privately to:

- `support@hubsays.com`

Include:

- affected repository or page
- steps to reproduce
- impact summary
- screenshots or logs only if they do not contain secrets

## What to Avoid Sending

- access tokens
- API keys
- session cookies
- raw secrets from local `.env` files

If a secret is accidentally exposed anywhere, it should be treated as compromised and rotated immediately.

## Response Model

Security issues are handled with a pragmatic, evidence-first approach:

- confirm exposure
- reduce blast radius
- rotate secrets if needed
- remove exposed artifacts
- document the control change that prevents recurrence
