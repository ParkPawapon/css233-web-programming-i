# Security Policy

## Supported Versions

Security updates are applied to the latest revision of the default branch,
`main`. Earlier revisions are not maintained separately.

## Reporting a Vulnerability

Report suspected vulnerabilities through
[GitHub private vulnerability reporting](https://github.com/ParkPawapon/css233-web-programming-i/security/advisories/new).
Do not disclose security issues in public issues, discussions, or pull requests.

Include the affected file or component, reproduction steps, expected impact,
and any suggested remediation. Do not include active credentials, personal
data, or unrelated confidential information.

## Response Objectives

- Acknowledge a complete report within two business days.
- Complete initial severity triage within five business days.
- Prioritize remediation according to exploitability and impact.
- Coordinate disclosure only after a remediation is available.

## Repository Governance

The `main` branch is governed by an active repository ruleset that requires
pull requests, code-owner review, resolved review conversations, signed
commits, and linear history. Branch deletion and non-fast-forward updates are
blocked.

Only `ParkPawapon` has bypass permission, limited to pull-request workflows so
that exceptional changes retain a reviewable audit trail.

## Automated Controls

The repository uses secret scanning, push protection, Dependabot alerts, and
Dependabot security updates. Sensitive values must never be committed, even if
they are later removed from the visible branch history.
