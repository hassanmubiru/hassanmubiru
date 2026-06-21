# Security Policy

The security of these projects — including StreetJS, Vibra, Afrchat, and SCMINER — is taken seriously. This policy explains which versions receive security updates and how to report a vulnerability responsibly.

## Supported Versions

Projects on the pre-1.0 line ship security fixes on the latest minor release. Once a project reaches 1.0, the most recent minor release receives security updates.

| Version | Supported          |
| ------- | ------------------ |
| Latest `0.y.z` (pre-release) | ✅ |
| Older `0.y.z` | ❌ |
| `>= 1.0` latest minor | ✅ |
| `>= 1.0` older minor | ❌ |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions, or pull requests.**

Instead, report them privately using GitHub's coordinated disclosure workflow:

1. Go to the **Security** tab of the affected repository.
2. Click **Report a vulnerability** to open a private security advisory.
3. Include the details below.

Alternatively, contact the maintainer through their GitHub profile at https://github.com/hassanmubiru and request a private channel.

### What to include

- A clear description of the vulnerability and its impact.
- The affected project, version, and environment.
- Step-by-step reproduction instructions or a proof of concept.
- Any relevant logs, stack traces, or configuration.
- Suggested remediation, if you have one.

## Response Process and Timeline

- **Acknowledgement:** within 3 business days of your report.
- **Triage and validation:** within 7 business days, including a severity assessment.
- **Status updates:** at least every 7 days while the issue is open.
- **Fix and disclosure:** a fix is prepared and released as a patch; a security advisory and CHANGELOG entry are published once users have had a reasonable window to upgrade.

## Disclosure Policy

This project follows coordinated disclosure. Please give the maintainer a reasonable opportunity to release a fix before any public disclosure. Reporters who follow this policy will be credited in the security advisory unless they request otherwise.

## Scope

In scope: source code, build and release pipelines, and dependencies as shipped in the affected repositories. Out of scope: vulnerabilities in third-party services, social-engineering attacks, and issues requiring privileged local access already granted to the user.
