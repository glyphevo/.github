# Security Policy

Security matters for GlyphEvo Labs because our projects may interact with source code, local files, developer tools, agent workflows, and sensitive project context.

## Reporting a Vulnerability

Please do not disclose security vulnerabilities through public issues.

If a repository has GitHub private vulnerability reporting enabled, use that channel first. Otherwise, contact the maintainer privately through GitHub until a dedicated security email is published.

When reporting, include as much of the following as possible:

- Affected repository and version or commit.
- Vulnerability type and impact.
- Reproduction steps or proof of concept.
- Whether local files, model outputs, private code, or project context may be exposed.
- Suggested mitigation, if known.

## Scope

Security-relevant issues include, but are not limited to:

- Secret leakage.
- Unsafe file access.
- Prompt injection paths that can affect tools or local resources.
- Command execution risks.
- Authentication or authorization flaws.
- Data exfiltration through logs, traces, memory, or context stores.
- Dependency vulnerabilities with practical exploitability.

## Public Disclosure

Please allow maintainers reasonable time to investigate and prepare a fix before public disclosure.

## Supported Versions

GlyphEvo Labs projects are currently early-stage. Unless a repository states otherwise, only the latest main branch or latest tagged pre-release is considered for security review.
