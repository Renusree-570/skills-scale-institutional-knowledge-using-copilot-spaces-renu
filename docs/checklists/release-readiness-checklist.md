# Release Readiness Checklist

Use this checklist before scheduling a production release.

- [ ] Acceptance criteria met for all included backlog items
- [ ] All PRs merged and CI passes (unit, integration, lint)
- [ ] Security scans completed and no unmitigated critical findings
- [ ] Migration steps documented and validated (if applicable)
- [ ] Rollback plan documented and verified
- [ ] Observability in place: dashboards, alerts, and runbooks reviewed
- [ ] Release owner and on-call contacts identified
- [ ] Staging smoke tests executed and passed
- [ ] Communications draft created for stakeholders and support
- [ ] Post-release verification plan documented (who validates, how)
- [ ] Data instrumentation validated (metrics and event telemetry)
- [ ] Compliance and regulatory needs reviewed (if applicable)

Notes:
- For cross-team releases, TPM and Delivery Lead should sign-off on sequencing and dependency mitigation.
- For security or compliance-sensitive changes, Security Liaison must confirm sign-off prior to deployment.
