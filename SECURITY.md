# Security policy

Andesyte builds security tooling, so we take vulnerabilities in our own code seriously.

## Reporting a vulnerability

Please do not open public issues for security reports.

Email **hello@foundationmachines.com** with the subject line `[security]` and:

- A description of the issue and its potential impact.
- Steps to reproduce, or a proof-of-concept.
- Any suggested remediation.

We aim to acknowledge receipt within two business days and provide a triage decision within five business days.

If you prefer encrypted communication, request our PGP key in your initial email.

## Scope

In scope:

- Source code in repositories owned by the `andesyte-oss` GitHub organization.
- The Sebastion AI GitHub App (https://github.com/apps/sebastion-code-security) and its production endpoints.
- foundationmachines.ai and any subdomains we operate.

Out of scope:

- Third-party services we depend on (report to those vendors directly).
- Findings that require a compromised end-user device or social engineering.
- Denial of service via volumetric attacks against shared infrastructure.

## Coordinated disclosure

We follow a coordinated disclosure model. We will work with you on a fix and credit you in the advisory unless you ask to remain anonymous. Please give us reasonable time to remediate before any public disclosure.

## Safe harbor

We will not pursue legal action against researchers who:

- Make a good-faith effort to follow this policy.
- Avoid privacy violations, destruction of data, and interruption of service.
- Only interact with accounts they own or have explicit permission to test.
