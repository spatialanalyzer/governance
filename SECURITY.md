# Security Policy

## Report vulnerabilities privately

Do not disclose a suspected vulnerability in a public issue, discussion, pull
request, chat, or social-media post.

Use **GitHub private vulnerability reporting** in the affected repository.
If that feature is not available, open a public issue containing no sensitive
details and ask the maintainers to provide a private reporting channel.

Include, when available:

- the affected repository, component, and version;
- the affected SpatialAnalyzer version;
- a description of the impact;
- reproducible steps or a proof of concept;
- relevant logs with secrets and proprietary data removed; and
- whether anyone else has been notified.

The project has not established a guaranteed acknowledgment or remediation
time.

## Initial triage

The Project Founder and Lead Architect and Hexagon Primary Focal are the
initial security triage contacts. Access to a report will be limited to people
needed to evaluate and remediate it.

Reports that plausibly affect SpatialAnalyzer, the SA SDK, Hexagon licensing
controls, or another Hexagon product must be referred privately to the Hexagon
Primary Focal. The project will coordinate with Hexagon before publicly
disclosing Hexagon product details.

The triage participants will determine whether a report primarily concerns:

1. Briosa or another organization-hosted open-source component;
2. the integration boundary between Briosa and SpatialAnalyzer;
3. SpatialAnalyzer or another Hexagon-controlled component; or
4. a third-party dependency or service.

That classification may change as investigation proceeds. When ownership is
unclear, the project and Hexagon focal will coordinate privately rather than
prematurely publishing the report.

## Handling and disclosure

The maintainers may use a GitHub repository security advisory to discuss and
prepare a fix. Reporters are asked to allow a reasonable opportunity for
investigation and coordinated remediation before disclosure.

Credit will be offered when appropriate and desired, subject to safety, legal,
and confidentiality restrictions.

## Supported versions

A complete supported-version policy has not been established. Individual
releases should identify the Briosa and SpatialAnalyzer versions tested
together. Until a policy is published:

- security fixes are provided on a best-effort basis;
- maintainers may prioritize the newest affected supported release; and
- users should not infer support for an unlisted SpatialAnalyzer version.

## Product boundary

This policy covers open-source projects hosted by the SpatialAnalyzer GitHub
organization. It does not replace Hexagon's official vulnerability-reporting
or product-support processes. A valid SpatialAnalyzer license and functioning
installation are required for Briosa to perform SpatialAnalyzer operations.
