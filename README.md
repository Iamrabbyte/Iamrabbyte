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

- [WebSocket Credential Exposure](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/F-001-websocket-credential-exposure.md)
- [AVIF / Next.js Security Validation](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/F-002-avif-security-validation.md)
- [Account Recovery Bypass](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/F-003-account-recovery-bypass.md)
- [Cross-Tenant Authentication](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/case-studies/F-005-cross-tenant-authentication.md)

## Sample Pentest Report

- [Sanitized Penetration Test Report](https://github.com/Iamrabbyte/security-research-portfolio/blob/main/sample-pentest-report.md)

## Approach

I focus on reproducible evidence rather than scanner-only findings.

My typical workflow:

1. Define scope and safety boundaries
2. Establish a baseline or negative control
3. Map the relevant application or API behavior
4. Reproduce suspected security issues
5. Validate impact using authorized synthetic accounts or test data
6. Separate confirmed behavior from theoretical exploitability
7. Restore modified test state where applicable
8. Document remediation guidance
9. Revalidate findings after remediation when possible

## Evidence Handling

Public research is intentionally sanitized.

I exclude sensitive operational details such as:

- target domains and URLs
- credentials
- session tokens
- cookies
- verification values
- real user information
- exact exploit inputs
- sensitive endpoint details

This allows the technical methodology and findings to be reviewed without exposing reusable attack material or target-specific secrets.

## Responsible Testing

All published research is based on intentionally vulnerable environments, systems I own, or systems where I have explicit authorization to assess.

Where higher-impact exploitation cannot be safely demonstrated, I document it as unconfirmed rather than presenting theoretical impact as proven.

## Portfolio

[View the full Security Research Portfolio](https://github.com/Iamrabbyte/security-research-portfolio)
