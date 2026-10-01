# Iamrabbyte

Independent Security Researcher focused on offensive web security, API security, and evidence-driven validation.

## Offensive Security Focus

- Web application penetration testing
- API attack surface analysis
- Authentication and authorization testing
- Access control and privilege-boundary testing
- JWT, session, and token security
- Account recovery and identity flows
- Multi-tenant isolation
- WebSocket and real-time application security
- Vulnerability validation
- Remediation and revalidation

## Selected Research

Public, sanitized case studies from authorized security testing:

- [WebSocket Credential Exposure](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/websocket-credential-exposure.md)
- [AVIF / Next.js Security Validation](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/avif-security-validation.md)
- [Account Recovery Bypass](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/account-recovery-bypass.md)
- [Cross-Tenant Authentication](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/cross-tenant-authentication.md)

## Sample Pentest Report

- [Sanitized Penetration Test Report](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/sample-pentest-report.md)

## Approach

I focus on reproducible evidence rather than scanner-only findings.

My typical workflow:

1. Define scope and safety boundaries
2. Establish a baseline or negative control
3. Map relevant application and API behavior
4. Reproduce suspected security issues
5. Validate impact using authorized synthetic accounts or test data
6. Separate confirmed behavior from theoretical exploitability
7. Restore modified test state where applicable
8. Document remediation guidance
9. Revalidate findings when possible

## Evidence Handling

Public research is intentionally sanitized.

Sensitive operational details such as the following are excluded where applicable:

- target domains and URLs
- credentials
- session tokens
- cookies
- verification values
- real user information
- exact exploit inputs
- sensitive endpoint details
- reusable attack material

The goal is to preserve technical methodology and evidence without exposing target-specific secrets or operational details.

## Responsible Testing

All published research is based on intentionally vulnerable environments, systems I own, or systems where I have explicit authorization to assess.

Where higher-impact exploitation cannot be safely demonstrated, I document it as unconfirmed rather than presenting theoretical impact as proven.

## Portfolio

[View the full Security Research Portfolio](https://github.com/Iamrabbyte/security-research-portfolio)
